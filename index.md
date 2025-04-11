---
layout: default
title: Naslovna
---

<!-- Navigacija -->
<style>
nav {
  background-color: #333;
  overflow: hidden;
}

nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
}

nav ul li {
  position: relative;
}

nav ul li a {
  display: block;
  padding: 14px 20px;
  color: white;
  text-decoration: none;
  background-color: #333;
}

nav ul li:hover > a {
  background-color: #111;
}

nav ul li ul {
  display: none;
  position: absolute;
  top: 48px;
  left: 0;
  background-color: #444;
  min-width: 160px;
  z-index: 1;
}

nav ul li:hover ul {
  display: block;
}

nav ul li ul li a {
  padding: 10px;
  background-color: #444;
}

nav ul li ul li a:hover {
  background-color: #555;
}
</style>

<nav>
  <ul>
    <li>
      <a href="#">O nama</a>
      <ul>
        <li><a href="/ZBTest/nas-tim.html">Naš tim</a></li>
        <li><a href="/ZBTest/nasa-prica.html">Naša priča</a></li>
      </ul>
    </li>
    <li>
      <a href="#">Usluge</a>
      <ul>
        <li><a href="/ZBTest/web-dizajn.html">Web dizajn</a></li>
        <li><a href="/ZBTest/seo-optimizacija.html">SEO optimizacija</a></li>
      </ul>
    </li>
    <li>
      <a href="#">Kontakt</a>
      <ul>
        <li><a href="/ZBTest/lokacija.html">Lokacija</a></li>
        <li><a href="/ZBTest/pisi-nam.html">Piši nam</a></li>
      </ul>
    </li>
  </ul>
</nav>

<!-- Glavni sadržaj -->
<h1>Dobrodošli!</h1>
<p>Ovo je početna stranica web projekta na GitHub Pages uz Jekyll i temu "minima".</p>
