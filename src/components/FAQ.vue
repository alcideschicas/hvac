<script setup></script>

<template>
	<div className="relative w-full bg-white px-6 pt-10 pb-8 mt-8 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:max-w-2xl sm:rounded-lg sm:px-10 my-16" id="faqs">
      <div className="mx-auto px-5">
        <div className="flex flex-col items-center">
          <h2 className="mt-5 text-center text-3xl font-bold tracking-tight md:text-5xl">
            FAQs
          </h2>
          <p className="mt-3 text-lg text-neutral-500 md:text-xl">
            Frequenty Asked Questions
          </p>
        </div>
        <div className="mx-auto mt-8 grid max-w-xl divide-y divide-neutral-200">
          <div className="py-5">
            <details className="group">
              <summary className="flex cursor-pointer list-none items-center justify-between font-medium">
                <span> What HVAC services do you offer?</span>
                <span className="transition group-open:rotate-180">
                  <svg
                    fill="none"
                    height="24"
                     shapeRendering="geometricPrecision"
                    stroke="currentColor"
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    strokeWidth="1.5"
                    viewBox="0 0 24 24"
                    width="24"
                  >
                    <path d="M6 9l6 6 6-6"></path>
                  </svg>
                </span>
              </summary>
              <p className="group-open:animate-fadeIn mt-3 text-neutral-600">
			  	We provide a full range of HVAC services, including heating and cooling system installation, repairs, preventative maintenance, and indoor air quality solutions. Whether you need a new furnace, an AC repair, or routine servicing, our expert technicians ensure your system runs efficiently year-round. We work with all major brands and guarantee top-quality service for both residential and commercial properties.
              </p>
            </details>
          </div>
          <div className="py-5">
            <details className="group">
              <summary className="flex cursor-pointer list-none items-center justify-between font-medium">
                <span> Do you offer emergency HVAC repair services?</span>
                <span className="transition group-open:rotate-180">
                  <svg
                    fill="none"
                    height="24"
                     shapeRendering="geometricPrecision"
                    stroke="currentColor"
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    strokeWidth="1.5"
                    viewBox="0 0 24 24"
                    width="24"
                  >
                    <path d="M6 9l6 6 6-6"></path>
                  </svg>
                </span>
              </summary>
              <p className="group-open:animate-fadeIn mt-3 text-neutral-600">Yes! We offer 24/7 emergency HVAC repair services to handle urgent issues such as system failures, refrigerant leaks, strange noises, or no heating or cooling when you need it most. Our team responds quickly to diagnose and fix the problem, ensuring your home or business stays comfortable and safe. If you're facing an HVAC emergency, don’t hesitate to call us anytime.</p>
            </details>
          </div>
          <div className="py-5">
            <details className="group">
              <summary className="flex cursor-pointer list-none items-center justify-between font-medium">
                <span> How often should I schedule HVAC maintenance?</span>
                <span className="transition group-open:rotate-180">
                  <svg
                    fill="none"
                    height="24"
                     shapeRendering="geometricPrecision"
                    stroke="currentColor"
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    strokeWidth="1.5"
                    viewBox="0 0 24 24"
                    width="24"
                  >
                    <path d="M6 9l6 6 6-6"></path>
                  </svg>
                </span>
              </summary>
              <p className="group-open:animate-fadeIn mt-3 text-neutral-600"> To keep your HVAC system running efficiently, we recommend scheduling maintenance twice a year—once in the spring for your air conditioner and once in the fall for your heating system. Regular tune-ups help prevent costly breakdowns, improve energy</p>
            </details>
          </div>
          <div className="py-5">
            <details className="group">
              <summary className="flex cursor-pointer list-none items-center justify-between font-medium">
                <span> How do I know if I need an HVAC repair or replacement?</span>
                <span className="transition group-open:rotate-180">
                  <svg
                    fill="none"
                    height="24"
                     shapeRendering="geometricPrecision"
                    stroke="currentColor"
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    strokeWidth="1.5"
                    viewBox="0 0 24 24"
                    width="24"
                  >
                    <path d="M6 9l6 6 6-6"></path>
                  </svg>
                </span>
              </summary>
              <p className="group-open:animate-fadeIn mt-3 text-neutral-600">If your HVAC system is over 10-15 years old, requires frequent repairs, or isn’t maintaining a consistent temperature, it may be time for a replacement. Other signs that you may need a replacement include rising energy bills, uneven airflow, or strange noises. Our experts can thoroughly inspect your system and provide an honest recommendation based on your specific needs and budget. Whether repair or replacement, we’ll ensure the best solution for your comfort.</p>
            </details>
          </div>
        </div>
      </div>
    </div>
</template>