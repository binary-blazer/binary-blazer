<style>
  img {
    width: 100%;
    user-select: none;
    pointer-events: none;
  }

  img:nth-child(1) {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
  }

  img::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: calc(100% - 1px);
    background: linear-gradient(transparent, transparent 50%, #fff 50%);
    background-size: 100% 200%;
    background-position: 0 0;
    transition: background-position 0.5s ease-in-out;
  }
</style>

<div style="width: 100%;">
  <a>
    <img src="cmd/content/hero.svg" />
    <img src="cmd/content/about.svg" />
    <img src="cmd/content/technologies.svg" />
  </a>
</div>
