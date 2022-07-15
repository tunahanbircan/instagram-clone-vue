<script>
import CustomText from '@/components/CustomText'
export default {
  name: 'HomeView',
  components: {
    CustomText
  }
}
</script>

<template>
  <div class="home">
    <div class="timeline">
      <h1>Home</h1>
      <CustomText class="a1" tag="p">Merhaba Dünya</CustomText>
      <CustomText class="a2" tag="p" size="small">Merhaba Dünya</CustomText>
      <CustomText class="a3" tag="p" size="xsmall">Merhaba Dünya</CustomText>
      <CustomText tag="p" size="xxsmall">Merhaba Dünya</CustomText>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus a
        animi nemo nostrum, veritatis odio necessitatibus tempora autem quasi
        obcaecati architecto, inventore est maxime! Omnis laborum nisi tempore
        voluptates modi.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus a
        animi nemo nostrum, veritatis odio necessitatibus tempora autem quasi
        obcaecati architecto, inventore est maxime! Omnis laborum nisi tempore
        voluptates modi.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus a
        animi nemo nostrum, veritatis odio necessitatibus tempora autem quasi
        obcaecati architecto, inventore est maxime! Omnis laborum nisi tempore
        voluptates modi.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus a
        animi nemo nostrum, veritatis odio necessitatibus tempora autem quasi
        obcaecati architecto, inventore est maxime! Omnis laborum nisi tempore
        voluptates modi.
      </p>
    </div>
    <div class="sidebar">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus a
        animi nemo nostrum, veritatis odio necessitatibus tempora autem quasi
        obcaecati architecto, inventore est maxime! Omnis laborum nisi tempore
        voluptates modi.
      </p>
    </div>
  </div>
</template>

<style scoped>
.home {
  max-width: 605px;
  margin-left: auto;
  margin-right: auto;
  @media (--t) {
    max-width: none;
    display: grid;
    grid-template-columns: 1fr 295px;
    grid-gap: 30px;
  }
}
.sidebar {
  display: none;
  @media (--t) {
    display: block;
  }
}
</style>
