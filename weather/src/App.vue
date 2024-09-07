<template>
  <div class="weather">
    <div class="container">
      <div class="card weather-form">
        <input
          type="text"
          class="weather-form__input"
          placeholder="Enter city"
        />
        <button class="weather-form__btn">Search</button>
      </div>

      <div class="card weather-load">Loading...</div>

      <div class="weather-info">
        <div class="weather-info__text">
          <p class="card">Phuket</p>
          <p class="card">29°C</p>
          <p class="card">Sunny</p>
        </div>
      </div>

      <div class="weather-bg">
        <div>
          <img
            class="weather-bg__img bg"
            src="./assets/bg.jpg"
            alt="App Background"
          />
          <img
            class="weather-bg overcast"
            src="./assets/overcast.jpg"
            alt="Overcast"
          />
          <img
            class="weather-bg partly-cloudy"
            src="./assets/partly-cloudy.jpg"
            alt="Partly Cloudy"
          />
          <img class="weather-bg sunny" src="./assets/sunny.jpg" alt="Sunny" />
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>
