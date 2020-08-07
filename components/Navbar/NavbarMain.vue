<template>
  <div id="navbar2" class="navbar2 sticky-top">
    <nuxt-link class="logo" to="/">
      STORE
      <div>
        <i class="fas fa-store"></i>
      </div>
    </nuxt-link>

    <form class="form-inline m-auto">
      <input class="searchbar" type="search" placeholder="Ne arıyordunuz?" aria-label="Search" />
      <button class="searchbutton" type="submit">
        Ara
        <i class="fa fa-search" aria-hidden="true"></i>
      </button>
    </form>

    <nuxt-link
      to="/cart"
      class="m-auto category2 text-center border border-light rounded p-1 category"
    >
      <i class="fa fa-shopping-cart" aria-hidden="true"></i>
      <span class="badge badge-danger ml-1">0</span>
      <div>Sepetim</div>
    </nuxt-link>

    <div class="my-auto categories2">
      <!-- Button trigger modal -->
      <div class="category catsignn border-0" data-toggle="modal" data-target="#login">Giriş Yap</div>

      <div class="category catsignn border-0" data-toggle="modal" data-target="#signup">Kayıt Ol</div>
    </div>
    <!-- Modal -->
    <div
      class="modal"
      id="login"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Giriş Yap</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <form>
              <div class="form-group">
                <label for="email">E-mail Adresi</label>
                <input placeholder="email@örnek.com" class="form-control" id="email" />
              </div>
              <div class="form-group">
                <label for="password">Şifre</label>
                <input type="password" class="form-control" id="password" />
              </div>
              <div class="form-group form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1" />
                <label class="form-check-label" for="exampleCheck1">Beni Hatırla</label>
              </div>
            </form>
          </div>
          <div class="modal-footer">
            <button type="submit" class="giris">Giriş Yap</button>
            <button type="submit" class="giris2">
              <i class="fab fa-facebook"></i> Facebook ile Giriş Yap
            </button>
            <button type="submit" class="giris3">
              <i class="fab fa-google-plus"></i> Google ile Giriş Yap
            </button>
          </div>
        </div>
      </div>
    </div>

    <div
      class="modal"
      id="signup"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel2"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Kayıt Ol</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <form>
              <div class="form-group namesurname">
                <div class="mr-1">
                  <label for="name">Adınız</label>
                  <input class="form-control" id="name" />
                </div>
                <div>
                  <label for="surname">Soyadınız</label>
                  <input class="form-control" id="surname" />
                </div>
              </div>

              <div class="form-group">
                <label for="email">E-mail Adresi</label>
                <input placeholder="email@örnek.com" class="form-control" id="email" />
              </div>
              <div class="form-group">
                <label for="password">Şifre</label>
                <input type="password" class="form-control" id="password" />
              </div>
              <div class="form-group">
                <label for="password">Tekrar Şifre</label>
                <input type="password" class="form-control" id="password" />
              </div>
            </form>
          </div>
          <div class="modal-footer">
            <button type="submit" class="giris">Kayıt Ol</button>
            <button type="submit" class="giris2">
              <i class="fab fa-facebook"></i> Facebook ile Kayıt Ol
            </button>
            <button type="submit" class="giris3">
              <i class="fab fa-google-plus"></i> Google ile Kayıt Ol
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
