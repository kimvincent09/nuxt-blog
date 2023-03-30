<template>
    <div class="container mx-auto w-1/2 py-8">
        <Title>{{ $route.params.id }} | {{ title }}</Title>
        <h3 class="text-3xl font-bold"><NuxtLink :to="`/posts/1`">Title of Post</NuxtLink></h3>
        <div class="post-meta text-gray-700 flex items-center space-x-2">
            <div>March 30, 2023</div>
            <div>&middot;</div>
            <div>Kim Vincent Alday</div>
        </div>
        <div class="post-preview leading-relaxed mt-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta error quasi et labore deleniti sed delectus, earum nulla nobis! Assumenda atque non, dolorum quibusdam illum recusandae possimus consequuntur nihil omnis!
        </div>
        <div class="post-content">
        {{$route.params.id}} Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illum, aperiam repellat dicta vitae accusantium reprehenderit iure ea modi incidunt a, dolorem tempora molestiae adipisci, cupiditate dolor similique soluta quod eaque?
    </div>
    </div>
</template>
<script>
</script>