<template>
  <main>
    <div class="container">
      <header>
        <h1 class="header-title">Memo</h1>
        <button class="header-button">+</button>
      </header>
      <div class="card-container">
        <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab, molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>
          
        </div>
         <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab, molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>
          
        </div>
         <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab, molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>
          
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
}

.container {
  max-width: 900px;
  padding: 10px;
  margin: 0 auto;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header-title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 25px;
  color: aqua;
}

.header-button {
  border: none;
  padding: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
  border-radius: 100%;
  background-color: aqua;
  color: white;
}

.card-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.card {
  width: 225px;
  height: 225px;
  padding: 10px;
  background-color: yellow;
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>