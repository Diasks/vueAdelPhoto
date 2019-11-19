<template>
  <div>
    <b-card-group deck style="margin: 20px; text-align: right; justify-content: center;">
      <router-link to="/Fineart">
        <b-card 
          style="max-width: 20rem; height: 200px;  box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.8), 0 24px 80px 0 rgba(0, 0, 0, 0.19);"
          title="Fine Art" class="backgroundImgOne">
        </b-card> 
      </router-link>
      <router-link to="/City">
        <b-card
          style="max-width: 20rem; height: 200px;  box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.8), 0 24px 80px 0 rgba(0, 0, 0, 0.19);"
          title="Landskap" class="backgroundImgTwo"> 
        </b-card>
      </router-link>
    </b-card-group>
    <b-card-group deck style="margin: 20px; text-align: right; justify-content: center;">
      <router-link to="/Macro">
        <b-card
          style="max-width: 20rem; height: 200px;  box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.8), 0 24px 80px 0 rgba(0, 0, 0, 0.19); "
          title="Macro" class="backgroundImgThree">
        </b-card>
      </router-link>
      <router-link to="Event">
        <b-card
          style="max-width: 20rem; height: 200px;  box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.8), 0 24px 80px 0 rgba(0, 0, 0, 0.19);"
          title="Evenemang" class="backgroundImgFour"> 
        </b-card>
      </router-link>
    </b-card-group>
  </div>
</template>

<script>
export default {
  name: 'Portfolio'
}
</script>

<style>
.backgroundImgOne {
  background-image: url('../assets/coffee.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  border: none;
  color: grey;
  text-shadow: red 2px 2px 5px;
  width: 350px;
  transition: transform .2s; /* Animation */
}

.backgroundImgOne:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgTwo {
  font-family: 'Montserrat';
  background-image: url('../assets/rightcity.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  color: black;
  border: none;
  width: 350px;
  text-shadow: white 2px 2px 5px;
  transition: transform .2s; /* Animation */
}

.backgroundImgTwo:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgThree {
  background-image: url('../assets/rightmacro.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  border: none;
  width: 350px;
  text-shadow: grey 2px 2px 5px;
  color: black;
  transition: transform .2s; /* Animation */
}

.backgroundImgThree:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgFour {
  background-image: url('../assets/rightevents.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  border: none;
  color: grey;
  width: 350px;
  text-shadow: #50d0c3 2px 2px 5px;
  transition: transform .2s; /* Animation */
}

.backgroundImgFour:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

a {
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}
</style>