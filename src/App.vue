<template>
  <div>
    <TheHeader />
    <TheSidebarHeader />
    <TheSidebarSmall />
    <TheSidebar />
    <TheSidebarMobile />
    <TheCategories />
    <TheVideos />
  </div>
</template> 

<script>
import TheHeader from './components/TheHeader.vue';
import TheCategories from './components/TheCategories.vue';
import TheSidebar from './components/TheSidebar.vue';
import TheSidebarMobile from './components/TheSidebarMobile.vue';
import TheSidebarSmall from './components/TheSidebarSmall.vue';
import TheVideos from './components/TheVideos.vue';

export default {
  components: {
    TheHeader,
    TheCategories,
    TheSidebar,
    TheSidebarMobile,
    TheSidebarSmall,
    TheVideos
  },
}
</script>