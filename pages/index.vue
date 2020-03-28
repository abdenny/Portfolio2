<template>
  <!-- Content -->
  <div class="content">
    <!-- Profile -->
    <img class="content__profile" src="/img/me.jpg" />
    <article
      class="content__article content__article--center content__article--margin-16"
    >
      <p class="content__article-title content__article-title--large">
        Austin Denny
      </p>
      <p class="content__article-subtitle">
        Web Developer
      </p>
      <p class="content__article-links">
        <a
          href="https://resumepdfad.s3.us-east-2.amazonaws.com/AustinDennyAtsResume2020.pdf"
          target="_blank"
        >
          <i class="far fa-file-alt content__article-link" />
        </a>
        <a href="https://github.com/abdenny" target="_blank">
          <i class="fab fa-github content__article-link" />
        </a>
        <a
          href="https://linkedin.com/in/austin-denny-0b77a8197/"
          target="_blank"
        >
          <i class="fab fa-linkedin-in content__article-link" />
        </a>
        <a href="mailto:austinbdenny@gmail.com" target="_blank">
          <i class="far fa-envelope content__article-link" />
        </a>
      </p>
    </article>

    <!-- About Me -->
    <article class="content__article content__article--margin-16">
      <p class="content__article-details">
        Recent Grad. Lover of all things science & tech. Passionate about
        responsive web design and minimalist single-page applications. As a
        former researcher, what I enjoy most about software development is how
        it rewards problem-solving and the application of scientific thinking,
        irrespective of material conditions.<br /><br />

        I'm driven to learn new technologies, broaden my knowledge of the tech
        industry, and make meaningful contributions to projects. Feel free to
        <a href="mailto:austinbdenny@gmail.com" target="_blank">reach out</a>!
        I'm open to exploring new opportunities that will challenge my current
        skill set, and offer long term growth potential.
      </p>
    </article>

    <!-- Projects -->
    <article class="content__article content__article--margin-24">
      <p class="content__article-title content__article-title--medium">
        <i class="fa fa-briefcase" /> Projects
      </p>
      <hr />
    </article>

    <!-- Project -->
    <article class="content__article content__article--margin-8">
      <!-- Title -->
      <p class="content__article-title content__article-title">
        Tribuo
      </p>
      <!-- Details -->
      <p class="content__article-details content__article--margin-8">
        Tribuo is a full-stack web app for company-wide task management that
        tracks employees, departments, and tasks in a relational database.<br />
        <span class="content__article-metadata">
          <b><i class="fa fa-code" /> Technology:</b> HTML, CSS, JavaScript ES6,
          AJAX, Node.js, Express, PostgreSQL, Sequelize, EJS, Hasura, Heroku,
          and GraphQL. Deployed on AWS (RDS & EC2).
        </span>
      </p>
      <!-- Preview -->
      <a
        href="http://ec2-18-222-118-237.us-east-2.compute.amazonaws.com"
        target="_blank"
      >
        <img src="/img/tribuo.png" class="content__article-preview" />
      </a>
      <!-- Links -->
      <p class="content__article-details">
        -- <br />
        <a
          href="http://ec2-18-222-118-237.us-east-2.compute.amazonaws.com"
          target="_blank"
          >Demo</a
        >
        |
        <a href="https://github.com/abdenny/Tribuo" target="_blank"
          >View on Github</a
        >
      </p>
      <hr />
    </article>

    <!-- Project -->
    <article class="content__article content__article--margin-8">
      <!-- Title -->
      <p class="content__article-title content__article-title">
        Book•Smart
      </p>
      <!-- Details -->
      <p class="content__article-details content__article--margin-8">
        Book•Smart is a front-end API-driven search engine for finding books and
        viewing both historical and current bestseller data from The New York
        Times.<br />
        <span class="content__article-metadata">
          <b><i class="fa fa-code" /> Technology:</b> HTML, CSS, Javascript ES6,
          AJAX, and JSON. Deployed on AWS S3.
        </span>
      </p>
      <!-- Preview -->
      <a
        href="http://jayesolutions.net.s3-website.us-east-2.amazonaws.com/index.html"
        target="_blank"
      >
        <img src="/img/homepage.png" class="content__article-preview" />
      </a>
      <!-- Links -->
      <p class="content__article-details">
        -- <br />
        <a
          href="http://jayesolutions.net.s3-website.us-east-2.amazonaws.com/index.html"
          target="_blank"
          >Demo</a
        >
        |
        <a href="https://github.com/abdenny/Book_Smart" target="_blank"
          >View on Github</a
        >
      </p>
      <hr />
    </article>

    <!-- Project -->
    <article class="content__article content__article--margin-8">
      <!-- Title -->
      <p class="content__article-title content__article-title">
        Title
      </p>
      <!-- Details -->
      <p class="content__article-details content__article--margin-8">
        Blackjack is a front-end app that allows users to play blackjack against
        the dealer, complete with full game logic.<br />
        <span class="content__article-metadata">
          <b><i class="fa fa-code" /> Technology:</b> HTML, CSS, Javascript
        </span>
      </p>
      <!-- Preview -->
      <a href="https://abdenny.github.io/Blackjack" target="_blank">
        <img src="/img/blackjack.png" class="content__article-preview" />
      </a>
      <!-- Links -->
      <p class="content__article-details">
        -- <br />
        <a href="https://abdenny.github.io/Blackjack" target="_blank">Demo</a> |
        <a href="https://github.com/abdenny/Blackjack" target="_blank"
          >View on Github</a
        >
      </p>
      <hr />
    </article>
  </div>
</template>

<style>
/* Block Elements */
.content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  z-index: 4;
}
.content__profile {
  height: 180px;
  width: 180px;
  border: solid white 4px;
  border-radius: 50%;
  box-shadow: 2px 2px 8px #494b4b;
}
.content__article {
  width: 100%;
}
.content__article-title {
  font-size: 22px;
  font-weight: bold;
  color: #3a4145;
}
.content__article-subtitle {
  font-size: 22px;
  font-weight: bold;
  color: #a9a9a9;
}
.content__article-details {
  font-size: 16px;
}
.content__article-metadata {
  font-size: 13px;
}
.content__article-links {
  margin: 8px 0;
}
.content__article-link {
  font-size: 22px;
  margin: 0 8px;
}
.content__article-preview {
  width: 100%;
  max-width: 800px;
  margin-top: 16px;
}

/* Modifiers */
.content__article-title--medium {
  font-size: 32px;
  font-weight: bold;
}
.content__article-title--large {
  font-size: 40px;
  font-weight: bold;
}
.content__article--center {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.content__article--margin-8 {
  margin-top: 8px;
}
.content__article--margin-16 {
  margin-top: 16px;
}
.content__article--margin-24 {
  margin-top: 24px;
}

@media only screen and (min-width: 800px) {
  .content {
    width: 800px;
  }
}
</style>
