<template>
    <ul class="nav bg-red-100">
        <li>
            <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
            <NuxtLink :to="{ name: 'create' }">Create</NuxtLink>
        </li>
    </ul>
</template>