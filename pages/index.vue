<template lang="pug">
    .wrapper
      div(class="row columns is-multiline")
        .card(class="column is-6")
          .card-images
            h1
            img(src="/images/profile.jpg")
        .card(class="column is-6")
          .card-content
            h1.title.is-1.has-text-weight-bold About Me
            h3.title.is-3 My name is Indah Widowati
            p.is-size-5 Results-oriented Front-end Developer dedicated to creating and optimizing interactive and user-friendly.Leverage analytical skills and strong attention to detail in order to deliver original andefficient web solutions, provide technical knowledge and expertise, build new websites from start to finish, and successfully manage a team of other software professionals.
            .contact
              h5.is-size-5.has-text-weight-semibold Contact
              | widowati.indah07@gmail.com
            .social-media
              a.title.is-3(href="https://github.com/indahwii") Github
              a.title.is-3(href="https://www.linkedin.com/in/indahwii/") LinkedIn
              a.title.is-3(href="https://www.instagram.com/indahwii/") Instagram
          
          
</template>

<script>
export default {}
</script>

<style>
  .mt-2 {
    margin-top: 2rem;
  }

  .wrapper {
    padding: 30px;
  }

  .contact {
    margin-top: 1rem;
  }

  .social-media {
    margin-top: 1rem;
    display: flex;
    left: 0;
    position: relative;
  }

  a{
    color: #000;
    margin-right: 10px;
  }


</style>
