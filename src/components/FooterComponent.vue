<template>
    <div>
        <ShopAreaComponent />
        <FooterLinksComponent />
        <SocialComponent />
    </div>
</template>

<script>

import ShopAreaComponent from '@/components/ShopAreaComponent.vue';
import FooterLinksComponent from '@/components/FooterLinksComponent.vue';
import SocialComponent from '@/components/SocialComponent.vue';

export default {
    name: 'FooterComponent',
    components: {
        ShopAreaComponent,
        FooterLinksComponent,
        SocialComponent,
    },
};
</script>

<style scoped lang="scss">

</style>