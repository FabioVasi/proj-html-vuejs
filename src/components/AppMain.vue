<script>
import SectionAbout from './SectionAbout.vue';
import SectionAudible from './SectionAudible.vue';
import SectionCritics from './SectionCritics.vue';
import SectionUpcoming from './SectionUpcoming.vue';
import SectionNewsletters from './SectionNewsletters.vue';
import SectionDig from './SectionDig.vue';
import SectionArticles from './SectionArticles.vue';

export default {
    name: 'AppMain',
    data() {
        return {
            
        }
    },
    components: {
        SectionAbout,
        SectionAudible,
        SectionCritics,
        SectionUpcoming,
        SectionNewsletters,
        SectionDig,
        SectionArticles
    }
}
</script>

<template>

    <main id="main_app">
        <!--section import-->
        <SectionAbout/><!--first-->

        <SectionAudible/><!--second-->

        <SectionCritics/><!--third-->

        <SectionUpcoming/><!--fourth-->

        <SectionNewsletters/><!--fifth-->

        <SectionDig/><!--sixth-->

        <SectionArticles/><!--seventh-->
        
    </main>

</template>

<style lang="scss" scoped>
    @use '../assets/scss/partials/variables.scss' as *;
</style>