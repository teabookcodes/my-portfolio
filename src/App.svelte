<script>
  import avatar from "/avatar.webp";
</script>

<main>
  <div>
    <img src={avatar} class="avatar" alt="Avatar" />
  </div>

  <p>
    Hi 👋 I'm Šimon, a college student and web developer based in Prague, Czech
    Republic.
  </p>
  <p>
    👨‍💻 I developed the web application <a
      href="https://nftaula.io"
      target="_blank"
      rel="noreferrer">nftaula.io</a
    >, which I am still working on
  </p>
  <p>
    🎓 I’m interested in or have some experience with the following
    technologies:
  </p>
  <p>
    JavaScript, Svelte, Go, Fiber, Pocketbase, React, Node.js, Express, MySQL,
    Next.js, HTML, CSS, Tailwind, Bootstrap, Figma, Postman, Git, Ubuntu
  </p>
  <p>
    📫 You can contact me via <a
      href="mailto:simon.kana@seznam.cz"
      rel="noreferrer">email</a
    >
    or
    <a href="https://twitter.com/teabookcodes" target="_blank" rel="noreferrer"
      >Twitter</a
    >
    and also check out my work on
    <a href="https://github.com/teabookcodes" target="_blank" rel="noreferrer"
      >GitHub</a
    >.
  </p>

  <small>
    You can download my CV <a
      href="https://drive.google.com/uc?id=1v6RUTFhibwUwJxJnjkOsthBuALAnvlB2&export=download"
      download>here</a
    >
  </small>

  <div>
    <!-- Link section -->
  </div>
</main>

<style>
  main {
    margin: 0 auto;
    padding: 32px 0;
    width: 96%;
  }
  .avatar {
    height: 10em;
    border-radius: 50%;
  }
  p {
    font-size: 1.5rem;
    line-height: 2rem;
  }
  a {
    color: #000;
    text-decoration: underline;
  }

  @media screen and (min-width: 640px) {
    main {
      padding: 64px 0;
      width: 72%;
    }
    p {
      font-size: 1.75rem;
      line-height: 2.25rem;
    }
    a:hover {
      background-color: #7f86fd;
    }
  }
  @media screen and (min-width: 768px) {
    main {
      width: 56%;
    }
  }
</style>
