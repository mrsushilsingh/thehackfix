<template>
  <div class="coming-soon">
    <h1>Coming Soon</h1>
    <p>We are working on the website and will be online soon.</p>
    <div class="contact-info">
      <p>Contact us:</p>
      <p>Phone: +91 9736993007</p>
      <p>Email: <a href="mailto:Info@thehackfix.com">Info@thehackfix.com</a></p>
    </div>
  </div>
</template>

<style scoped>
  .coming-soon {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    min-height: 100vh;
    background: linear-gradient(135deg, #a18cd1, #fbc2eb);
    color: white;
    font-family: Arial, sans-serif;
    transition: background 1s ease;
  }

  .contact-info {
    margin-top: 20px;
  }
</style>
