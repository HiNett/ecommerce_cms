<template>
    <nav class="container">
        <ul>
            <li><NuxtLink to="/"><strong>ecommerce_cms</strong></NuxtLink></li>
        </ul>
        <ul>
            <li><NuxtLink :to="{name: 'test' }">Test1</NuxtLink></li>
            <li><a href="#">Test2</a></li>
            <li><a href="#">Test3</a></li>
        </ul>
    </nav>
</template>