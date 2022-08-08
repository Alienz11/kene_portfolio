<template>
  <div>
     

    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#" class="nav__logo"  >Kenechukwu Nsofor</a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                     <li class="nav__item"><a href="#portfolio" class="nav__link">Portfolio</a></li>
                    <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>



            <div class="nav__toggle" id="nav-toggle">
                <i class='bx bx-menu'></i>
            </div>
        </nav>
    </header>

    <main class="l-main">
        <!--===== HOME =====-->
        <section class="home" id="home">
            <div class="home__container bd-grid">
                <h4 class="home__title">HEY,<br> I'm  <span class="make_black">Kene</span> I <br>build <span> webapps</span><br></h4>

                <div class="home__scroll">
                    <a href="#about" class="home__scroll-link"><i class='bx bx-up-arrow-alt' ></i>Scroll down</a>
                </div>

                <img src="@/assets/img/preg1.png" alt="" class="home__img" style="background">
            </div>
        </section>



        <!-- // portfolio -->
<section class="portfolio section" id="portfolio">
            <h2 class="section-title">Portfolio</h2>
            <h4 class="portfolio__link-name">   Here are a few design projects I've worked on recently, click to visit the site. Want to see more?
                 <a href="#contact" style="color: #5361FF"> Email me.</a>   </h4>

            <div class="portfolio__container bd-grid">
                 <div class="portfolio__img">
                    <img src="./assets/img/guestbook.png" alt="">

                    <div class="portfolio__link">
                        <a href="https://fl-guest-book.herokuapp.com/" class="portfolio__link-name"> A guest book application built with Python and web flask framework  
                          <br><br>
                        visit site  <span style="color: #5361FF"> <i class='bx bx-link-external' ></i>   </span></a>
                    </div>
                </div>

                <div class="portfolio__img">
                    <img src="./assets/img/maze.png" alt="">

                    <div class="portfolio__link">
                        <a href="https://github.com/Alienz11/Maze_Project_Alx" class="portfolio__link-name">A maze game built with C programing
                            language and SDL2 media tool, modeled based on Wolfenstein 1981 <br><br>
                        visit site  <span style="color: #5361FF"> <i class='bx bx-link-external' ></i>   </span></a>
                    </div>
                </div>
                <div class="portfolio__img">
                    <img src="./assets/img/calorypal.png" alt="">

                    <div class="portfolio__link">
                        <a href="#" class="portfolio__link-name">A web app that stores data about the user's food and calories it
                             contains to keep track and eat healthy<br><br>
                        visit site  <span style="color: #5361FF"> <i class='bx bx-link-external' ></i>   </span></a>
                    </div>
                </div>
            </div>
        </section>

  <!-- //skills -->

        <section class="skills section" id="skills">
            <h2 class="section-title">Skills</h2>

            <div class="skills__container bd-grid">
                <div class="skills__box">
                    <h3 class="skills__subtitle">Development</h3>
                    <span class="skills__name">Html  <i class='bx bxl-html5'></i></span>
                    <span class="skills__name">Css <i class='bx bxl-css3'></i></span>
                    <span class="skills__name">Javascript <i class='bx bxl-javascript' ></i></span>
                    <span class="skills__name">Vue <i class='bx bxl-vuejs' ></i></span>
                    <span class="skills__name">Heroku<i class='bx bxl-heroku' ></i></span>
                    <span class="skills__name">Git<i class='bx bxl-git' ></i></span>
                     <span class="skills__name">React<i class='bx bxl-react'></i></span>
                     <span class="skills__name">Firebase<i class='bx bxl-firebase' ></i></span>
                    <span class="skills__name">Node <i class='bx bxl-nodejs'></i></span>
                    <span class="skills__name">Python <i class='bx bxl-python'></i></span>
                    <span class="skills__name">Django <i class='bx bxl-django'></i></span>
                    <span class="skills__name">Flask <i class='bx bxl-flask'></i></span>
                    <span class="skills__name">C/C++ <i class='bx bxl-c-plus-plus'></i></span>
                    <span class="skills__name">Cloud Functions <i class='bx bx-cloud-upload' ></i></span>
                   <span class="skills__name">Bootstrap <i class='bx bxl-bootstrap' ></i></span>
                </div>

                <div class="skills__img">
                    <img src="./assets/img/theskill.png" alt="">
                </div>
            </div>
        </section>


        <!-- // about -->


        <section class="about section" id="about">
            <h2 class="section-title">About</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="@/assets/img/kene.png" alt="">
                </div>

                <div>
                    <h2 class="about__subtitle">I am Kenechukwu Nsofor</h2>
                    <span class="about__profession">Web developer and Devops engineer</span>
                    <p align=justify class="about__text">
                       I am a Software Engineering graduate from Holberton School, where I got hands on experience with Web Development,
                       Web App Development and Development Operations(Devops). I mostly enjoy back-end development as I specialized in
                       back-end development in Holberton School using Python and Javascript. But with my knowledge in React, Vue, Html and CSS I am more of a Full-Stack
                       developer. 

                    
                    </p>

                    <div class="about__social">
                        <a href="https://www.linkedin.com/in/kenechukwu-nsofor-3472ab132" class="about__social-icon"><i class='bx bxl-linkedin' ></i></a>
                        <a href="https://github.com/Alienz11" class="about__social-icon"><i class='bx bxl-github' ></i></a>
                        <a href="https://www.facebook.com/kenechukwu.nsofor" class="about__social-icon"><i class='bx bxl-facebook' ></i></a>
                        <a href="https://weeztechnology.wordpress.com/" class="about__social-icon"><i class='bx bxl-wordpress' ></i></a>

                    </div>
                </div>
            </div>
        </section>



      



      


        <!--===== CONTACT =====-->
        <section class="contact section" id="contact">
            <h2 class="section-title">Contact</h2>

            <div class="contact__container bd-grid">
                <div class="contact__info">
                    <h3 class="contact__subtitle">EMAIL</h3>
                    <span class="contact__text">nsoforkenechukwu2@gmail.com</span>

                    <h3 class="contact__subtitle">PHONE</h3>
                    <span class="contact__text">+234 8133588057</span>

                    <h3 class="contact__subtitle">ADDRESS</h3>
                    <span class="contact__text">No. 36 Apkata rd, Shomolu, Lagos, Nigeria</span>
                </div>

                <form action="" class="contact__form" @submit.prevent="sendEmail">
                    <div class="contact__inputs">
                        <input type="text" placeholder="Name" class="contact__input" name="name" v-model="name"> 
                        <input type="mail" placeholder="Email" class="contact__input" name="email" v-model="email">
                    </div>

                    <textarea name="message" id="" cols="0" rows="10" class="contact__input"  v-model="message"></textarea>

                    <input type="submit" value="submit" class="contact__button">
                </form>
            </div>
        </section>



        <footer class="footer section">
            <div class="footer__container bd-grid">
                <div class="footer__data">
                    <h2 class="footer__title">Kenechukwu Nsofor</h2>
                    <p class="footer__text">I am  Kenechukwu Nsofor and this is my website</p>
                </div>

                <div class="footer__data">
                    <h2 class="footer__title">EXPLORE</h2>
                    <ul>
                        <li><a href="#home" class="footer__link">Home</a></li>
                        <li><a href="#about" class="footer__link">About</a></li>
                        <li><a href="#skills" class="footer__link">Skills</a></li>
                        <li><a href="#portfolio" class="footer__link">Portfolio</a></li>
                        <li><a href="#Contact" class="footer__link">Contact</a></li>
                    </ul>
                </div>

                <div class="footer__data">
                    <h2 class="footer__title">FOLLOW</h2>
                    <a href="https://www.linkedin.com/in/kenechukwu-nsofor-3472ab132" class="about__social-icon"><i class='bx bxl-linkedin' ></i></a>
                        <a href="https://github.com/Alienz11" class="about__social-icon"><i class='bx bxl-github' ></i></a>
                        <a href="https://www.facebook.com/kenechukwu.nsofor" class="about__social-icon"><i class='bx bxl-facebook' ></i></a>
                        <a href="https://weeztechnology.wordpress.com/" class="about__social-icon"><i class='bx bxl-wordpress' ></i></a>
                </div>


            </div>
        
        </footer>



    </main>

  </div>
</template>

<script>
// import ScrollReveal from 'scrollreveal'
// import { menuScroll } from './components/scroll';
// import emailjs from 'emailjs-com';
import dotenv from 'dotenv';
dotenv.config();


// export default {
//     data() {
//     return {
//       name: '',
//       email: '',
//       message: ''
//     }
//   },
//    mounted() {
//        menuScroll();


//     },
//     methods: {
// // 'service_1zuqst5', 'template_p8oju5z', e.target, 'user_taeyowfinVFhWZK6jHrrm'
       
//     sendEmail(e) {
//       try {
//         emailjs.sendForm('service_1zuqst5', 'template_p8oju5z', e.target,
//         'user_taeyowfinVFhWZK6jHrrm', {
//           name: this.name,
//           email: this.email,
//           message: this.message
//         })
//     console.log('success');
//       } catch(error) {
//           console.log({error})
//       }
//       // Reset form field
//       this.name = ''
//       this.email = ''
//       this.message = ''
//     },
//   }
// }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


    /*===== GOOGLE FONTS =====*/
    
    @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600;700&display=swap");
    /* variable css */
    
     :root {
        --header-height: 3rem;
        --font-medium: 500;
    }
    /* colors */
    
     :root {
        --first-color: #5361FF;
        --white-color: #FAFAFF;
        --dark-color: #2A3B47;
        --text-color: #697477;
    }
    /* font-sizes */
    
     :root {
        --body-font: 'Montserrat', sans-serif;
        --big-font-size: 4rem;
        --h2-font-size: 1.25rem;
        --normal-font-size: .983rem;
        --small-font-size: 813rem;
    }
    
    @media screen and (min-width:768px) {
         :root {
            --big-font-size: 5.5rem;
            --h2-font-size: 2rem;
            --normal-font-size: 1rem;
            --small-font-size: 813rem;
        }
    }
    /*===== Margenes =====*/
    
     :root {
        --mb-1: .5rem;
        --mb-2: 1rem;
        --mb-3: 1.5rem;
        --mb-4: 2rem;
    }
    /*===== z index =====*/
    
     :root {
        --z-fixed: 100;
    }
    
    *,
     ::before,
     ::after {
        box-sizing: border-box;
    }
    
    html {
        scroll-behavior: smooth;
    }
    
    body {
        margin: var(--header-height) 0 0 0;
        font-family: var(--body-font);
        font-size: var(--normal-font-size);
        font-weight: var(--font-medium);
        color: var(--text-color);
        line-height: 1.6;
    }
    
    h1,
    h2,
    p {
        margin: 0;
    }
    
    ul {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    
    a {
        text-decoration: none;
        color: var(--text-color);
    }
    
    img {
        max-width: 100%;
        height: auto;
        display: block;
    }
    /* //class css */
    
    .section {
        padding: 3rem 0;
    }
    
    .section-title {
        position: relative;
        font-size: var(--h2-font-size);
        color: var(--dark-color);
        margin: var(--mb-4) 0;
        text-align: center;
    }
    
    .section-title::after {
        position: absolute;
        content: "";
        width: 32px;
        height: .18rem;
        left: 0;
        right: 0;
        margin: auto;
        top: 2rem;
        background-color: var(--first-color);
    }
    
    .bd-grid {
        max-width: 1024px;
        display: grid;
        grid-template-columns: 100%;
        grid-column-gap: 2rem;
        width: calc(100%-2rem);
        margin-left: var(--mb-2);
        margin-right: var(--mb-2);
    }
    
    .l-header {
        width: 100%;
        position: fixed;
        top: 0;
        left: 0;
        z-index: var(--z-fixed);
        background-color: var(--first-color);
    }
    
    .nav {
        height: var(--header-height);
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    @media screen and (max-width: 768px) {
        .nav__menu {
            position: fixed;
            top: var(--header-height);
            right: -100%;
            width: 80%;
            height: 100%;
            padding: 2rem;
            background-color: rgba(255, 255, 255, .3);
            transition: .5s;
            backdrop-filter: blur(10px);
        }
    }
    
    .nav__item {
        margin-bottom: var(--mb-4);
    }
    
    .nav__link {
        position: relative;
        color: var(--dark-color);
    }
    
    .nav__link:hover {
        color: var(--first-color);
    }
    
    .nav__logo {
        color: var(--white-color);
    }
    
    .nav__toggle {
        color: var(--white-color);
        font-size: 1.5rem;
        cursor: pointer;
    }
    
    .show {
        right: 0;
    }
    /* // active menu */
    
    .active::after {
        position: absolute;
        content: "";
        width: 100%;
        height: .18rem;
        left: 0;
        top: 2rem;
        background-color: var(--first-color);
    }
    /* home */
    
    .home {
        position: relative;
        background-color: var(--first-color);
        overflow: hidden;
    }
    
    .home__container {
        row-gap: 5rem;
    }
    
    .home__title {
        align-self: flex-end;
        font-size: var(--big-font-size);
        color: var(--white-color);
        line-height: .9;
    }
    
    /* .home__title span {
        text-shadow: 0 20px 25px rgba(0, 0, 0, .5);
    } */
    
    .home__scroll {
        align-self: flex-end;
        padding-bottom: var(--mb-4);
    }
    
    .home__scroll-link {
        writing-mode: vertical-lr;
        transform: rotate(-180deg);
        color: var(--white-color);
    }
    
    .home__img {
        position: absolute;
        right: 0;
        bottom: 0;
        width: 295px;
    }
    /* about */
    
    .about__container {
        justify-items: center;
        row-gap: 2rem;
        text-align: center;
    }
    
    .about__img {
        display: flex;
        justify-content: center;
        padding-top: 1rem;
        width: 100%;
        height: 100%;
        border-radius: 5%;
        overflow: hidden;
        object-fit: cover;
    }
    
    .about__img img {
        width: 100px;
    }
    
    .about__subtitle {
        font-size: var(--h2-font-size);
        color: var(--first-color);
        margin-bottom: var(--mb-1);
    }
    
    .about__text {
        margin-bottom: var(--mb-4);
    }
    
    .about__profession {
        display: block;
        margin-bottom: var(--mb-4);
    }
    
    .about__social-icon {
        font-size: 1.4rem;
        margin: 0 var(--mb-1);
    }
    
    .about__social-icon:hover {
        color: var(--first-color);
    }
    /* // skills */
    
    .skills__container {
        row-gap: 2rem;
    }
    
    .skills__subtitle {
        color: var(--first-color);
        margin-bottom: var(--mb-3);
    }
    
    .skills__name {
        display: inline-block;
        margin-right: var(--mb-2);
        margin-bottom: var(--mb-3);
        padding: .25rem .5rem;
        background-color: var(--white-color);
        border-radius: .25rem;
    }
    
    .skills__name:hover {
        background-color: var(--first-color);
        color: var(--white-color);
    }
    
    .skills__img img {
        border-radius: .5rem;
    }
    /* ===== PORTFOLIO =====*/
    
    .portfolio {
        background-color: var(--white-color);
    }
    
    .portfolio__container {
        justify-items: center;
        row-gap: 5rem;
    }
    
    .portfolio__img {
        position: relative;
        overflow: hidden;
    }
    
    .portfolio__img img {
        border-radius: .5rem;
    }
    
    .portfolio__link {
        position: absolute;
        bottom: -100%;
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgba(255, 255, 255, .3);
        border-radius: .5rem;
        cursor: pointer;
        backdrop-filter: blur(10px);
        transition: .3s;
    }
    
    .portfolio__img:hover .portfolio__link {
        bottom: 0;
    }

    .make_black{
          color: var(--dark-color);
    }
    
    .portfolio__link-name {
        color: var(--dark-color);
        text-align: center;
    }
    /* // contact */
    
    .contact__container {
        row-gap: 2rem;
    }
    
    .contact__subtitle {
        font-size: var(--normal-font-size);
        color: var(--first-color);
    }
    
    .contact__text {
        display: inline-block;
        margin-bottom: var(--mb-2);
    }
    
    .contact__inputs {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        column-gap: 1rem;
    }
    
    .contact__input {
        width: 100%;
        padding: .8rem;
        outline: none;
        border: 1.5px solid var(--dark-color);
        font-size: var(--normal-font-size);
        margin-bottom: var(--mb-4);
        border-radius: .5rem;
    }
    
    .contact__button {
        display: block;
        background-color: var(--first-color);
        color: var(--white-color);
        padding: .75rem 2.5rem;
        margin-left: auto;
        border-radius: .5rem;
        border: none;
        outline: none;
        font-size: var(--normal-font-size);
        cursor: pointer;
    }
    /* // footer */
    
    .footer {
        background-color: var(--dark-color);
    }
    
    .footer__container {
        row-gap: 2rem;
    }
    
    .footer__title {
        font-size: var(--normal-font-size);
        color: var(--white-color);
        margin-bottom: var(--mb-2);
    }
    
    .footer__link {
        padding: .25rem 0;
    }
    
    .footer__link:hover {
        color: var(--first-color);
    }
    
    .footer__social {
        font-size: 1.4rem;
        margin-right: var(--mb-1);
    }
    
    .footer__social:hover {
        color: var(--first-color);
    }
    /* // media screens */
    
    @media screen and (min-width: 768px) {
        body {
            margin: 0;
        }
        .section {
            padding-top: 4rem;
        }
        .section-title {
            margin-bottom: 3rem;
        }
        .section-title::after {
            width: 64px;
            top: 3rem;
        }
        .nav {
            height: calc(var(--header-height) + 1rem);
        }
        .nav__list {
            display: flex;
        }
        .nav__item {
            margin-left: var(--mb-4);
            margin-bottom: 0;
        }
        .nav__toggle {
            display: none;
        }
        .nav__link {
            color: var(--white-color);
        }
        .nav__link:hover {
            color: var(--white-color);
        }
        .active::after {
            background-color: var(--white-color);
        }
        .home__container {
            height: 100vh;
            grid-template-rows: 1.7fr 1fr;
            row-gap: 0;
        }
        .home__img {
            width: 404px;
            right: 10%;
        }
        .about__container {
            grid-template-columns: repeat(2, 1fr);
            align-items: center;
            text-align: initial;
            padding: 4rem 0;
        }
        .about__img {
            width: 45%;
            height: 70%;
        }
        .about__img img {
            width: 100%;
        }
        .skills__container {
            grid-template-columns: repeat(2, 1fr);
            align-items: center;
        }
        .portfolio__container {
            grid-template-columns: repeat(3, 1fr);
            grid-template-rows: repeat(2, 1fr);
            column-gap: 2rem;
        }
        .contact__container {
            grid-template-columns: repeat(2, 1fr);
            justify-items: center;
        }
        .contact__form {
            width: 380px;
        }
        .footer__container {
            grid-template-columns: repeat(3, 1fr);
            justify-items: center;
        }
    }
    
    @media screen and (min-width: 1024px) {
        .bd-grid {
            margin-left: auto;
            margin-right: auto;
        }
    }

    #particles-js {
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: #b61924;
  background-image: url("");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}

/* ---- stats.js ---- */

.count-particles{
  background: #000022;
  position: absolute;
  top: 48px;
  left: 0;
  width: 80px;
  color: #13E8E9;
  font-size: .8em;
  text-align: left;
  text-indent: 4px;
  line-height: 14px;
  padding-bottom: 2px;
  font-family: Helvetica, Arial, sans-serif;
  font-weight: bold;
}

.js-count-particles{
  font-size: 1.1em;
}

#stats,
.count-particles{
  -webkit-user-select: none;
  user-select: none
}

#stats{
  border-radius: 3px 3px 0 0;
  overflow: hidden;
}

.count-particles{
  border-radius: 0 0 3px 3px;
}

</style>
