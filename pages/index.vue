<template>

    <ProfileInfo
        :photo="photo"
        title="Gustavo Braga"
        subtitle = "@GustavoHenriqueBraga"
        heading = "Software Engineer - Senior DevOps"
        />
    
    <div class="max-w-xs mx-auto">
        <ButtonAction
          text="Whatsapp"
          link="https://wa.me/+5511957462378"
          icon="📱"
        />

        <ButtonAction
          text="Linkedin"
          link="https://www.linkedin.com/in/gustavo-braga-925639196/"
          icon="💼"
        />

        <ButtonAction
          text="Github"
          link="https://github.com/GustavoHBraga"
          icon="👨‍💻"
        />

        <ButtonAction
          text="Instagram"
          link="https://www.instagram.com/gustavo_henribraga/"
          icon="📸"
        />
    </div>
    
</template>

<script setup>

    import photo from "../assets/img/picture.jpg";
</script>