<script setup>
import { ref } from 'vue';

const activeTab = ref("Home")

function setActiveTab(tab) {
	activeTab = tab
}

const showMenu = ref(false)
const toggleMenu = () => {
	showMenu.value = !showMenu.value
}
</script>

<template>
	<nav
		class="bg-white dark:bg-gray-900 fixed w-full relative z-10 top-0 start-0 border-b border-gray-200 dark:border-gray-600">
		<div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
			<a href="/" class="flex items-center space-x-3 rtl:space-x-reverse">
				<i class="fa-solid fa-hammer fa-xl text-gray-500"></i>
				<span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Jose HVAC
					Services</span>
			</a>
			<div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
				<button class="md:hidden z-100 relative" @click="toggleMenu">
					<svg class="w-6 h-6" fill="none" stroke="white" viewBox="0 0 24 24">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
							d="M4 6h16M4 12h16M4 18h16" />
					</svg>
				</button>
			</div>
			<div id="navbar-sticky" :class="[
				'w-full md:flex md:w-auto md:order-2 mt-4 md:mt-0',
				showMenu ? 'flex flex-col gap-4' : 'hidden',
			]">
				<ul class="flex flex-col md:flex-row gap-4">
					<li @click="setActiveTab('Home')">
						<a href="#hero"
							:class="['block py-2 px-3 rounded-sm md:bg-transparent md:p-0', activeTab == 'Home' ? 'bg-blue-700 text-white md:dark:text-blue-500 md:text-blue-700' : 'text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700']">Home</a>
					</li>
					<li @click="setActiveTab('Services')">
						<a href="#services"
							:class="['block py-2 px-3 rounded-sm md:bg-transparent md:p-0', activeTab == 'Services' ? 'bg-blue-700 text-white md:dark:text-blue-500 md:text-blue-700' : 'text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700']">Services</a>
					</li>
					<li @click="setActiveTab('Reviews')">
						<a href="#reviews"
							:class="['block py-2 px-3 rounded-sm md:bg-transparent md:p-0', activeTab == 'Reviews' ? 'bg-blue-700 text-white md:dark:text-blue-500 md:text-blue-700' : 'text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700']">Reviews</a>
					</li>
					<li @click="setActiveTab('FAQs')">
						<a href="#faqs"
							:class="['block py-2 px-3 rounded-sm md:bg-transparent md:p-0', activeTab == 'FAQs' ? 'bg-blue-700 text-white md:dark:text-blue-500 md:text-blue-700' : 'text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700']">FAQs</a>
					</li>
					<li @click="setActiveTab('Contact')">
						<a href="#contact"
							:class="['block py-2 px-3 rounded-sm md:bg-transparent md:p-0', activeTab == 'Contact' ? 'bg-blue-700 text-white md:dark:text-blue-500 md:text-blue-700' : 'text-gray-900 hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700']">Contact</a>
					</li>
					<li>
						<a href="tel:240-802-9076"
							class="bg-red-600 text-gray-900 hover:bg-red-500 py-2 px-3 rounded-full text-xs font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg me-3 cursor-pointer"><i
								class="fas fa-phone"></i> (240) 802-9076</a>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</template>