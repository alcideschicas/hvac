<script setup></script>

<template>
  <div className="relative bg-gradient-to-r from-purple-600 to-blue-600 h-screen text-white overflow-hidden" id="hero">
    <div className="absolute inset-0">
      <img src="/src/assets/hvac-worker.jpg" alt="HVAC Worker" className="object-cover object-center w-full h-full" />
      <div className="absolute inset-0 bg-black opacity-50"></div>
    </div>
    <div className="relative z-10 flex flex-col justify-center items-center h-full text-center">
      <h1 className="text-5xl font-bold leading-tight mb-4">Stay Comfortable, Save Energy - Smart HVAC Solutions</h1>
      <p className="text-lg text-gray-300 mb-8">Smart Heating & Cooling for a Cozy Home</p>
      <div>
        <a href="tel:240-802-9076"
          className="bg-blue-600 text-gray-900 hover:bg-blue-500 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg me-3 cursor-pointer"><i
            className="fas fa-phone"></i> Call Now</a>
        <a href="#services"
          className="bg-yellow-300 text-gray-900 hover:bg-yellow-200 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg cursor-pointer">View
          Services</a>
      </div>
    </div>
  </div>
</template>