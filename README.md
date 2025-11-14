<p align="center">
  <div class="input-wrapper">
  <input aria-label="Ask us anything">
  <span class="placeholder"></span>
  </div>
</p>

<p align="center">
  <img src="https://i.pinimg.com/originals/b9/01/85/b9018579aebd5c161b0eac79ca04f17a.gif" alt="gif" />
</p>


<h1 align="center">Hi, I'm <a href="https://luqman.me">Luqman(Luka)</a>!</h1>

<h3 align="center">Welcome to my GitHub Profile 👀</h3>

<p align="center">i'm a tech geek / striving philantrophist ☆</p>

<p align="center">
  <strong><a href="https://yuna0x0.com">Website</a></strong> |
  <strong><a href="https://x.com/yunaNULL">Linkedin</a></strong> |
  <strong><a href="https://bsky.app/profile/yuna0x0.com">Bluesky</a></strong> |
  <strong><a href="https://discord.gg/nYXzaUS">Discord</a></strong> |
</p>

<p align="center">
  <img 
    src="https://github-readme-streak-stats.herokuapp.com/?user=luqmanshaqiq2&theme=nightowl&hide_border=true" 
    alt="GitHub Streak Stats"
  />
</p>



<style>
body {
  display: grid;
  height: 100vh;
  place-items: center;
  width: 100%;
}

.input-wrapper {
  display: block;
  font-family: monospace;
  font-size: 125%;
  width: 50%;
  > input,
  > .placeholder {
    display: block;
    appearance: none;
    width: 100%;
    height: 100%;
    background-color: transparent;
    border: none;
  }
  > .placeholder {
    pointer-events: none;
    @include typed(
      "How many roads must a man walk down before you call him a man?",
      "How many seas must a white dove sail before she sleeps in the sand?",
      "The answer, my friend, is blowin' in the wind",
      1.5,
      (
        caret-width: 2px,
        caret-space: 2px
      )
    );
  }
  > input {
    &:focus,
    &:active {
      + .placeholder {
        display: none;
      }
    }
  }
}
</style>
