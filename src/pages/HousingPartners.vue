<template>
  <div class="lg:w-full min-h-[600px] bg-red-400 bgImg">
    <div class="w-full h-[600px] flex justify-center items-center">
      <div class="w-[70%]">
        <h1 class="text-5xl text-white  w-[100%] leading-snug">
          <div>Working with You</div>
        </h1>
        <p class="text-white mt-4 tracking-wide leading-snug font-semibold lg:w-[50%]">
          Short Introductory summary for the page<br />goes here lilke so
        </p>
      </div>
    </div>
  </div>

  <div class="w-full flex justify-center">
    <div class="w-[70%]">
      <div class="py-44">
        <div class="lg:flex">
          <div class="flex-auto">
            <img class="lg:max-w-sm px-15" src="../assets/svg/CardImage.svg" alt />
          </div>
          <div class="flex-auto">
            <h1 class="text-4xl mt-10 px-8 text-trisec text-ellipsis leading-[40px] font-semibold">
              <span class="font-light">Our full service working <span class="font-bold">end to end</span> offering
                overview</span>
            </h1>
            <p class="text-md mt-4 px-8">
              At Stef & Philips, we strive to make the lives of vulnerable
              people safer and more secure. We do this by delivering safe,
              suitable homes and vital services for tenants, authorities and
              partners, while providing secure investments for private and
              corporate investors.
            </p>
            <button type="button"
              class="bg-blue-100 mt-5 ml-8 w-32 ring-2 ring-white py-3.5 text-sm font-semibold text-white shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-600">
              Our Partners
            </button>
          </div>
        </div>

        <div class="lg:flex">
          <div class="flex-auto w-full mx-auto grid">
            <h1 class="text-4xl mt-20 text-trisec text-ellipsis leading-[40px] font-semibold">
              <span class="font-light">We make your life <br /><span class="font-bold">easier</span></span>
            </h1>
            <p class="text-md">
              At Stef & Philips, we strive to make the lives of vulnerable
              people safer and more secure. We do this by delivering safe,
              suitable homes and vital services for tenants, authorities and
              partners, while providing secure investments for private and
              corporate investors.
            </p>
            <button type="button"
              class="bg-blue-500 w-64 mt-5 ring-2 ring-white py-2 text-sm font-semibold text-white">
              Temporary accommodation
            </button>
            <button type="button"
              class="bg-blue-900 w-64 mt-3 ring-2 ring-white py-2 text-sm font-semibold text-white">
              Private rented sector
            </button>

          </div>
          <div class="flex-auto">
            <img class="lg:max-w-sm px-15 mt-9" src="../assets/svg/CardImage2.svg" alt />
          </div>
        </div>

      </div>
    </div>
  </div>

  <HousingPartnersCards />

  <div class="w-full flex justify-center bg-gray-800">
    <div class="w-[70%]">
      <div class="mt-20 mb-20">

        <h1 class="text-4xl text-white">The Stef and Philips difference <br /> <span class="font-bold">Our full
            service solution</span>
        </h1>
        <p class="text-white font-sm mt-3">End-to-end service that sets S&P apart - accountability, trust
          and control over the entires <br /> process , making their life easier. Paragraph style fusce
          laoreet lorem id consequat<br /> rhoncus. Curabitur ultrices condimentum enim, id fringilla libero
          rutrum vel.
        </p>

        <div class="mx-auto grid  grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8 mt-20">
          <div class="flex flex-col justify-start">
            <img class="h-[78px] w-[70px]" src="../assets/svg/ShapeA.svg" alt />
            <h3 class="mt-2 text-xl font-semibold leading-7 tracking-tight text-left text-white">Investment</h3>
            <p class="mt-2 text-sm leading-6 text-white text-left">Short description goes here like so in this featured
              icon element lore ipsum.</p>
          </div>
          <div class="flex flex-col justify-start">
            <img class="h-[78px] w-[70px]" src="../assets/svg/ShapeA.svg" alt />
            <h3 class="mt-2 text-xl font-semibold leading-7 tracking-tight text-left text-white">Sourcing</h3>
            <p class="mt-2 text-sm leading-6 text-white text-left">Short description goes here like so in this featured
              icon element lore ipsum.</p>
          </div>
          <div class="flex flex-col justify-start">
            <img class="h-[78px] w-[70px]" src="../assets/svg/ShapeA.svg" alt />
            <h3 class="mt-2 text-xl font-semibold leading-7 tracking-tight text-left text-white">Construction</h3>
            <p class="mt-2 text-sm leading-6 text-white text-left">Short description goes here like so in this featured
              icon element lore ipsum.</p>
          </div>
        </div>

      </div>
    </div>
  </div>

  <div class="w-full flex justify-center">
    <div class="w-[70%]">
      <div class="py-44">
        <div class="lg:flex">
          <div class="flex-auto">
            <img class="lg:max-w-sm px-15" src="../assets/svg/CardImage.svg" alt />
          </div>
          <div class="flex-auto">
            <h1 class="text-4xl mt-20 px-8 text-trisec text-ellipsis leading-[40px] font-semibold">
              <span class="font-light">Working with our<br /><span class="font-bold">partners</span></span>
            </h1>
            <p class="text-md mt-4 px-8">
              At Stef & Philips, we strive to make the lives of vulnerable
              people safer and more secure. We do this by delivering safe,
              suitable homes and vital services for tenants, authorities and
              partners, while providing secure investments for private and
              corporate investors.
            </p>
            <button type="button"
              class="bg-blue-500 mt-5 ml-8 w-48 ring-2 ring-white py-3.5 text-sm font-semibold text-white shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-600">
              Get in Touch
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="w-full flex justify-center">
    <!-- <div class="w-full h-[600px] flex"> -->
    <div class="w-[70%] bgImg2 h-[400px]">
      <div class="py-20 px-20">
        <img class="" src="../assets/svg/quotation.svg" alt />
        <p class="text-white tracking-wide leading-snug font-light lg:w-[100%]">
          Stef & Philips have been short quote goes here like so in this featured element element lore ipsum short quote
          goes here like so in this featured element element lore ipsum short quote goes here like so in this.
        </p>
        <p class="text-white mt-5 tracking-wide leading-snug lg:w-[100%]">
          Name here
        </p>
        <h5 class="text-white tracking-wide leading-snug font-bold lg:w-[100%]">Title here</h5>

      </div>
    </div>
    <!-- </div> -->
  </div>

  <div class="w-full flex justify-center">
    <div class="w-[70%]">
      <div class="py-44">
      <div class="lg:flex">
        <div class="flex-auto w-full mx-auto grid bg-teal-50 pb-5">
          <h1 class=" text-2xl mt-20 px-8 text-blue-900 text-ellipsis leading-[40px] font-bold h-[32px]">
            Download brochure
          </h1>
          <p class="text-md px-8">
            At Stef & Philips, we strive to make the lives of vulnerable
            people safer and more secure. We do this by delivering safe,
            suitable homes and vital services for tenants, authorities and
            partners, while providing secure investments for private and
            corporate investors.
          </p>
          <button type="button" class="bg-blue-500 w-32 ml-8 ring-2 ring-white py-3.5 text-sm font-light text-white h-[50px]">
            Download
          </button>

        </div>
        <div class="flex-auto">
          <img class="lg:max-w-sm px-15" src="../assets/svg/img1.svg" alt />
        </div>
      </div>
    </div>
    </div>

  </div>







  <!-- <div class="lg:w-full flex justify-center">
    <div class="w-[60%]">
      <div class="lg:pt-40">
        <div class="lg:max-w-5xl grid md:grid-cols-2 grid-cols-1 h-[540px] gap-12">
          <div class="">
            <img class="lg:max-w-sm" src="../assets/svg/CardImage.svg" alt="CardImage" />
          </div>
          <div class="">

            <h1 class="lg:text-4xl mt-12 text-trisec leading-[50px] font-semibold">
              <span class="font-light">Our full service working <span class="font-bold">end to end</span> offering
                overview</span>
            </h1>
            <p class="text-md lg:py-5">
              At Stef & Philips, we strive to make the lives of vulnerable
              people safer and more secure. We do this by delivering safe,
              suitable homes and vital services for tenants, authorities and
              partners, while providing secure investments for private and
              corporate investors.
            </p>
            <button type="button"
              class="bg-blue-100 w-32 ring-2 ring-white py-3.5 text-sm font-semibold text-white shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-600">
              Our Partners
            </button>
          </div>

        </div>
      </div>

      <div class="">
        <div class="lg:max-w-5xl grid md:grid-cols-2 grid-cols-1 h-[540px] gap-12">
          <div class="">
            <img class="lg:max-w-sm" src="../assets/svg/CardImage.svg" alt="CardImage" />
          </div>
          <div class="">

            <h1 class="lg:text-4xl mt-12 text-trisec leading-[50px] font-semibold">
              <span class="font-light">Our full service working <span class="font-bold">end to end</span> offering
                overview</span>
            </h1>
            <p class="text-md lg:py-5">
              At Stef & Philips, we strive to make the lives of vulnerable
              people safer and more secure. We do this by delivering safe,
              suitable homes and vital services for tenants, authorities and
              partners, while providing secure investments for private and
              corporate investors.
            </p>
            <button type="button"
              class="bg-blue-100 w-32 ring-2 ring-white py-3.5 text-sm font-semibold text-white shadow-sm focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-600">
              Our Partners
            </button>
          </div>

        </div>
      </div>

  </div>
  </div> -->
</template>
<script setup>
import HousingPartnersCards from "../components/HousingPartnersCards.vue"
</script>
<style scoped>
.bgImg {
  background-image: url("../assets/svg/Background.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

.bgImg2 {
  background-image: url("../assets/svg/overlay.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
</style>