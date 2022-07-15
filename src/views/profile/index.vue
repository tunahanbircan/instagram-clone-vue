<template>
  <div class="home">
    <CustomText tag="h1">Profile</CustomText>
    <CustomText tag="p"
      >Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis
      dolores natus sunt iure commodi assumenda ullam, inventore nesciunt unde
      magni. Cumque eaque perspiciatis, dolor mollitia sequi sint quidem
      suscipit fuga.</CustomText
    >

    <div id="nav">
      <router-link to="/profile">Post</router-link> |
      <router-link to="/profile/igtv">IGTV</router-link> |
      <router-link to="/profile/save">Save</router-link> |
      <router-link to="/profile/tag">Tag</router-link>
    </div>

    <router-view />
  </div>
</template>
<script>
import CustomText from '@/components/CustomText'
export default {
  name: 'ProfileView',
  components: {
    CustomText
  }
}
</script>

<style scoped></style>
