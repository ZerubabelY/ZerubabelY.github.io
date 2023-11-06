<template>
  <div>
    <div
      class="flex items-center justify-center h-full rounded bg-primary-600 wow zoomIn"
    >
      <form class="w-2/3 py-10">
        <div class="flex flex-col gap-y-5">
          <div class="col-xl-12">
            <input
              type="text"
              class="w-full px-3 py-2 border-0 bg-primary-50 focus:outline-none text-secondary-600"
              placeholder="Your Name"
              style="height: 55px"
            />
          </div>
          <div>
            <input
              type="email"
              class="w-full px-3 py-2 border-0 bg-primary-50 focus:outline-none text-secondary-600"
              placeholder="Your Email"
              style="height: 55px"
            />
          </div>
          <div>
            <select
              class="w-full px-3 py-2 border-0 bg-primary-50 focus:outline-none text-secondary-600"
              style="height: 55px"
            >
              <option selected>Select A Service</option>
              <option value="web_development">Web Development</option>
              <option value="apps_development">Apps Development</option>
              <option value="system_development">System Development</option>
              <option value="deployment">Deployment</option>
              <option value="maintenance">Maintenance</option>
              <option value="custom_service">Custom Service</option>
            </select>
          </div>
          <div>
            <textarea
              class="w-full px-3 py-2 border-0 bg-primary-50 focus:outline-none text-secondary-600"
              rows="3"
              placeholder="Message"
            ></textarea>
          </div>
          <div>
            <button
              class="w-full py-3 text-white bg-midnight-950"
              type="submit"
            >
              Request A Quote
            </button>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>
