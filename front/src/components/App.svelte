<div class="center">
  <main class="messenger">
    <div class="messenger__inner">
      <div class="messenger__input">
        <input type="text" placeholder="Enter message" />
        <img src="icons/send.svg" alt="send" />
      </div>
    </div>
  </main>
</div>

<style>
  .center {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }

  main {
    width: 85%;
    height: 80%;
    background-color: #222;

    box-shadow: -10px 10px 5px 0px rgba(33, 32, 32, 0.4);
    -webkit-box-shadow: -10px 10px 5px 0px rgba(33, 32, 32, 0.4);
    -moz-box-shadow: -10px 10px 5px 0px rgba(33, 32, 32, 0.4);
    padding: 1rem;
  }

  .messenger__inner {
    width: 100%;
    height: 100%;
    position: relative;
  }

  .messenger__input {
    position: absolute;
    bottom: 0;
    left: 0;

    display: flex;

    width: 100%;
  }

  .messenger__input input {
    width: 100%;
    border-radius: 10px;
    height: 30px;
  }

  .messenger__input img {
    margin-left: 0.7rem;
    height: 30px;
  }
</style>
