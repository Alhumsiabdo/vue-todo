<template>
  <div class="container">
    <div class="about">
      <h1>About Us</h1>
      <p>Welcome to our Vue.js todo project! Here, we've created a fantastic web application designed to help you effectively manage your tasks and to-do items.</p>
      <p>With the power of Vue.js, a cutting-edge JavaScript framework, we've crafted an intuitive and user-friendly interface that allows you to effortlessly add, complete, and remove tasks.</p>
      <p>Our project isn't just about managing tasks; it's about streamlining your workflow and boosting your productivity. Whether you're a professional, a student, or anyone in between, our todo app is here to make your life easier.</p>
      <p>Join us on this journey towards better task management and organization. Together, we'll conquer tasks and achieve our goals!</p>
    </div>
  </div>
</template>

<style scoped>
  .container {
    display: flex;
    justify-content:center;
    align-items: center;
    min-height: 100vh;
    padding-bottom: 200px;
  }

  .about {
    max-width: 600px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 8px;
    background-color: #f5f5f5;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  h1 {
    margin-bottom: 16px;
    text-align: center;
    padding-top: 15px;
    font-size: 24px;
  }

  p {
    line-height: 1.6;
    margin-bottom: 12px;
  }
</style>
