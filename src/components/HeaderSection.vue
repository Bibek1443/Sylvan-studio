<template>
  <header>
    <!--TOP-HEADER-->
    <div class="top-header">
      <nav class="navbar bg-black">
        <div class="container">
          <div class="left-text">
            <a class="navbar-brand text-white">
              <img src="../assets/icons/logo.svg" alt="" class="p-1" />WELCOME
              TO SYLVAN STUDIO</a
            >
          </div>

          <div class="right-text">
            <a class="navbar-brand text-white active">
              <img
                src="../assets/icons/phone.svg "
                alt=""
                class="p-1"
              />800-877-4758</a
            >
            <a class="navbar-brand text-white">
              <img src="../assets/icons/mail.svg" alt="" class="p-1" />
              info@memoriesbysylvan.com
            </a>
          </div>
        </div>
      </nav>
    </div>

    <!--MID-HEADER-->
    <div class="mid-header">
      <nav class="navbar">
        <div class="container">
          <div class="left-content">
            <div class="buttons">
              <button type="button" class="btn-offer me-2 gap-1">
                <img src="../assets/icons/offer.svg" alt="" class="me-1" />
                <a href="">OFFER ZONE</a>
              </button>
              <button type="button" class="btn-arrival me-2">
                <img src="../assets/icons/arrival.svg" alt="" class="me-1" />
                <a href="">NEW ARRIVALS</a>
              </button>
              <button type="button" class="btn-order">
                <img src="../assets/icons/order.svg" alt="" class="me-1" />
                <a class="me-2" href="">ORDER FORM</a>

                <i class="fa-solid fa-angle-down"></i>
              </button>
            </div>
          </div>

          <button
            class="navbar-toggler border-none"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <!-- <div class="left-text">
                <a class="navbar-brand text-white">
                  <img
                    src="../assets/icons/logo.svg"
                    alt=""
                    class="p-1"
                  />WELCOME TO SYLVAN STUDIO</a
                >
              </div> -->
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="mid-logo">
            <img src="../assets/icons/mid-logo.svg" alt="" />
          </div>

          <div class="right-content">
            <div class="contact-details">
              <div class="phone-group">
                <div class="icon">
                  <img src="../assets/icons/user.svg" alt="" />
                </div>

                <ul class="phones">
                  <li><a class="active">Hello, Sign in</a></li>
                  <li><a>Your Account</a></li>
                </ul>
              </div>
            </div>

            <div class="cart-link pt-3">
              <ul>
                <li><img src="../assets/icons/favourite.svg" alt="" /></li>
                <li><img src="../assets//icons/addtocart.svg" alt="" /></li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
    </div>

    <!--TOP-BORDER-->
    <div class="top-border"></div>

    <!--BOTTOM-HEADER-->
    <section class="bottom-header">
      <div class="container">
        <nav class="navbar navbar-expand-lg navbar-light">
          <div class="container-fluid">
            <li class="nav-item dropdown shop-now">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarScrollingDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                <i class="fa-solid fa-bars me-2"></i> Shop by category
              </a>

              <ul
                class="dropdown-menu"
                aria-labelledby="navbarScrollingDropdown"
              >
                <li>
                  <a class="dropdown-item mb-2 active text-black" href="#">
                    <img src="../assets/icons/badge 1.svg" alt="" />
                    Ribbons
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/rossettes.svg" alt="" />
                    Rossettes</a
                  >
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/banner.svg" alt="" />
                    Banners & Sashes
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/medal.svg" alt="" />
                    Medals
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/trophies.svg" alt="" />
                    Trophies
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/plaques.svg" alt="" />
                    Plaques
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/crystals&glass.svg" alt="" />
                    Crystal& Glass
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/acrylics.svg" alt="" />
                    Acrylics
                  </a>
                </li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/bremate.svg" alt="" />
                    BreMate
                  </a>
                </li>

                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item mb-2" href="#">
                    <img src="../assets/icons/badge 1.svg" alt="" />
                    Something else here</a
                  >
                </li>
              </ul>
            </li>
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <!-- <div class="left-text">
                <a class="navbar-brand text-white">
                  <img
                    src="../assets/icons/logo.svg"
                    alt=""
                    class="p-1"
                  />WELCOME TO SYLVAN STUDIO</a
                >
              </div> -->
              <span class="navbar-toggler-icon"></span>
            </button>

            <div
              class="collapse navbar-collapse ms-5"
              id="navbarSupportedContent"
            >
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <a class="active nav-link me-4" aria-current="page" href="#">
                    Home</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link me-4" href="#"> About </a>
                </li>

                <li class="nav-item">
                  <a class="nav-link me-4" href="#"> Shop </a>
                </li>

                <li class="nav-item">
                  <a class="nav-link me-4" href="#"> Sale </a>
                </li>

                <li class="nav-item">
                  <a class="nav-link me-4" href="#"> Blog </a>
                </li>

                <li class="nav-item">
                  <a class="nav-link me-4" href="#"> Contact us </a>
                </li>
              </ul>
              <form class="d-flex">
                <input
                  class="form-control me-2"
                  type="search"
                  placeholder="Search"
                  aria-label="Search"
                />
              </form>
            </div>
          </div>
        </nav>
      </div>
    </section>
  </header>
</template>