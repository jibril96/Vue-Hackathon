<template>
<TheNavbar />
 <div>
    <TheHeader/>
    <main>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta reiciendis laudantium eum provident sequi quidem ipsa adipisci delectus, debitis ex neque eveniet officia consectetur, aperiam velit molestias nam sed eos?</p>
      </main>
  </div>
  <caption-content>
    <template #content>
      <img 
      src="https://images.pexels.com/photos/846265/pexels-photo-846265.jpeg?cs=srgb&dl=pexels-the-happiest-face-%29-846265.jpg&fm=jpg"
      />
    </template>
    <template #caption="{source}">
    Source: <a href="pexels.com">{{source}}</a>
    </template>
  </caption-content>
      <TheFooter/>
      <template>
    <footer>
     <p>&copy; Jibril Adem 2022</p>
    </footer>
</template>
      
</template>

<script>

import CaptionContent from  './components/CaptionContent.vue'
import TheFooter from './components/TheFooter.vue'
import TheHeader from './components/TheHeader.vue'
import TheNavbar from './components/TheNavbar.vue'
export default {
  components: {
    CaptionContent,
    TheFooter,
    TheHeader,
    TheNavbar,
  },
}
</script>
<style>

#app {

  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: red;
}

</style>