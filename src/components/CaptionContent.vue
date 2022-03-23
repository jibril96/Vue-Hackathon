<template>
    <div>
     <slot name="content">
        <img src="https://images.pexels.com/photos/50594/sea-bay-waterfront-beach-50594.jpeg?cs=srgb&d">;
      </slot>
     <p>
        <slot name="caption" v-bind:source="source">caption</slot>
     </p>
    </div>
</template>

<script>
export default {
data() {
return {
  source: 'pixels.com',
  }
 },
}
</script>

<style>
img {
    width: 600px;
    
}

p {
    font-size: 20px;
    color:blue;
}
</style>