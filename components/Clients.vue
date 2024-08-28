<template>
    <div class="clients">
      <div class="container-narrow">
        <div class="clients-wrapper">
  
          <!-- Use the Title component -->
          <Title title="Our Clients"/>
  
          <div class="clients-logo">
            <!-- Ensure all img tags are self-closing -->
            <div class="client-logo">
              <img src="../assets/images/Boiler Room.png" alt="" />
            </div>
            <div class="client-logo">
              <img src="../assets/images/Budweiser White.png" alt="" />
            </div>
            <div class="client-logo">
              <img src="../assets/images/Echoes of Earth.png" alt="" />
            </div>
            <div class="client-logo">
              <img src="../assets/images/Corona White.png" alt="" />
            </div>
            <div class="client-logo">
              <img src="../assets/images/Supersonic.png" alt="" />
            </div>
          </div>
  
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import Title from './Title.vue';  // Import the Title component
  </script>
  
  <style src="./Clients.scss" lang="scss" scoped></style>
  