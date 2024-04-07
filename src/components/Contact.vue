<template>
  <div class="contact-wrapper">
    <div class="contact-container animated fadeIn two-color-bg">
      <div class="card">
        <h4 class="card-header dancing-text">Contact Information</h4>
        <div class="card-body contact-info">
          <table>
            <tr>
              <td><strong>Name:</strong></td>
              <td>Genilsa Lunils</td>
            </tr>
            <tr>
              <td><strong>Gender:</strong></td>
              <td>Male</td>
            </tr>
            <tr>
              <td><strong>Birthdate:</strong></td>
              <td>November 5, 1998</td>
            </tr>
            <tr>
              <td><strong>Age:</strong></td>
              <td>25</td>
            </tr>
            <tr>
              <td><strong>Address:</strong></td>
              <td>Gabi Cordova Cebu</td>
            </tr>
            <tr>
              <td><strong>School:</strong></td>
              <td>Cordova Public College</td>
            </tr>
            <tr>
              <td><strong>Course:</strong></td>
              <td>College of Information Technology</td>
            </tr>
            <tr>
              <td><strong>Email Address:</strong></td>
              <td>Genilsajherald001@gmail.com</td>
            </tr>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.contact-wrapper {
  background: linear-gradient(to bottom, #b9af42, #4682B4);
}

.contact-container {
  margin: 10%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  text-align: left;
  border-radius: 10px;
  color: #333;
}

.card {
  width: 100%;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.card-header {
  background-color: #4682B4;
  color: #fff;
  padding: 10px;
  border-radius: 10px 10px 0 0;
}

.card-body {
  padding: 20px;
}

/* Dancing text animation */
.dancing-text {
  animation: dance 2s ease infinite;
  color: aquamarine; /* Change text color to aquamarine */
}

@keyframes dance {
  0%, 100% {
    transform: translateX(0);
  }
  50% {
    transform: translateX(10px);
  }
}

/* Animation */
.animated {
  animation-duration: 10s;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Table styles */
table {
  width: 100%;
}

table td {
  padding: 10px;
  border-bottom: 1px solid #ddd;
}

table tr:last-child td {
  border-bottom: none;
}
</style>
