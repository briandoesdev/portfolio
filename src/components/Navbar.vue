<template>  
    <v-navbar dark fixed>
        <template v-slot:brandTitle>Brian Heidrich</template>
        <v-nav-region position="right">
            <v-navbar-item href="https://github.com/brianfrombellevue?tab=repositories">Projects</v-navbar-item>
            <v-navbar-item href="https://dev.to/brianheidrich">Blog</v-navbar-item>
        </v-nav-region>
    </v-navbar>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>
