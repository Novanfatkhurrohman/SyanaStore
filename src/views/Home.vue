<template>
  <div class="home">
    <HeaderSyana />
    <Hero />
    <Item />
    <InstaSyana />
    <TeamSyana />
    <FooterSyana />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
// import carousel from 'vue-owl-carousel'
import HeaderSyana from '@/components/HeaderSyana.vue'
import Hero from '@/components/Hero.vue'
import Item from '@/components/Item.vue'
import InstaSyana from '@/components/InstaSyana.vue'
import TeamSyana from '@/components/TeamSyana.vue'
import FooterSyana from '@/components/FooterSyana.vue'

export default {
  name: 'Home',
  components: {
    HeaderSyana,
    Hero,
    Item,
    InstaSyana,
    TeamSyana,
    FooterSyana
  }
}
</script>
