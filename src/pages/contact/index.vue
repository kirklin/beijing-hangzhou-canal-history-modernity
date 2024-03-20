<script setup lang="ts">

</script>

<template>
  <header class="mx-auto box-content max-w-screen-2xl px-5 pt-[60px] sm:pt-[100px] md:px-[50px]">
    <h1 class="max-w-[80%] font-song text-[120px]">
      联系我们
    </h1>
    <p class="mt-[30px] max-w-[80%] font-italics text-2xl font-bold ">
      <span class="false">
        如果您有任何问题或建议，可以通过电话、电子邮件或在线留言的方式与我们联系。<br>我们的工作人员将会竭诚为您服务。
      </span>
    </p>
  </header>
  <!-- Container for demo purpose -->
  <div class="container my-24 mx-auto px-6">
    <!-- Section: Design Block -->
    <section class="mb-32 text-center ">
      <div class="px-6 py-12">
        <div class="container mx-auto">
          <div class=" grid items-center lg:grid-cols-2">
            <div class="mb-12 md:mt-12 lg:my-0">
              <div
                class="block rounded-lg px-6 py-12 shadow-lg md:px-12 lg:-mr-14"
                style="background: hsla(0, 0%, 100%, 0.55); backdrop-filter: blur(30px)"
              >
                <form>
                  <div class="form-group mb-6">
                    <input
                      id="exampleInput7"
                      type="text"
                      class="form-control m-0 block w-full rounded border border-solid border-gray-300 bg-white bg-clip-padding px-3 py-1.5 text-base font-normal text-gray-700 transition ease-in-out focus:border-blue-600 focus:bg-white focus:text-gray-700 focus:outline-none"
                      placeholder="Name"
                    >
                  </div>
                  <div class="form-group mb-6">
                    <input
                      id="exampleInput8"
                      type="email"
                      class="form-control m-0 block w-full rounded border border-solid border-gray-300 bg-white bg-clip-padding px-3 py-1.5 text-base font-normal text-gray-700 transition ease-in-out focus:border-blue-600 focus:bg-white focus:text-gray-700 focus:outline-none"
                      placeholder="Email address"
                    >
                  </div>
                  <div class="form-group mb-6">
                    <textarea
                      id="exampleFormControlTextarea13"
                      class="form-control m-0 block w-full rounded border border-solid border-gray-300 bg-white bg-clip-padding px-3 py-1.5 text-base font-normal text-gray-700 transition ease-in-out focus:border-blue-600 focus:bg-white focus:text-gray-700 focus:outline-none"
                      rows="3"
                      placeholder="Message"
                    />
                  </div>
                  <div class="form-group form-check mb-6 text-center">
                    <input
                      id="exampleCheck87"
                      type="checkbox"
                      class="form-check-input mt-1 mr-2 h-4 w-4 cursor-pointer appearance-none rounded-sm border border-gray-300 bg-white bg-contain bg-center bg-no-repeat align-top transition duration-200 checked:border-blue-600 checked:bg-blue-600 focus:outline-none"
                      checked
                    >
                    <label class="form-check-label inline-block text-gray-800" for="exampleCheck87">Send me a copy of this message</label>
                  </div>
                  <button
                    type="submit"
                    class="w-full rounded bg-blue-600 px-6 py-2.5 text-xs font-medium uppercase leading-tight text-white shadow-md transition duration-150 ease-in-out hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg"
                  >
                    Send
                  </button>
                </form>
              </div>
            </div>
            <div class="md:mb-12 lg:mb-0">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Section: Design Block -->
  </div>
  <!-- Container for demo purpose -->
</template>

<style scoped>
.map-container {
  height: 700px;
  z-index: -1;
}
</style>
