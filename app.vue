<template>
  <div class="coming-soon">
    <h1>Coming Soon</h1>
    <p>Our website is under construction, but we'll be online shortly!</p>
    <div class="contact-info">
      <p>For inquiries, reach out to us:</p>
      <p>📞 Phone: +91 9736993007</p>
      <p>📧 Email: <a href="mailto:Info@thehackfix.com">Info@thehackfix.com</a></p>
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

  .coming-soon h1 {
    font-size: 3rem;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .coming-soon p {
    font-size: 1.2rem;
    margin: 5px 0;
  }

  .contact-info {
    margin-top: 20px;
  }

  .contact-info p {
    font-size: 1rem;
  }

  .contact-info a {
    color: #fff;
    text-decoration: underline;
  }

  .contact-info a:hover {
    color: #fbc2eb;
  }
</style>
