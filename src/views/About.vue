<template>
  <div class="about-card">
    <div class="card-title">
      <img
        height="50px"
        src="https://image.shutterstock.com/image-vector/male-default-placeholder-avatar-profile-260nw-387516193.jpg"
        class="avatar"
        alt
      />
      <div class="title-text-content">
        <p>About Me</p>
        <h2>John Doe</h2>
      </div>
    </div>

    <div class="card-content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi voluptate ratione qui et error dolorum totam quia. Nobis labore dicta alias omnis eos ea illo nesciunt repellat dignissimos commodi corrupti dolorem officiis qui, maiores vitae tempora! Distinctio, necessitatibus quibusdam. Quas itaque enim quos deserunt nisi? Culpa distinctio suscipit quos dicta!</p>
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Photoshop, Figma, Canvas, Adobe XD</td>
        </tr>
        <tr>
          <td>Front-end</td>
          <td>React.js, Vue.js, HTML, CSS, javaScript</td>
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Express.js, MongoDB, Mongoose, GraphQL</td>
        </tr>
        <tr>
          <td>Shop</td>
          <td>Stripe, PayFast, E-commerce, CMS</td>
        </tr>
      </table>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque hic, quibusdam ipsum aut tempore minima! Maiores, laudantium mollitia. Molestiae mollitia fugit deserunt provident quaerat esse ducimus! Quidem magni quaerat maxime nobis? Inventore cumque vero voluptatum aut facilis, autem cum minus, obcaecati saepe est, ducimus fugit doloremque aliquid quibusdam. Quisquam, eligendi.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque, sequi quod explicabo ipsa nesciunt consequuntur nam unde numquam, perspiciatis ipsam ex possimus itaque. Eius mollitia, inventore minus nulla eum maiores sit! Nam sequi consequatur veritatis temporibus distinctio. Impedit nostrum fugit harum sit adipisci, deleniti aspernatur dolorum est non nesciunt fugiat.</p>
    </div>
  </div>
</template>



<style lang="sass" scoped>
.about-card
  background: #333
  padding: 3rem
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content
    p
      margin-bottom: 0
      color: rgb(210, 210, 210)
    h2
      margin-top: 0
.card-content p
  line-height: 1.5
  margin: 30px auto

table
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none
</style>