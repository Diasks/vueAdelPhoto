<template>
  <div>
    <b-card-group deck style="margin-top: 100px; text-align: right; justify-content: center;">
      <router-link to="/Fineart">
        <b-card 
          style="max-width: 20rem; height: 250px;  box-shadow: -1px -1px 100px 6px rgba(0,0,0,1);"
          title="Fine art" class="backgroundImgOne">
        </b-card> 
      </router-link>
      <router-link to="/City">
        <b-card
          style="max-width: 20rem; height: 250px;   box-shadow: -1px -1px 100px 6px rgba(224,220,224,1);"
          title="Landskap" class="backgroundImgTwo"> 
        </b-card>
      </router-link>
    </b-card-group>
    <b-card-group deck style="margin: 20px; text-align: right; justify-content: center;">
      <router-link to="/Macro">
        <b-card
          style="max-width: 20rem; height: 250px;  box-shadow: -1px -1px 100px 6px rgba(97,97,97,0.76); "
          title="Macro" class="backgroundImgThree">
        </b-card>
      </router-link>
      <router-link to="Event">
        <b-card
          style="max-width: 20rem; height: 250px;  box-shadow:  -1px -1px 100px 6px rgba(168,168,168,1);"
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
  color: black;
 text-shadow: white 2px 2px 5px;
  width: 450px;
  transition: transform .2s; /* Animation */
}

.backgroundImgOne:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgTwo {
  font-family: 'Montserrat';
  background-image: url('../assets/coffee.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  color: black;
  border: none;
  width: 450px;
  text-shadow: white 2px 2px 5px;
  transition: transform .2s; /* Animation */
}

.backgroundImgTwo:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgThree {
  background-image: url('../assets/coffee.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  border: none;
  width: 450px;
  text-shadow: white 2px 2px 5px;
  color:  black;
  transition: transform .2s; /* Animation */
}

.backgroundImgThree:hover {
  transform: scale(1.1); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}

.backgroundImgFour {
  background-image: url('../assets/coffee.jpg');
  background-size: cover;
  font-family: 'Montserrat';
  border: none;
  color: black;
  width: 450px;
 text-shadow: white 2px 2px 5px;
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