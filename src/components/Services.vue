<template>
	<div class="bg-gray-700 p-4 pb-15" id="services">
		<div aria-hidden="true" class="absolute inset-0 h-max w-full m-auto grid grid-cols-2 -space-x-52 opacity-20">
			<div class="blur-[106px] h-56 bg-gradient-to-br  to-purple-400 from-blue-700"></div>
			<div class="blur-[106px] h-32 bg-gradient-to-r from-cyan-400  to-indigo-600"></div>
		</div>
		<div class="max-w-7xl mx-auto px-6 md:px-12 xl:px-6">
			<div class="mt-15 text-gray-100">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-20 h-20 text-secondary">
					<path fill-rule="evenodd" d="M9 4.5a.75.75 0 01.721.544l.813 2.846a3.75 3.75 0 002.576 2.576l2.846.813a.75.75 0 010 1.442l-2.846.813a3.75 3.75 0 00-2.576 2.576l-.813 2.846a.75.75 0 01-1.442 0l-.813-2.846a3.75 3.75 0 00-2.576-2.576l-2.846-.813a.75.75 0 010-1.442l2.846-.813A3.75 3.75 0 007.466 7.89l.813-2.846A.75.75 0 019 4.5zM18 1.5a.75.75 0 01.728.568l.258 1.036c.236.94.97 1.674 1.91 1.91l1.036.258a.75.75 0 010 1.456l-1.036.258c-.94.236-1.674.97-1.91 1.91l-.258 1.036a.75.75 0 01-1.456 0l-.258-1.036a2.625 2.625 0 00-1.91-1.91l-1.036-.258a.75.75 0 010-1.456l1.036-.258a2.625 2.625 0 001.91-1.91l.258-1.036A.75.75 0 0118 1.5zM16.5 15a.75.75 0 01.712.513l.394 1.183c.15.447.5.799.948.948l1.183.395a.75.75 0 010 1.422l-1.183.395c-.447.15-.799.5-.948.948l-.395 1.183a.75.75 0 01-1.422 0l-.395-1.183a1.5 1.5 0 00-.948-.948l-1.183-.395a.75.75 0 010-1.422l1.183-.395c.447-.15.799-.5.948-.948l.395-1.183A.75.75 0 0116.5 15z" clip-rule="evenodd"></path>
				</svg>
				<h2 class="my-3 text-2xl font-bold text-white md:text-4xl">Our Services</h2>
				<p class="text-gray-300">We provide top-quality heating, ventilation, and air conditioning (HVAC)
					services to keep your home or business comfortable year-round. Our expert technicians specialize in:
				</p>
			</div>
			<div
				class="mt-10 grid divide-x divide-y  divide-gray-700 overflow-hidden  rounded-3xl border text-gray-600 border-gray-700 sm:grid-cols-2 lg:grid-cols-4 lg:divide-y-0 xl:grid-cols-4">
				<div
					class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl  hover:shadow-gray-600/10">
					<div class="relative space-y-8 py-12 p-8">
						<i loading="lazy"
							class="fas fa-temperature-arrow-up fa-3x bg-gradient-to-r from-blue-600 via-green-500 to-indigo-400 text-transparent bg-clip-text"></i>
						<div class="space-y-2">
							<h5 class="text-xl font-semibold text-white transition group-hover:text-secondary">Heating
								Services</h5>
							<p class="text-gray-300">Furnace installation, repair, and maintenance for a warm, cozy
								winter.</p>
						</div>
					</div>
				</div>
				<div
					class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
					<div class="relative space-y-8 py-12 p-8">
						<i loading="lazy"
							class="fas fa-snowflake fa-3x bg-gradient-to-r from-blue-600 via-green-500 to-indigo-400 text-transparent bg-clip-text"></i>
						<div class="space-y-2">
							<h5 class="text-xl font-semibold text-white transition group-hover:text-secondary">Cooling
								Services</h5>
							<p class="text-gray-300">AC installation, repair, and tune-ups to keep you cool in summer.
							</p>
						</div>
					</div>
				</div>
				<div
					class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10">
					<div class="relative space-y-8 py-12 p-8">
						<i loading="lazy"
							class="fas fa-wind fa-3x bg-gradient-to-r from-blue-600 via-green-500 to-indigo-400 text-transparent bg-clip-text"></i>
						<div class="space-y-2">
							<h5 class="text-xl font-semibold text-white transition group-hover:text-secondary">Indoor
								Air Quality</h5>
							<p class="text-gray-300">Air purifiers, humidifiers, and ventilation solutions for cleaner,
								healthier air.</p>
						</div>
					</div>
				</div>
				<div class="group relative bg-gray-800 transition hover:z-[1] hover:shadow-2xl hover:shadow-gray-600/10 pb-8">
					<div class="relative space-y-8 pt-12 p-8">
						<i loading="lazy"
							class="fas fa-triangle-exclamation fa-3x bg-gradient-to-r from-blue-600 via-green-500 to-indigo-400 text-transparent bg-clip-text"></i>
						<div class="space-y-2">
							<h5 class="text-xl font-semibold text-white transition group-hover:text-secondary">Emergency
								Repairs</h5>
							<p class="text-gray-300">Fast, 24/7 service when you need it most.</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>