<template>
  <section class="section">
    <div id="splash-img" class="hero fullscreen hero-img parallax-img">
        <div class="hero-body">
            <div class="content">
              <v-row>
                <v-col c="5" dynamicOffset="right">
                  <div class="text-center">
                    <v-headline size="4">
                      hello, world!
                    </v-headline>
                    <h6 class="font-alt font-light">my name is <b>brian</b> and i am a <b>.NET developer!</b></h6>
                  </div>
                </v-col>
              </v-row>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Override Cirrus max width section class="section"-->
<style scoped>
.content {
  max-width: 100%;
}

#splash-img{ 
    background: url('../assets/background.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}
</style>
