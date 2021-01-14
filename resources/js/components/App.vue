<!-- Template -->
<template>
    <div>
        <header-component></header-component>
        <div>
            <transition name="fade">
                <router-view></router-view>
            </transition>
        </div>
        <footer-component></footer-component>
    </div>
</template>
<!-- process -->
<script>
// import component
// import Name from "@/components/Name.vue";
import HeaderComponent from "./layout/HeaderComponent.vue";
import FooterComponent from "./layout/FooterComponent.vue";

export default {
    data() {
        return {};
    },
    components: {
        HeaderComponent,
        FooterComponent
    },
    methods: {},
    computed: {},
    watch: {},
    beforeCreate() {},
    created() {},
    mounted() {},
    beforeUpdate() {},
    updated() {},
    beforeDestroy() {},
    destroyed() {}
};
</script>
<!-- css -->
<style scoped>
.fade-enter-active, .fade-leave-active {
  transition: opacity .5s
}
.fade-enter, .fade-leave-active {
  opacity: 0
}
</style>
