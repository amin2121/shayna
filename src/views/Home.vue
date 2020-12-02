<template>
	<div>
		<Header/>
		<HeroCarousel/>
		<ProductItem/>
		<InstagramPhoto/>
		<PartnerLogo/>
		<Footer/>
	</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header';
import HeroCarousel from '@/components/HeroCarousel';
import ProductItem from '@/components/ProductItem';
import InstagramPhoto from '@/components/InstagramPhoto';
import PartnerLogo from '@/components/PartnerLogo';
import Footer from '@/components/Footer';

export default {
  name: 'Home',
  components: {
    // HelloWorld
    Header,
    HeroCarousel,
    ProductItem,
    InstagramPhoto,
    PartnerLogo,
    Footer
  }
}
</script>
