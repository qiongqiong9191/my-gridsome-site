<template>
  <div class="layout sticky-header">
    <header class="header sticky">
      <div class="container">
        <div class="left">
          <g-link to="/" class="home-link">
            <g-image
              alt="Nichlas W. Andersen"
              src="~/assets/img/logo.svg"
              class="logo"
            />
          </g-link>
        </div>
        <nav class="nav right">
          <g-link class="nav__link" to="/journal">Journal</g-link>
          <g-link class="nav__link" to="/contract">Say Hi!</g-link>
        </nav>
      </div>
    </header>
    <slot />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

