<template>
  <main>
    <div class="container">
      <header>
        <h1 class="header-title">Memo</h1>
        <button class="header-button">+</button>
      </header>
      <div class="card-container">
        <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab,
            molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>

        </div>
        <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab,
            molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>

        </div>
        <div class="card">
          <p class="card-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam eveniet neque ab,
            molestiae
            repellendus, omnis quae quasi eligendi, et fugit ea reprehenderit optio magni consequatur. Nemo ad voluptate
            ab consequatur?</p>
          <p class="card-date">04/03/2026</p>

        </div>
      </div>
    </div>
    <div class="form-overlay">
      <div class="form-modal">
        <button class="form-close-btn">&times;</button>
        <textarea name="memo" id="memo" cols="30" rows="10"></textarea>
        <button class="form-save-btn">Save</button>
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

.form-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.77);
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: center;
}

.form-modal {
  width: 420px;
  background-color: white;
  border-radius: 10px;
  padding: 30px;
  position: relative;
  display: flex;
  flex-direction: column;
}

.form-save-btn {
  padding: 10px 20px;
  font-size: 20px;
  width: 100%;
  background-color: blue;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  margin-top: 15px;
  color: white;
}

.form-close-btn {
  position: absolute;
  top: 5px;
  right: 10px;
  width: 30px;
  height: 30px;
  background-color: transparent;
  border: none;
  font-size: 30px;
  cursor: pointer;
}
</style>