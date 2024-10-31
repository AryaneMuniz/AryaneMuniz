<div class="dvd-text">
  QUICANDO PELO GITHUB
</div>

<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #000;
    overflow: hidden;
    margin: 0;
  }

  .dvd-text {
    font-size: 2em;
    color: #FFF;
    font-weight: bold;
    position: absolute;
    animation: bounce 5s infinite;
  }

  @keyframes bounce {
    0%   { top: 0; left: 0; color: #4CAF50; }
    25%  { top: 0; right: 0; color: #FF5722; }
    50%  { bottom: 0; right: 0; color: #2196F3; }
    75%  { bottom: 0; left: 0; color: #FFEB3B; }
    100% { top: 0; left: 0; color: #4CAF50; }
  }
</style>
