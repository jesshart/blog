<style>
.header {
  text-align: center;
  padding: 2rem 0;
  border-bottom: 1px solid #eee;
}
.logo-large {
  max-width: 600px;
  width: 100%;
  height: auto;
}
.content {
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
}

/* Invert logos in dark mode */
[data-md-color-scheme="slate"] .logo-large {
  filter: invert(1);
}
[data-md-color-scheme="slate"] .md-header__button.md-logo img {
  filter: invert(1);
}
</style>

<div class="header">
  <img src="assets/images/logo_written.png" alt="Hartman Coffee" class="logo-large">
</div>

<div class="content">
  <p>This is my personal library-of-things I have done while sipping coffee.</p>
</div>