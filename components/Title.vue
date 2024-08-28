<template>
    <div class="title">
      <div class="container-narrow">
        <div class="title-head">
          <!-- Bind the style to the size prop -->
          <h2 :style="{ fontSize: size }">{{ title }}</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Commodo quis imperdiet massa tincidunt nunc.</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      title: {
        type: String,
        required: true,
        default: 'Title',
      },
      size: {
        type: String,
        default: '4.5rem',
      },
    },
  }
  </script>
  
  <style src="./Title.scss" lang="scss" scoped></style>
  