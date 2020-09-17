<template>
	<div class="home">
		<HeaderShayna />
		<HeroShayna />
		<BannerShayna />
		<Instagram />
		<PartnerLogo />
		<Footer />
	</div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import BannerShayna from "@/components/BannerShayna.vue";
import Instagram from "@/components/Instagram.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import Footer from "@/components/Footer.vue";

export default {
	name: "Home",
	components: {
		HeaderShayna,
		HeroShayna,
		BannerShayna,
		Instagram,
		PartnerLogo,
		Footer,
	},
};
</script>
