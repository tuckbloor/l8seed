<template>
    <div>
        <h1>Inertiajs is {{ test }}</h1>

        <h1 class="text-3xl font-bold underline">
            Hello world!
        </h1>
        <Link href="/">home</Link>
    </div>
</template>

<script>
    import { Link } from "@inertiajs/inertia-vue3";
    export default {
        components: {
            Link,
        },
        props: ["test"],
    };
</script>