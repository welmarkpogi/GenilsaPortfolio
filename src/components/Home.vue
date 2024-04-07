<template>
  <div id="home" class="two-color-bg">
    <div class="container">
      <div class="content">
        <div class="animated-picture"></div>
        <br>
        <strong><h1 class="animated-text white-text">Hello! Its me Genilsa</h1></strong>
        <p class="white-text">A guy with a girl's heart, passionate, confident, and talented, with big dreams in life.<br>A strong passionate independent one who only choose to be chosen</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
#home {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.container {
  text-align: center;
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.animated-picture {
  width: 200px;
  height: 200px;
  background-color: rgba(255, 255, 255, 0.7);
  background-image: url('@/assets/genilsa.jpg');
  background-size: contain;
  background-position: center;
  border-radius: 50%;
  animation: stationary 4s linear infinite;
  margin-bottom: 20px;
}

@keyframes stationary {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(0deg);
  }
}

.animated-text {
  animation: rollText 5s linear infinite; /* Apply horizontal rolling animation */
  margin: 0; /* Remove default margin */
}

@keyframes rollText {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(100%); /* Move text 100% horizontally */
  }
}

.white-text {
  color: white;
}

.name {
  margin-top: 20px;
}

/* Two-color background */
.two-color-bg {
  background: linear-gradient(to bottom, #b9af42, #4682B4); /* Use your desired colors */
  margin: 0;
  padding: 0;
}
</style>
