<template>
    <v-app>
        <v-main>
            <router-view></router-view>
        </v-main>
    </v-app>
</template>

<script>
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'App',
    });
</script>

<style scoped lang="scss">
  ::v-deep .v-application__wrap {
   position: unset;
  }
</style>
