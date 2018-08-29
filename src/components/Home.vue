<template>
  <div class="home">
    <div class="home_background">
      <div class="home_nav">
      <nav>
        <a href="#" v-scroll-to="'#div-portfolio'" class="nav_elements">PORTFOLIO</a>
        <a href="#" v-scroll-to="'#div-about'" class="nav_elements">ABOUT</a>
        <a href="#" v-scroll-to="'#div-skills'" class="nav_elements">SKILLS</a>
        <a href="#" v-scroll-to="'#div-contact'" class="nav_elements">CONTACT</a>
      </nav>
      </div>
      <div class="welcome">
        <h1 class="main_name">Sam Johnston</h1>
        <h2 class="fullstack">Fullstack Web Developer</h2>
      </div>
      <div class="arrow bounce"></div>
    </div>
    <div id="div-portfolio"></div>
    <div class="portfolio">
      <h1 class="portfolio_head">HAVE A LOOK AT SOME OF MY RECENT WORK</h1>
      <div class="ports">
        <div class="project">
          <div class="port_info">
            <carousel class="carousel" :paginationEnabled="false" :autoplay="true" :autoplayTimeout="3000" :per-page="1" :loop="true" :navigationEnabled="true" minSwipeDistance="8">
              <slide>
                <img class="portfolio_pic" src="../assets/web_snippet.png" alt="eventer">
              </slide>
              <slide>
                <img class="portfolio_pic" src="../assets/eventer_dashboard.png" alt="eventer">
              </slide>
              <slide>
                <img class="portfolio_pic" src="../assets/eventer_login.png" alt="eventer">
              </slide>
            </carousel>
            <div class="portfolio_info">
              <div class="proj_title">
                <h2 class="port_title">Eventer</h2>
                <h3 class="port_sub">Personally developed</h3>
              </div>
              <p class="proj_description">
                Eventer is a social media app built in React that allows users to connect with their friends and plan hangouts.  Each user can view/edit their profile information and friends list.  Upon the creation of an event by a user they are prompted to invite friends and can view the event.  The event viewer page allows them to search nearby food and entertainment, while simultaneously chatting with friends who are part of the event.  
              </p>
              <div>
                <a href="https://eventer.network/#/" class="portfolio_buttons">LIVE SITE</a>
                <a href="https://github.com/samabu/eventer" class="portfolio_buttons">GITHUB REPO</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="ports">
        <div class="project">
          <div class="port_info">
            <carousel class="carousel" :paginationEnabled="false" :autoplay="true" :autoplayTimeout="3000" :per-page="1" :loop="true" :navigationEnabled="true" minSwipeDistance="8">
              <slide>
                <img class="portfolio_pic" src="../assets/Tool_Share_Home.png" alt="tool_share">
              </slide>
              <slide>
                <img class="portfolio_pic" src="../assets/Tool_Share_Post.png" alt="tool_share">
              </slide>
              <slide>
                <img class="portfolio_pic" src="../assets/Tool_Share_FAQ.png" alt="tool_share">
              </slide>
              <slide>
                <img class="portfolio_pic" src="../assets/Tool_Share_Messages.png" alt="tool_share">
              </slide>
            </carousel>
            <div class="portfolio_info">
              <div class="proj_title">
                <h2 class="port_title">Tool Share</h2>
                <h3 class="port_sub">Group Project</h3>
              </div>
              <p class="proj_description">
                Tool Share is a mobile app that allows its users to complete their home projects without draining their wallets. Rather than having to buy a brand new saw for one time use for a specific project, you can rent it at a daily rate, saving you considerable money and storage space. If you already have tools that you don't often use, you can list them as available to rent and make money on the side.
              </p>
              <div>
                <a href="https://toolshare.pro/#/" class="portfolio_buttons">LIVE SITE</a>
                <a href="https://github.com/michaeljamie/tool-share" class="portfolio_buttons">GITHUB REPO</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="div-about"></div>
    <div class="about">
      <h1 class="about_head">IN CASE YOU'RE INTERESTED</h1>
      <div class="about_professional">
        <p class="personal_info">
          I still remember the first day I discovered coding.  I spent a full day on it at school.  When I got home, all I wanted to do was keep
          going.  My mind has always been powered by a logical thinking brain, and I love being able to create something from nothing, so a career in web development
          perfectly suits me.  Since then, I have taken multiple computer science classes in college and attended DevMountain where I specialized in fullstack web 
          development.  I currently work for the Brigham Young University Athletic Department as a web developer.
        </p>
      </div>
      <div class="about_for_fun">
        <p class="personal_info">
          When I'm not coding I enjoy doing all kinds of outdoor activities.  I grew up in Utah and have hiked just about every nearby mountain you can name.
          I also enjoy climbing, mountain biking, kayaking, backpacking, camping, and longboarding.  In college I majored in Economics with an emphasis in data 
          analytics.  
        </p>
      </div>
    </div>
    <div id="div-skills"></div>
    <div class="skills">
      <h1 class="skills_head">SKILLS</h1>
      <h2 class="skills_quote">“Knowledge is a weapon. I intend to be formidably armed.”<br/>
      ― Terry Goodkind</h2>
      <div class="skills_div">
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/js_icon.png" alt="javascript">
          <h3>JAVASCRIPT</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/react_icon.png" alt="react">
          <h3>REACT</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/nodejs_icon.png" alt="node">
          <h3>NODE.JS</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/postgresql.png" alt="postgres">
          <h3>POSTGRESQL</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/expressjs_icon.png" alt="express">
          <h3>EXPRESS.JS</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/python_icon.png" alt="python">
          <h3>PYTHON</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/c-plus-plus-logo.png" alt="c++">
          <h3>C++</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/html_icon.png" alt="html">
          <h3>HTML 5</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/css_icon.png" alt="css">
          <h3>CSS 3</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/git_icon.png" alt="git">
          <h3>GIT</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/sass.png" alt="sass">
          <h3>SASS</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/vue.png" alt="vue">
          <h3>VUE</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/massive.png" alt="massive">
          <h3>MASSIVE</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/socket.png" alt="socket">
          <h3>SOCKET.IO</h3>
        </div>
        <div class="individual_skills">
          <img class="skill_icons" src="../assets/redux.png" alt="redux">
          <h3>REDUX</h3>
        </div>
      </div>
    </div>
    <div id="div-contact"></div>
    <div class="contact">
      <h1 class="contact_head"></h1>
      <div class="my_info">
        <div class="name">Sam Johnston</div>
        <div class="title">Fullstack Web Developer</div>
        <div class="phone">(801) 800 - 2110</div>
        <div class="email">samuelalbertjohnston@gmail.com</div>
        <img class="picture" src="../assets/download.png" alt="me!">
        <div>Please feel free to reach out to me regarding future projects!</div>
        <div>I would love to discuss how I can help you meet your goals.</div>
      </div>
      <div class="contact_inputs">

      </div>
    </div>
    <footer>
      <div>This website was created using Vue</div>
      <div>© Samuel Johnston</div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      showNav: false,
    }
  },
  methods: {
    toggleNav() {
      this.showNav = !this.showNav
    }
  },
  mounted() {
    let scrollpos = window.scrollY
    const header = document.querySelector("nav")
    const header_height = header.offsetHeight


    const add_class_on_scroll = () => header.classList.add("fade-in")
    const remove_class_on_scroll = () => header.classList.remove("fade-in")


    window.addEventListener('scroll', function() { 
      scrollpos = window.scrollY;

      if (scrollpos >= header_height) { add_class_on_scroll() }
      else { remove_class_on_scroll() }

      console.log(scrollpos);
    })
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans');

@mixin flex($justify-content, $align-items, $flex-direction: row) {
  display: flex;
  justify-content: $justify-content;
  align-items: $align-items;
  flex-direction: $flex-direction
}
.home {
  height: 100vh;
  width: 100%;
  font-family: 'Open Sans', sans-serif;
}

.home_background {
  height: 100%;
  width: 100%;
  background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url('../assets/background.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  background-attachment: fixed;
  @include flex(space-between, center, column);
}

nav {
  height: 10%;
  width: 100%;
  @include flex(space-around, center);
  color: whitesmoke;
  font-size: 28px;
  --ease: all 300ms ease;
  position: fixed;
  transition: var(--ease);
}

nav.fade-in { 
  background: linear-gradient( rgba(10, 10, 10, 0.7), rgba(0, 0, 0, 0.8) ); 
  z-index: 500;
}

.home_nav {
  width: 100%;
}

.nav_elements {
  transition: transform 250ms ease-in-out;
  text-decoration: none;
  color: whitesmoke;
}

.nav_elements:hover {
  transform: scale(1.2);
  transition: transform 250ms ease-in-out;
}

.welcome {
  height: 30%;
  width: 100%;
  background-color: rgba(95, 95, 95, 0.5);
  @include flex(center, center, column);
  color: whitesmoke;
}

.main_name {
  font-size: 40px;
  margin: 1%;
}

.fullstack {
  font-size: 32px;
  margin: 1%;
}

.arrow {
  margin-bottom: 4%;
  width: 60px;
  height: 60px;
  background-image: url('https://simpkinsand.co.uk/wp-content/uploads/2016/08/white-down-arrow-png.png');
  background-size: contain;
}

.bounce {
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}

.portfolio {
  min-height: 100vh;
  width: 100%;
  height: auto;
  background-color: #292929;
  @include flex(center, center, column);
  flex-wrap: wrap;
} 

.portfolio_head {
  width: 95vw;
  height: 10vh;
  text-align: center;
  color: whitesmoke;
  margin: 25px;
}

.ports {
  height: 65vh;
  width: 100%;
  background-color: rgba(79, 79, 79, 0.5);
  margin: 25px;
  @include flex(center, center, column);
  color: whitesmoke;
  font-size: 48px; 
}

.project {
  width: 100%;
  @include flex(center, center, column);
}

.port_info {
  width: 55vh;
  width: 95%;
  @include flex(flex-start, center);
  z-index: 10;
}

.portfolio_info {
  width: 100%;
  height: 55vh;
  font-size: 22px;
  @include flex(space-around, center, column);
}

.proj_title {
  width: 100%;
  height: 100%;
  @include flex(flex-start, center, column);
}

.portfolio_pic {
  height: 45vh;
  width: 45vw;
  z-index: 900;
}

.carousel {
  height: 45vh;
  width: 45vw;
  margin: 25px;
  z-index: 900;
}

.proj_description {
  text-align: justify;
  padding: 4vh;
}

.portfolio_buttons {
  text-decoration: none;
  font-size: 26px;
  color: whitesmoke;
  background-color: #65BE86;
  width: 10vw;
  height: 5vh;
  border: none;
  margin: 15px;
  border-radius: 10px;
  padding: 10px;
}

.about {
  min-height: 100vh;
  width: 100%;
  height: auto;
  background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url('../assets/hiker.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  background-attachment: fixed;
  @include flex(space-around, center, column);
}

.about_head {
  width: 95vw;
  height: 5vh;
  text-align: center;
  color: whitesmoke;
  margin-top: 25px;
}

.about_professional {
  height: 35vh;
  width: 55vw;
  margin-left: 25px;
  background-color: rgba(79, 79, 79, 0.7);
  color: whitesmoke;
  align-self: flex-start;
  @include flex(center, center);
  flex-wrap: wrap;
}

.about_for_fun {
  height: 27.5vh;
  width: 55vw;
  margin-right: 25px;
  background-color: rgba(79, 79, 79, 0.7);
  color: whitesmoke;
  align-self: flex-end;
  @include flex(center, center);
  flex-wrap: wrap;
}

.personal_info {
  padding: 35px;
  font-size: 18px;
  text-align: justify;
}

.skills {
  min-height: 75vh;
  width: 100%;
  height: auto;
  background-color: #3C3C3C;
  @include flex(center, center);
  flex-wrap: wrap;
}

.skills_head {
  width: 95%;
  height: 5vh;
  text-align: center;
  color: whitesmoke;
  margin-top: 25px;
}

.skills_quote {
  width: 95%;
  color: white;
  text-align: center;
  margin: 5vh;
}

.skills_div {
  width: 65%;
  @include flex(center, center);
  flex-wrap: wrap;
}

.individual_skills {
  height: 16vh;
  width: 10vw;
  margin: 2vh;
  color: whitesmoke;
  @include flex(center, center, column);
}

.skill_icons {
  height: 13vh;
  width: 8vw;
}

.contact {
  height: 100vh;
  width: 100%;
  background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url('../assets/contact.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  background-attachment: fixed; 
  @include flex(space-between, center, column);
  color: whitesmoke;
}

.contact_head {
  margin-top: 25px;
}

.my_info {
  height: 80vh;
  width: 50%;
  background-color: rgba(79, 79, 79, 0.7);
  @include flex(space-around, center, column);
  font-size: 24px;
}

.picture {
  height: 250px;
  width: 250px;
  border-radius: 125px;
}

footer {
  height: 15vh;
  width: 100%;
  @include flex(space-around, center, column);
  background-color: #292929;
  color: white;
  font-size: 24px;
}


@media (max-width: 500px) {

  body {
    width: 100%;
    padding: 0;
    margin: 0;
    border: none;
    overflow-x: hidden;
  }

  .home {
    width: 100%;
  }

  .home_background {
    background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url('../assets/background.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: none;
    background-repeat: no-repeat;
    background-attachment: fixed;
    @include flex(space-between, center, column);
  }

  .home_nav {
    width: 100%;
  }

  nav {
    width: 100vw;
    overflow-x: hidden;
  }

  .nav_elements:hover {
    transform: scale(1)
  }

  .nav_elements {
    font-size: 16px;
    margin: 0;
    padding: 0;
  }

  .fullstack {
    font-size: 28px;
  }
  
  .ports {
    width: 100%;
    margin-left: 0;
    margin-right: 0;
  }

  .port_info {
    display: flex;
    flex-direction: column;
  }

  .portfolio_pic {
    width: 80vw;
    height: 35vh;
  }
  
  .carousel {
    width: 80vw;
    height: 35vh;
    margin: 0;
  }

  .ports {
    height: 110vh;
  }

  .portfolio_head {
    font-size: 28px;
    margin-left: 0;
    margin-right: 0;
  }

  .proj_title {
    margin-bottom: 10vh;
  }

  .portfolio_pic {
    width: 100%;
    height: 30vh;
  }

  .portfolio_info {
    width: 100%;
    font-size: 16px;
  }

  .portfolio_buttons {
    font-size: 18px;
  }

  .about {
    @include flex(space-around, center, column);
  }

  .about_head {
    height: 15vh;
  }

  .about_professional {
    height: auto;
    width: 90%;
    font-size: 12px;
    margin: 0;
    align-self: center;
  }

  .about_for_fun {
    height: auto;
    width: 90%;
    font-size: 12px;
    margin: 0;
    align-self: center;
  }

  .personal_info {
    font-size: 14px;
    padding: 20px;
  }

  .skills_div {
    width: 100%;
  }

  .individual_skills {
    height: 10vh;
    width: 15vw;
    margin: 1vh;
    padding: 2vh 3vh;
    font-size: 12px;
  }

  .skill_icons {
    height: 7.5vh;
    width: 15vw;
  }

  .skills_quote {
    font-size: 18px;
  }

  .my_info {
    width: 80%;
    font-size: 16px;
    text-align: center;
  }

  .name {
    font-size: 26px;
  }

  .title {
    font-size: 24px;
  }

  .phone {
    font-size: 22px;
  }

  .email {
    font-size: 18px;
  }

  footer {
    font-size: 20px;
  }
}
</style>
