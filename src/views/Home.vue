<template>
  <Button /><br>
   <Button />
    <Button />
     <Button />
     <HeroSection />
</template>

<script>
// @ is an alias to /src
import Button from "@/components/Button.vue"
import HeroSection from "@/components/HeroSection.vue"

export default {
  name: 'Home',
  components: {
    Button,
    HeroSection
  }
}

</script>
