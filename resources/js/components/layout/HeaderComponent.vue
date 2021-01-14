<!-- Template -->
<template>
    <div>
        <nav>
            <ul>
                <li>
                    <router-link to="/">Home</router-link>
                </li>
                <li>
                    <router-link to="/task">Task</router-link>
                </li>
            </ul>
        </nav>
    </div>
</template>
<!-- process -->
<script>
// import component
// import Name from "@/components/Name.vue";

export default {
    data() {
        return {};
    },
    methods: {},
    computed: {},
    watch: {},
    beforeCreate() {},
    created() {},
    mounted() {
        console.log("Example Component mounted.");
    },
    beforeUpdate() {},
    updated() {},
    beforeDestroy() {},
    destroyed() {}
};
</script>
<!-- css -->
<style lang="stylus" scoped></style>
