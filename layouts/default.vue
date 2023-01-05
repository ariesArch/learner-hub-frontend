<script lang="ts" setup></script>

<template>
 <div class="">
		<div class="flex justify-between p-2 text-white">
      <div>
        <NuxtLink to='/' class="p-2 bg-blue-500 text-white rounded items-end">Home</NuxtLink>
      </div>
			<div>
        <NuxtLink to='/login' class="p-2 bg-blue-500 text-white rounded mr-1 hover:bg-blue-600 duration-100">Login</NuxtLink>
        <NuxtLink to='/register' class="p-2 bg-blue-500 text-white rounded hover:bg-blue-600 duration-100">Register</NuxtLink>
        <!-- <NuxtLink to='/dashboard' class="p-2 bg-blue-500 text-white rounded">Dashboard</NuxtLink> -->
      </div>
		</div>
		<NuxtPage />
	</div>
</template>

<style scoped></style>
