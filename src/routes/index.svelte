<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }

  .home-copy {
    flex: 1;
  }

  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  p {
    font-size: 1.4em;
    line-height: 1.5;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  figcaption {
    font-size: .8em;
    font-style: italic;
  }

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    p {
      font-size: 1.2em;
    }

    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
</style>

<svelte:head>
  <title>Kariyer Cafe</title>
  <meta name="description" content="Kariyer Cafe ile günlük İK dozunuzu alın! Güncel kariyer sohbetlerinin keyfine varın.">
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>Günlük IK Dozunuz</h1>
    <p>Gülhan Berkman web sitesi için <a href="https://www.gulhanberkman.com" target="_blank" rel="noreferrer">tıklayınız</a></p>
  </div>

  <figure>
    <img alt='Person typing on laptop' src='undraw-illustration.svg' width="400" height="353">
    <figcaption>Illustration thanks to <a href="https://undraw.co" target="_blank" rel="noreferrer">Undraw</a></figcaption>
  </figure>
</div>
