<template>
    <nav class="flex mb-4" aria-label="Breadcrumb">
        <ol
            class="inline-flex items-center space-x-1 md:space-x-3 rtl:space-x-reverse"
        >
            <li class="inline-flex items-center">
                <a
                    href="#"
                    class="inline-flex items-center text-sm font-medium text-gray-700 hover:text-blue-600 dark:text-gray-400 dark:hover:text-white"
                >
                    <svg
                        class="w-3 h-3 me-2.5"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                    >
                        <path
                            d="m19.707 9.293-2-2-7-7a1 1 0 0 0-1.414 0l-7 7-2 2a1 1 0 0 0 1.414 1.414L2 10.414V18a2 2 0 0 0 2 2h3a1 1 0 0 0 1-1v-4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v4a1 1 0 0 0 1 1h3a2 2 0 0 0 2-2v-7.586l.293.293a1 1 0 0 0 1.414-1.414Z"
                        />
                    </svg>
                    Home
                </a>
            </li>
            <li>
                <div class="flex items-center">
                    <svg
                        class="w-3 h-3 text-gray-400 mx-1 rtl:rotate-180"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 6 10"
                    >
                        <path
                            stroke="currentColor"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="m1 9 4-4-4-4"
                        />
                    </svg>
                    <a
                        href="#"
                        class="ms-1 text-sm font-medium text-slate-700 hover:text-blue-600 md:ms-2 dark:text-gray-400 dark:hover:text-white"
                        >Charities</a
                    >
                </div>
            </li>
            <li aria-current="page">
                <div class="flex items-center">
                    <svg
                        class="w-3 h-3 text-gray-400 mx-1 rtl:rotate-180"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 6 10"
                    >
                        <path
                            stroke="currentColor"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="m1 9 4-4-4-4"
                        />
                    </svg>
                    <span
                        class="ms-1 text-sm font-medium text-gray-700 md:ms-2 dark:text-gray-400"
                        >Charity Table</span
                    >
                </div>
            </li>
            <li aria-current="page">
                <div class="flex items-center">
                    <svg
                        class="w-3 h-3 text-gray-400 mx-1 rtl:rotate-180"
                        aria-hidden="true"
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 6 10"
                    >
                        <path
                            stroke="currentColor"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="m1 9 4-4-4-4"
                        />
                    </svg>
                    <span
                        class="ms-1 text-sm font-medium text-gray-700 md:ms-2 dark:text-gray-400"
                        >Edit Charity</span
                    >
                </div>
            </li>
        </ol>
    </nav>
    <h2
        class="mb-4 text-3xl font-extrabold leading-none tracking-tight text-gray-900 md:text-4xl dark:text-white"
    >
        Edit Charity Profile
    </h2>
    <hr class="h-px my-6 bg-gray-300 border-0 dark:bg-gray-700" />
    <section class="text-gray-200 body-font">
        <div class="container px-5 py-24 mx-auto flex flex-col">
            <!-- Edit Section-->
            <div class="lg:w-4/6 mx-auto" >
                <!-- image upload -->
                <div class="shrink-0 mb-6 justify-center flex">
                    <img
                        class="h-20 w-20 bg-slate-300 object-cover rounded-full"
                        src=""
                        alt=""
                    />
                </div>
                <label
                    class="mb-2 text-sm font-medium text-gray-900 dark:text-white"
                    for="file_input"
                    >Upload Photo</label
                >
                <input
                    class="mb-2 w-full text-sm text-gray-900 border border-gray-300 rounded-lg cursor-pointer bg-gray-50 dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400"
                    id="file_input"
                    type="file"
                />
               <!-- image upload End -->
                <!-- Form -->
                <form class="grid grid-cols-4 gap-6 w-full p-4 md:p-5">
                    <div class="col-span-2 justify-center mb-4">
                         <div class="col-span-2">
                      <label for="id" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Admin Id</label>
                      <input type="number" name="id" id="id" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full mb-2 p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Type Admin ID" required="">
                  </div>
                        <div class="col-span-2">
                            <label
                                for="name"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                                >Name</label
                            >
                            <input
                                type="text"
                                name="name"
                                id="name"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="Charity Name"
                                required=""
                            />
                        </div>
                        <div class="col-span-2">
                            <label
                                for="phone"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                                >Phone</label
                            >
                            <input
                                type="text"
                                name="phone"
                                id="phone"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="Phone"
                                required=""
                            />
                        </div>
                        <div class="col-span-2">
                            <label
                                for="email"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                                >Email</label
                            >
                            <input
                                type="email"
                                name="email"
                                id="email"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                                placeholder="Email"
                                required=""
                            />
                        </div>
                        <div class="col-span-2">
                            <label
                                for="website"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                                >Website URL</label
                            >
                            <input
                                type="url"
                                id="website"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="Website.com"
                                required
                            />

                        </div>
                    </div>
                    <div class="mb-4 col-span-2">

                        <div class="col-span-2">

                            <label
                                for="category"
                                class="block mb-2 text-sm  font-medium text-gray-900 dark:text-white"
                                >Major</label
                            >
                            <select
                                id="category"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 w-full focus:border-primary-500 block p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                            >
                                <option selected="">-</option>
                                <option value="">Major 1</option>
                                <option value="">Major 2</option>
                                <option value="">Major 3</option>
                                <option value="">Major 4</option>
                            </select>
                        </div>
                        <div class="col-span-2">
                            <label
                                for="category"
                                class="block mb-2 text-sm  font-medium text-gray-900 dark:text-white"
                                >Status</label
                            >
                            <select
                                id="category"
                                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 w-full focus:border-primary-500 block p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                            >
                                <option selected="">-</option>
                                <option value="">Active</option>
                                <option value="">Not Active</option>
                            </select>
                        </div>

                        <div class="col-span-2">
                            <label
                                for="description"
                                class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                            >
                                Description</label
                            >
                            <textarea
                                id="description"
                                rows="4"
                                class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                placeholder="Write product description here"
                            ></textarea>
                        </div>
                    </div>
                </form>
                <button
                    type="submit"
                    class="text-white inline-flex w-full items-center bg-green-700 hover:bg-green-800 focus:ring-4 focus:outline-none focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
                >
                    <svg
                        class="me-1 -ms-1 w-5 h-5"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            fill-rule="evenodd"
                            d="M10 5a1 1 0 011 1v3h3a1 1 0 110 2h-3v3a1 1 0 11-2 0v-3H6a1 1 0 110-2h3V6a1 1 0 011-1z"
                            clip-rule="evenodd"
                        ></path>
                    </svg>
                    Create
                </button>
                <!-- Form End -->
            </div>
            <!-- Edit Section End-->
                <hr class="h-px my-6 bg-gray-300 border-0 dark:bg-gray-700" />

            <div class="lg:w-4/6 mx-auto">
                <div class="py-20">
                    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                        <div
                            class="flex flex-col flex-1 gap-10 lg:gap-0 lg:flex-row lg:justify-between"
                        >
                            <div
                                class="w-full lg:w-1/4 border-b pb-10 lg:border-b-0 lg:pb-0 lg:border-r border-gray-100"
                            >
                                <div
                                    class="font-manrope font-bold text-5xl text-gray-900 mb-5 text-center"
                                >
                                    260+
                                </div>
                                <span
                                    class="text-xl text-gray-500 text-center block"
                                    >Expert Consultants
                                </span>
                            </div>
                            <div
                                class="w-full lg:w-1/4 border-b pb-10 lg:border-b-0 lg:pb-0 lg:border-r border-gray-100"
                            >
                                <div
                                    class="font-manrope font-bold text-5xl text-gray-900 mb-5 text-center"
                                >
                                    975+
                                </div>
                                <span
                                    class="text-xl text-gray-500 text-center block"
                                    >Active Clients
                                </span>
                            </div>
                            <div
                                class="w-full lg:w-1/4 border-b pb-10 lg:border-b-0 lg:pb-0 lg:border-r border-gray-100"
                            >
                                <div
                                    class="font-manrope font-bold text-5xl text-gray-900 mb-5 text-center"
                                >
                                    724+
                                </div>
                                <span
                                    class="text-xl text-gray-500 text-center block"
                                    >Projects Delivered
                                </span>
                            </div>
                            <div class="w-full lg:w-1/4">
                                <div
                                    class="font-manrope font-bold text-5xl text-gray-900 mb-5 text-center"
                                >
                                    89+
                                </div>
                                <span
                                    class="text-xl text-gray-500 text-center block"
                                    >Orders in Queue
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <charities-users-table />
        </div>
    </section>
</template>

<script setup>
import { onMounted } from "vue";
import { initFlowbite } from "flowbite";
import AdminsLayout from "@/Layouts/AdminsLayout.vue";
defineOptions({ layout: AdminsLayout });
import CharitiesUsersTable from "@/Components/CharitiesUsersTable.vue";
import SaveButton from "@/Components/SaveButton.vue";
// initialize components based on data attribute selectors
onMounted(() => {
    initFlowbite();
});
</script>

<style lang="scss" scoped></style>
