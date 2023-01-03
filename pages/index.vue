<template>
    <div class="body_container">
    <Header />
    <DiscoveryPage />
    <Reasonable />
    <HomePageLanding />
    <Trading />
    <Footer />
    </div>
</template>

<script>
import Header from '@/components/header'
import Footer from '@/components/footer'
import HomePageLanding from '@/components/landing'
import DiscoveryPage from '@/components/discovery'
import Reasonable from '@/components/reasonable'
import Trading from '@/components/trading'


export default {
    components: {
        Header,
        Footer,
        DiscoveryPage,
        Reasonable,
        Trading,
        HomePageLanding,
    },
    name: "index"
}
</script>

<style lang="scss">
.body_container {
    max-width: 1920px;
    position: relative;
    margin: 0 auto;
    font-family: 'RoRoboto';
    .container {
        max-width: 1320px;
        margin: 0 auto;
    }
}
</style>