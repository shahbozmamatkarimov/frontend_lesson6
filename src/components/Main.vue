<template>
    <main>
        <section>
            <Home />
            <Client />
            <System />
        </section>
    </main>
</template>

<script>
import {Client, Home, System} from "../views";
export default {
    components: {
    Home,
    Client,
    System
}
}
</script>

<style lang="scss">
    
</style>