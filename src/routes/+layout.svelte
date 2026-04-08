<script>
  import "../app.css";
  let { children } = $props();
</script>

<header>
  <div class="container">
    <div style="display: flex; justify-content: space-between; align-items: center;">
      <a href="/" style="display: flex; align-items: center; gap: 15px;">
        <img src="/images/logo.jpg" alt="TSA Logo" style="height: 60px; width: auto;" />
        <span style="font-family: var(--font-serif); font-size: 1.5rem; font-weight: bold; color: var(--color-wood-dark);">
          TSA
        </span>
      </a>
      <nav>
        <ul>
          <li><a href="/">Aðalsíða</a></li>
          <li><a href="/um-tsa">Um TSA</a></li>
          <li><a href="/myndir">Myndir</a></li>
          <li><a href="/hafd-samband">Hafðu samband</a></li>
        </ul>
      </nav>
    </div>
  </div>
</header>

<main>
  {@render children()}
</main>

<footer>
  <div class="container">
    <p>&copy; {new Date().getFullYear()} TSA - Trésmíðaverkstæði Stefáns & Ara</p>
    <p>Brekkustígur 38, 260 Njarðvík | Sími: 421-2788 | <a href="mailto:tsa@tsa.is">tsa@tsa.is</a></p>
  </div>
</footer>
