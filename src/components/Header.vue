<script>
import "@/assets/styles/header.css";

</script>

<template>
    <header class="site-header">

      <div class="container header-row">
        <div class="header-left">
          <a class="brand logo" href="/">PrimerPaso.com</a>

          <nav aria-label="Main navigation">
            <a href="/">Home</a>
            <a href="/jobs">Jobs</a>
          </nav>
        </div>

        <div class="header-right">
          <div id="guestMenu">
            <a class="btn-student" href="/loginuser">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h4a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-4"></path><polyline points="10 17 15 12 10 7"></polyline><line x1="15" y1="12" x2="3" y2="12"></line></svg>
              <span>Student</span>
            </a>
            <a class="btn-company" href="/company-login">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h4a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-4"></path><polyline points="10 17 15 12 10 7"></polyline><line x1="15" y1="12" x2="3" y2="12"></line></svg>
              <span>Company</span>
            </a>
          </div>
        </div>
      </div>
    </header>
</template>

<style scoped></style>