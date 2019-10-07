<template>
    <v-app>
        <app-header></app-header>
        <v-container>
          <v-row>
            <app-server-details></app-server-details>
          </v-row>
          <v-row>
            <servers></servers>
          </v-row>
        </v-container>
        <app-footer></app-footer>
    </v-app>
</template>

<script>
    import Header from './components/Shared/Header.vue';
    import Footer from './components/Shared/Footer.vue';
    import Servers from './components/Server/Servers.vue';
    import ServerDetails from './components/Server/ServerDetails.vue';

    export default {
        components: {
            appHeader: Header,
            Servers,
            'app-server-details': ServerDetails,
            'app-footer': Footer
        }
    }
</script>

<style>

</style>
