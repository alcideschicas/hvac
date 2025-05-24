<script setup>
import jose from '@/assets/jose.png';
import eliseo from '@/assets/eliseo.jpeg';
import nierah from '@/assets/nierah.png';
</script>

<template>
  <section className="bg-white dark:bg-gray-900 py-12">
    <div className="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
      <div className="mx-auto mb-8 max-w-screen-sm lg:mb-16">
        <h2 className="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Our Team</h2>
      </div>
      <div className="grid gap-4 lg:gap-4 sm:grid-cols-3 md:grid-cols-3 lg:grid-cols-3">
        <div className="text-center text-gray-500 dark:text-gray-400">
          <img className="mx-auto mb-4 w-auto h-36 rounded-full" :src="jose" alt="Jose" />
          <h3 className="mb-1 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            <a href="#">Jose Romero</a>
          </h3>
          <p>HVAC Lead Technician</p>
        </div>
        <div className="text-center text-gray-500 dark:text-gray-400">
          <img className="mx-auto mb-4 w-auto h-36 rounded-full" :src="eliseo" alt="Cheyo" />
          <h3 className="mb-1 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            <a href="#">Cheyo</a>
          </h3>
          <p>HVAC Apprentice</p>
        </div>
        <div className="text-center text-gray-500 dark:text-gray-400">
          <img className="mx-auto mb-4 w-auto h-36 rounded-full" :src="nierah" alt="Nierah" />
          <h3 className="mb-1 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
            <a href="#">Nierah</a>
          </h3>
          <p>Customer Service</p>
        </div>
      </div>
    </div>
  </section>
</template>