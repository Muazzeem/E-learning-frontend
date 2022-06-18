<template>
  <div>
    <nav
        class="navbar navbar-expand-lg  blur blur-rounded top-0 border-bottom z-index-3 shadow w-100 mt-4 fixed-top my-3 py-2">
      <div class="container-fluid">
        <a class="navbar-brand font-weight-bolder ms-3" href="" rel="tooltip" title="Designed and Coded by Creative Tim"
           data-placement="bottom" target="_blank">
          Fractalslab
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navigation"
                aria-controls="navigation" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navigation">
          <ul class="navbar-nav navbar-nav-hover mx-auto">
            <li class="nav-item px-3">
              <a class="nav-link">
                Pages
              </a>
            </li>

            <li class="nav-item px-3">
              <a class="nav-link">
                Utilities
              </a>
            </li>

            <li class="nav-item px-3">
              <a class="nav-link">
                Blocks
              </a>
            </li>

            <li class="nav-item px-3">
              <a class="nav-link">
                Docs
              </a>
            </li>
          </ul>

          <ul class="navbar-nav">
            <a href="#contact-form" class="btn btn-sm  bg-gradient-dark  btn-round mb-0 me-1">Enroll Now</a>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <router-view/>
  <div class="view container-fluid">

  </div>
</template>

<style lang="stylus">
@import "/src/assets/css/soft-design-system.css"
@import "/src/assets/css/style.css"
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;600;700;800;900&display=swap');
body {
  font-family: 'Rubik', sans-serif;
  background-color: #f5f5fa !important;
}

p, .ps-2 {
  font-family: 'Rubik', sans-serif;
}

.navbar-brand {
  font-size: 30px;
  padding: 0px;
}
</style>
