<template>
  <v-app>
    <v-main>
      <LogoBar></LogoBar>
    </v-main>
  </v-app>
</template>

<script>
import LogoBar from '@/components/LogoBar';

export default {
  name: 'App',

  data: () => ({
    //
  }),

  components: {
    LogoBar,
  },
};
</script>
