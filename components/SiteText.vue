<template>
  <div class="text">
    <header>
      <div class="logo">Aimm.</div>
      <button class="menu"></button>
    </header>
    <main class="content">
      <h1>Change the way art is valued</h1>
      <p>
        Let your most possionate fans support your creative work via monthly
        membership.
      </p>
      <button>Become a creator</button>
    </main>
  </div>
</template>

<style lang="scss" scoped>
.text {
  flex: 1;
  padding: 5%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 2em;

  header {
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo {
      font-weight: bold;
      text-transform: capitalize;
    }

    .menu {
      background: none;
      width: 20px;
      height: 10px;
      border: none;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      direction: rtl;
      cursor: pointer;

      &::after,
      &::before {
        content: '';
        background: #58595f;
        height: 2px;
        border-radius: 2px;
      }

      &::after {
        width: 80%;
      }
      &::before {
        width: 100%;
      }
    }
  }

  .content {
    h1 {
      font-size: 3em;
    }

    p {
      color: #5d5f68;
      margin: 0.8em 0;
    }

    button {
      background: #4e74fd;
      color: white;
      padding: 1em;
      border-radius: 8px;
      border: none;
      cursor: pointer;
    }
  }
}
</style>
