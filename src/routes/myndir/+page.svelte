<svelte:head>
  <title>Myndir - TSA - Trésmíðaverkstæði Stefáns & Ara</title>
</svelte:head>

<section class="section">
  <div class="container">
    <h1 style="text-align: center; margin-bottom: 3rem;">Myndir af verkum</h1>
    
    <p style="text-align: center; margin-bottom: 3rem;">Hér má sjá sýnishorn af þeim fjölmörgu verkefnum sem við höfum tekið að okkur.</p>

    <div class="grid">
      <div class="gallery-item">
        <img src="/images/gallery2.jpg" alt="Regnbogi við Flugstöð Leifs Eiríkssonar" class="gallery-img" />
        <h3>Regnbogi við Flugstöð Leifs Eiríkssonar</h3>
      </div>
      <div class="gallery-item">
        <img src="/images/gallery1.jpg" alt="Bygging Bio Process í Höfnum" class="gallery-img" />
        <h3>Bygging Bio Process í Höfnum</h3>
      </div>
    </div>


  </div>
</section>

<style>
  .gallery-img {
    width: 100%;
    height: 300px;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 15px;
    border: 1px solid var(--color-wood-light);
  }

  .gallery-item h3 {
    margin-bottom: 5px;
  }

  .gallery-item p {
    font-size: 0.9rem;
    color: #666;
  }
</style>
