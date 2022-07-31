<template>
    <section id="content">
        <img class="img" src="https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg" alt="Vue Logo" />
        <h1>Hello, {{ name }}</h1>
        <h3>Vue.js + TypeScript Boilerplate (with Parcel as bundle & build tool)</h3>
        <p>Start editing <code>src/App.vue</code> and save to reload.</p>
    </section>
</template>

<script lang="ts">
export default {
    name: 'App',
    data() {
        return {
            name: 'Vue',
        };
    },
};
</script>

<style>
body {
    background: #35495e;
}
h1,
h2,
h3,
p {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
        'Open Sans', 'Helvetica Neue', sans-serif;
    color: #fff;
}
code {
    color: #42b883;
}
.img {
    height: 160px;
}
#content {
    text-align: center;
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
