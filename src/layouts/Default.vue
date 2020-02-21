<template>
  <div class="layout">
    <div class="has-background-light">
      <div class="container">
        <nav class="navbar is-light is-fixed" role="navigation" aria-label="main navigation">
          <div class="navbar-brand">
            <a class="navbar-item" href="#">
              <img src="../../static/Startup..png" alt />
            </a>

            <a role="button" class="navbar-burger burger" data-target="navbar">
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>
          </div>

          <div id="navbar" class="navbar-menu">
            <div class="navbar-end">
              <a class="navbar-item">Home</a>

              <a class="navbar-item">Documentation</a>

              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link">More</a>

                <div class="navbar-dropdown">
                  <a class="navbar-item">About</a>
                  <a class="navbar-item">Jobs</a>
                  <a class="navbar-item">Contact</a>
                  <hr class="navbar-divider" />
                  <a class="navbar-item">Report an issue</a>
                </div>
              </div>
              <div class="navbar-item">
                <div class="buttons">
                  <a class="button is-primary">
                    <strong>Sign up</strong>
                  </a>
                  <a class="button is-outlined is-primary">Log in</a>
                </div>
              </div>
            </div>
          </div>
        </nav>
      </div>
    </div>

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

<style>
.layout {
}
</style>
