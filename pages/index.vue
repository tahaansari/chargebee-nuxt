<template>
  <div>
    <header class="header">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-6 col-lg-2">
            <img class="logo" src="~/assets/images/logo.svg" alt="" />
          </div>
          <div class="col-lg-10 d-none d-lg-block">
            <div class="d-flex align-items-center justify-content-between">
              <nav class="nav">
                <ul class="nav__list d-lg-flex">
                  <li class="px-3">
                    <nuxt-link to="#"> Product </nuxt-link>
                  </li>
                  <li class="px-3">
                    <nuxt-link to="#"> Pricing </nuxt-link>
                  </li>
                  <li class="px-3">
                    <nuxt-link to="#"> Solutions </nuxt-link>
                  </li>
                  <li class="px-3">
                    <nuxt-link to="#"> Customers </nuxt-link>
                  </li>
                  <li class="px-3">
                    <nuxt-link to="#"> Resources </nuxt-link>
                  </li>
                </ul>
              </nav>
              <div class="d-flex justify-content-end">
                <nuxt-link to="#" class="btn btn--noborder mr-3">
                  Schedule a Demo
                </nuxt-link>
                <nuxt-link to="#" class="btn btn--primary"> Log in </nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-6 d-lg-none">
            <div class="d-flex justify-content-end">
              <img class="hamburger" src="~/assets/images/menu.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </header>
    <section class="banner">
      <div class="container">
        <div class="row">
          <div class="col-lg-5">
            <h2 class="banner__heading banner__heading--1">
              Subscription <br />
              Billing & Revenue <br />
              Operations
            </h2>
            <h2 class="banner__heading banner__heading--2 mb-3">
              For Businesses <br />
              Designed for Growth
            </h2>
            <p class="mb-5">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex
              recusandae, labore nisi corporis reprehenderit dolorem quidem
              nobis non maiores amet, porro at ratione! Perspiciatis, placeat!
            </p>
            <div class="d-flex flex-column flex-lg-row mb-5">
              <nuxt-link to="#" class="btn btn--primary mb-3 mb-lg-0 mr-lg-3"
                >Get a Consultation</nuxt-link
              >
              <nuxt-link to="#" class="btn">Sign Up for Free</nuxt-link>
            </div>
            <div>
              <p>
                Trusted by leading brands to process over $3Bn in recurring
                revenue
              </p>
              <div class="d-flex">
                <div class="mr-3">Goop</div>
                <div class="mr-3">Study.com</div>
                <div class="mr-3">Freshworks</div>
              </div>
            </div>
          </div>
          <div class="col-lg-7 d-none d-lg-block">
            <h1>Right banner</h1>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-3">
            <div class="info">
              <div class="info__title mb-2">Deploy Strategies</div>
              <h3 class="info__heading mb-4">
                What does this challenge make possible
              </h3>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus
                suscipit exercitationem commodi, odio optio ab distinctio
                reprehenderit, quibusdam dicta numquam.
              </p>
            </div>
          </div>
          <div class="col-lg-8">
            <h2>Slider</h2>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-3">
            <div class="info">
              <div class="info__title mb-2">Beyond Billing</div>
              <h3 class="info__heading mb-4">
                Streamline Your Entire RevOps Workflow
              </h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Corporis voluptatum esse impedit quaerat at nostrum suscipit?
                Distinctio, dolorem.
              </p>
            </div>
          </div>
          <div class="col-lg-8">
            <b-tabs class="workflow" content-class="mt-3">
              <b-tab title="Subscription Automation" active>
                <div class="row">
                  <div
                    class="col-lg-8 d-flex justify-content-center justify-content-lg-end"
                  >
                    <img
                      class="limit-img"
                      src="~/assets/images/subscription-automation.svg"
                      alt=""
                    />
                  </div>
                  <div class="col-lg-4">
                    <div class="info">
                      <h6 class="info__heading">
                        Automate the <br />
                        Order-to-Revenue <br />
                        Lifecycle
                      </h6>
                      <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Vitae, minima?
                      </p>
                      <nuxt-link to="#" class="btn btn--link"
                        >Biling Exprience</nuxt-link
                      >
                    </div>
                  </div>
                </div>
              </b-tab>
              <b-tab title="Billing Experiments">
                <p>Billing Experiments</p>
              </b-tab>
              <b-tab title="Extensible Plathform">
                <p>Extensible Plathform</p>
              </b-tab>
            </b-tabs>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div
            class="col-lg-9 d-flex justify-content-center justify-content-lg-end"
          >
            <img
              class="limit-img"
              src="~/assets/images/billing-experiments.svg"
              alt=""
            />
          </div>
          <div class="col-lg-3">
            <div class="info">
              <h5 class="info__heading">
                Evolve your Billing Workflow to Fit Your Business Strategy
              </h5>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae,
                minima?
              </p>
              <nuxt-link to="#" class="btn btn--link"
                >Biling Exprience</nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div
            class="col-lg-9 d-flex justify-content-center justify-content-lg-end"
          >
            <img
              class="limit-img"
              src="~/assets/images/integration.svg"
              alt=""
            />
          </div>
          <div class="col-lg-3">
            <div class="info">
              <h5 class="info__heading">
                Scale Your Revenue Stack for Each Stage of Growth
              </h5>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Eveniet, cupiditate aspernatur assumenda totam architecto autem.
              </p>
              <nuxt-link to="#" class="btn btn--link"
                >Entinsible Plathform</nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div class="col">
            <b-tabs class="testimonial" content-class="mt-3">
              <b-tab title="Rethink Pricing" active>
                <div class="testimonial-item">
                  <h3 class="testimonial-item__title">
                    Achive 20x ROI <br />
                    with Chargebee
                  </h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Quasi dicta alias tempore obcaecati officia beatae
                    consequatur nam quos deserunt a!
                  </p>
                  <nuxt-link to="#" class="btn btn--link"
                    >Read Case Study</nuxt-link
                  >
                  <div>
                    <img
                      class="testimonial-item__thumbnail"
                      src="~/assets/images/nathanfeld-drawboard.png"
                      alt=""
                    />
                    <p>
                      Nathan Field, <br />
                      Drawboard
                    </p>
                  </div>
                </div>
              </b-tab>
              <b-tab title="Automate Finops">
                <p>Automate Finops</p>
              </b-tab>
              <b-tab title="Go Global">
                <p>Go Global</p>
              </b-tab>
            </b-tabs>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-5">
            <div class="info">
              <div class="info__title mb-2">For the mordern cfo</div>
              <h3 class="info__heading mb-5">
                Spending less time Closing, <br />
                More time Driving.
              </h3>
            </div>
          </div>
        </div>
        <div class="row feature">
          <div class="col-lg-4 mb-4 pr-lg-5">
            <h5 class="feature__title font-bold">GAAP Compliant RevRec</h5>
            <p class="mb-1">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus,
              neque.
            </p>
            <nuxt-link to="#" class="btn btn--link"
              >Entinsible Plathform</nuxt-link
            >
          </div>
          <div class="col-lg-4 mb-4 pr-lg-5">
            <h5 class="feature__title font-bold">GAAP Compliant RevRec</h5>
            <p class="mb-1">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus,
              neque.
            </p>
            <nuxt-link to="#" class="btn btn--link"
              >Entinsible Plathform</nuxt-link
            >
          </div>
          <div class="col-lg-4 mb-4 pr-lg-5">
            <h5 class="feature__title font-bold">GAAP Compliant RevRec</h5>
            <p class="mb-1">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus,
              neque.
            </p>
            <nuxt-link to="#" class="btn btn--link"
              >Entinsible Plathform</nuxt-link
            >
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-7">
            <h2 class="footer-heading mb-4">
              Exprience the Smartest Way to Automate Recurring Payments
            </h2>
          </div>
          <div class="col-lg-5">
            <div class="d-flex flex-column flex-lg-row">
              <nuxt-link to="#" class="btn btn--primary mb-3 mb-lg-0 mr-lg-3">
                Schedule a Demo
              </nuxt-link>
              <nuxt-link to="#" class="btn"> Sign up for Free </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
@import '~/assets/scss/variables.scss';
</style>
