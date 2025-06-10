<script setup></script>

<template>
	<section class="bg-white" id="contact">
		<div class="py-8 lg:py-16 px-4 mx-auto max-w-screen-md">
			<h2 class="mb-4 text-4xl tracking-tight font-extrabold text-center text-dark">Contact Us</h2>
			<p class="mb-8 lg:mb-16 font-light text-center text-gray-500 sm:text-xl">Need expert HVAC services?
				Whether it's a repair, installation, or maintenance, our team is here to help! Fill out the form below,
				and we'll get back to you as soon as possible.</p>
			<form action="/thank-you" netlify-honeypot="bot-field" method="POST" class="space-y-8" name="contact" data-netlify="true">
				<div>
					<label for="name" class="block mb-2 text-sm font-bold text-gray-900">Name</label>
					<input type="text" id="name" name="name"
						class="block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500"
						placeholder="Full name" required />
				</div>
				<div>
					<label for="email" class="block mb-2 text-sm font-bold text-gray-900">Your email</label>
					<input type="email" id="email" name="email"
						class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5"
						placeholder="name@email.com" required />
				</div>
				<div>
					<label for="subject" class="block mb-2 text-sm font-bold text-gray-900">Subject</label>
					<input type="text" id="subject" name="subject"
						class="block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500"
						placeholder="Let us know how we can help you" required />
				</div>
				<div class="sm:col-span-2">
					<label for="message" class="block mb-2 text-sm font-bold text-gray-900">Your message</label>
					<textarea id="message" rows="6" name="message"
						class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-50"
						placeholder="Leave a comment..."></textarea>
				</div>
				<input type="hidden" name="form-name" value="contact" />
				<button type="submit"
					class="w-full bg-gradient-to-r from-blue-500 to-indigo-600 text-white font-semibold py-3 rounded-2xl shadow-lg hover:from-blue-600 hover:to-indigo-700 transition-all duration-300 ease-in-out transform hover:scale-105">Submit</button>
			</form>
		</div>
	</section>
</template>