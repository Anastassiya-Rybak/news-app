<template>
  <div class="site-header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
          <a class="col-2 navbar-brand logo text-center p-0 mb-2" href="#">NEWS</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Мир</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Страны 
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Казахстан</a></li>
                  <li><a class="dropdown-item" href="#">Россия</a></li>
                  <li><a class="dropdown-item" href="#">Кыргыстан</a></li>
                  <li><a class="dropdown-item" href="#">Китай</a></li>
                  <li><a class="dropdown-item" href="#">Украина</a></li>
                  <li><a class="dropdown-item" href="#">Египет</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Весь список</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Прямой эфир</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success search-btn" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>    
  </div>
</template>

<script lang="js">
export default {
  name: 'SiteHeader',
}
</script>

<style lang="css">
</style>