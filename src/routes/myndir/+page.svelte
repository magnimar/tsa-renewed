<svelte:head>
  <title>Myndir - TSA - Trésmíðaverkstæði Stefáns & Ara</title>
</svelte:head>

<section class="section">
  <div class="container">
    <h1 style="text-align: center; margin-bottom: 3rem;">Myndir af verkum</h1>
    
    <p style="text-align: center; margin-bottom: 3rem;">Hér má sjá sýnishorn af þeim fjölmörgu verkefnum sem við höfum tekið að okkur.</p>

    <div class="grid">
      <div class="gallery-item">
        <div class="placeholder-img">Regnbogi</div>
        <h3>Regnbogi</h3>
        <p>Flugstöð Leifs Eiríkssonar</p>
      </div>
      <div class="gallery-item">
        <div class="placeholder-img">Bio Process</div>
        <h3>Bio Process</h3>
        <p>Bygging í Höfnum</p>
      </div>
      <div class="gallery-item">
        <div class="placeholder-img">Innréttingar</div>
        <h3>Innréttingar</h3>
        <p>Sérsmíði fyrir fyrirtæki</p>
      </div>
      <div class="gallery-item">
        <div class="placeholder-img">Bláa Lónið</div>
        <h3>Bláa Lónið</h3>
        <p>Nýbygging</p>
      </div>
    </div>

    <p style="text-align: center; margin-top: 4rem; font-style: italic;">
      Fleiri myndir munu bætast hér á síðuna innan skamms.
    </p>
  </div>
</section>

<style>
  .placeholder-img {
    background-color: var(--color-wood-light);
    height: 250px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.2rem;
    color: var(--color-wood-medium);
    border-radius: 8px;
    margin-bottom: 15px;
    border: 2px dashed var(--color-accent);
  }

  .gallery-item h3 {
    margin-bottom: 5px;
  }

  .gallery-item p {
    font-size: 0.9rem;
    color: #666;
  }
</style>
