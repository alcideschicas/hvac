<script setup>
  import { ref } from "vue";

  const reviews = ref([
    {
      id: 1,
      avatar: 'https://randomuser.me/api/portraits/men/1.jpg',
      name: 'Gerardo Torres',
      rating: 5,
      comment: 'Excellent service and professionalism. My air conditioner stopped working in the middle of summer, and they arrived quickly to fix it. Highly recommended!'
    },
    {
      id: 2,
      avatar: 'https://randomuser.me/api/portraits/women/2.jpg',
      name: 'Yessica Sanchez',
      rating: 5,
      comment: 'Very satisfied with the maintenance of my heating system. The technicians were punctual, friendly, and left everything working perfectly. I will definitely hire them again.'
    },
    {
      id: 3,
      avatar: 'https://randomuser.me/api/portraits/men/3.jpg',
      name: 'Rondo Fernandez',
      rating: 5,
      comment: 'I called for an emergency with my heating, and they arrived the same day. They fixed the problem quickly and at a fair price. Reliable and professional service!'
    }
  ]);
</script>

<template>
  <div class="max-w-2xl mx-auto px-4 py-8 my-16" id='reviews'>
      <h2 class="text-3xl font-bold mb-10 text-center">See What Our Customers Have To Say</h2>
      <div class="p-4 bg-white shadow-lg rounded-lg mb-4" v-for="review in reviews" :key="review.id">
        <div class="flex items-center mb-4">
          <img :src="review.avatar" :alt="review.name" class="w-12 h-12 rounded-full mr-4" />
          <div>
            <h3 class="text-lg font-semibold">{{review.name}}</h3>
            <div class="flex">
              <i v-for="num in 5" :key="num" :class="num <= review.rating ? 'fas fa-star text-yellow-500' : 'fas fa-star text-gray-300'" />
            </div>
          </div>
        </div>
        <p class="text-gray-600">{{ review.comment }}</p>
      </div>
    </div>
</template>