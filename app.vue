<template>
  <div class="container">
    <h1>GPTaaS: The world's leading GPT and LLM-based Technology Systems Integrator</h1>
    <p>We're using the latest machine learning and natural language processing technologies to revolutionize how businesses operate.</p>
    <div class="features">
      <div class="feature">
        <img src="/images/feature-1.png" alt="Feature 1">
        <h2>Automated Workflows and Operational Efficiency</h2>
        <p>We can help you create best-in-breed, custom-trained models and automated AI-powered workflows to leverage within your Customer Success and Support workflows based on the latest AI/ML industry LLM models, including OpenAI's GPT technology.</p>
      </div>
      <div class="feature">
        <img src="/images/feature-2.png" alt="Feature 2">
        <h2>Customer Success + Support</h2>
        <p>Our models use natural language processing (NLP) to provide personalized customer support 24/7, improving customer satisfaction and reducing workload for your team.</p>
      </div>
      <div class="feature">
        <img src="/images/feature-3.png" alt="Feature 3">
        <h2>GPT and LLM-based Integrations</h2>
        <p>Our team can assist with integrating GPT and LLM technology into your current product stack or offerings to enhance how you serve your end customers. </p>
      </div>
    </div>
    <button class="cta">Get started today!</button>
  </div>
</template>

<script>
export default {
  head: {
    title: 'AI-based Startup | Revolutionizing Businesses with Machine Learning',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'We\'re using the latest machine learning and natural language processing technologies to revolutionize how businesses operate.' }
    ],
    link: [
      { rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }
    ]
  }
}
</script>

<style>
  body {
    font-family: "Open Sans", sans-serif;
  }
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 50px;
  text-align: center;
}
.features {
  display: flex;
  justify-content: space-between;
  margin-top: 50px;
}
.feature {
  flex-basis: 30%;
  margin-bottom: 30px;
}
.feature img {
  width: 100%;
  height: auto;
  margin-bottom: 20px;
}
h2 {
  font-size: 24px;
  margin-bottom: 10px;
}
p {
  font-size: 18px;
  line-height: 1.5;
  margin-bottom: 20px;
}
.cta {
  background-color: #ff9800;
  color: #fff;
  font-size: 18px;
  padding: 15px 30px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}
.cta:hover {
  background-color: #f57c00;
}
</style>
