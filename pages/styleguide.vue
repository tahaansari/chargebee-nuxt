<template>
  <div>
    <section>
      <div>
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>
      </div>
    </section>
    <section>
      <div>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum
          ratione maxime sequi quis aperiam blanditiis voluptatum animi deserunt
          quod reiciendis magnam, nostrum quas asperiores cumque modi quae
          distinctio dolores accusantium! Explicabo cupiditate voluptatibus
          nostrum necessitatibus tempore pariatur molestias reiciendis vitae
        </p>
        amet nobis nisi hic
      </div>
    </section>
    <section>
      <div>
        <nuxt-link class="btn" to="#"> Get a Consultation </nuxt-link>
        <nuxt-link class="btn btn--noborder" to="#">
          Get a Consultation
        </nuxt-link>
        <nuxt-link class="btn btn--primary" to="#">
          Get a Consultation
        </nuxt-link>
        <div>
          <nuxt-link class="btn btn--link" to="#"> Change Pricing </nuxt-link>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.header {
  background: linear-gradient(-107.11deg, #4300a3 0%, #6100bb 100%);
  color: #ffffff;
  font-size: 40px;
}
</style>
