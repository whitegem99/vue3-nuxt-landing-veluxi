<template>
  <div class="footer-deco">
    <div class="decoration">
      <svg class="left-deco">
        <use xlink:href="/images/saas/deco-bg-left.svg#main" />
      </svg>
      <svg class="right-deco">
        <use xlink:href="/images/saas/deco-bg-right.svg#main" />
      </svg>
    </div>
    <div class="action">
      <h4 class="use-text-title2">
        {{ $t('saasLanding.footer_waiting') }}
      </h4>
      <v-btn color="secondary" size="large">
        {{ $t('saasLanding.getstarted') }}
      </v-btn>
    </div>
    <footer-main />
  </div>
</template>

<style lang="scss" scoped>
@import './footer-style.scss';
</style>

<script>
import Footer from './Footer';

export default {
  components: {
    'footer-main': Footer,
  },
};
</script>
