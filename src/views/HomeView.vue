<template>
  <div class="home">
    <!-- dots -->
    <nav>
      <div class="dots-wrapper">
        <div class="dot red"></div>
        <div class="dot yellow"></div>
        <div class="dot green"></div>

        <div class="title">my_portfolio</div>
      </div>

      <!-- files tabs -->
      <section class="tab-wrapper">
        <div class="file-tab active">
          <a href="/">Home</a>
          <span class="material-symbols-outlined"> close </span>
        </div>
        <div class="file-tab">
          <a href="#about">About</a>
          <span class="material-symbols-outlined"> close </span>
        </div>
        <div class="file-tab">
          <a href="#projects">Projects</a>
          <span class="material-symbols-outlined"> close </span>
        </div>
        <div class="file-tab">
          <a href="#contact">Contact</a>
          <span class="material-symbols-outlined"> close </span>
        </div>
      </section>
    </nav>

    <main>
      <div class="container">
        <!-- intro -->
        <div class="sections" id="intro">
          <div class="row">
            <div class="flex-center col-md-12 col-lg-6">
              <div class="code-wrapper">
                <p class="h1 mb-4">
                  <span class="num">1</span> Hi! I'm
                  <span class="name">Mark</span>
                  <span class="cursor">_</span>
                </p>
                <p class="h4">
                  <span class="num">2</span> I am a
                  <code class="purple">front-end</code> web developer.
                </p>
                <p class="h4">
                  <span class="num">3</span> I use
                  <span class="yellow">{{ stack }}</span>
                  to transform
                </p>
                <p class="h4">
                  <span class="num">4</span> designs into working code.
                </p>
              </div>
            </div>
            <div class="col-md-12 col-lg-6">
              <h1 class="header code">
                coding is
                <span
                  >{{ poetry
                  }}<span :class="blink ? 'opaque' : ''" class="white"
                    >|</span
                  ></span
                >
              </h1>
            </div>
          </div>
        </div>

        <!-- about -->
        <div class="sections" id="about">
          <div class="wrapper">
            <h2 class="section-title">about</h2>
            <div class="code-wrapper">
              <p class="h3 mb-4 green">
                <span class="num">5</span>
                Summary
              </p>
              <p class="mb-2">
                <span class="num">6</span>
                As a master of the arcane arts of HTML, CSS, and JavaScript,
              </p>
              <p class="mb-2">
                <span class="num">7</span> I conjure the mystical elements that
                bring websites to life. Through my spellbinding skills,
              </p>
              <p class="mb-2">
                <span class="num">7</span>
                I transmute mere designs into interactive and captivating
                experiences for all who traverse the digital realm ✨.
              </p>
            </div>

            <div class="code-wrapper mt-5">
              <p class="h3 mb-4 green">
                <span class="num">8</span>
                Education
              </p>
              <p class="mb-2 blue">
                <span class="num">9</span>
                Bachelor of Science in Information Technology
              </p>
              <p class="mb-2 yellow">
                <span class="num">10</span> Eastern Samar State University |
                2018
              </p>
              <p class="mb-2">
                <span class="num">11</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Cum laude
              </p>
              <p class="mb-2">
                <span class="num">12</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Outstanding Campus Press Leader
              </p>
            </div>

            <div class="code-wrapper mt-5">
              <p class="h3 mb-4 green">
                <span class="num">13</span>
                Work history
              </p>
              <p class="mb-2 blue">
                <span class="num">14</span>
                Front-end Web Developer
              </p>
              <p class="mb-2 yellow">
                <span class="num">15</span>
                PwC Philippines
              </p>
              <p class="mb-2">
                <span class="num">16</span>
                <i>Nov 2021 - Present</i>
              </p>
              <p class="mb-2">
                <span class="num">17</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Be involved in the project development from planning,
                development and release.
              </p>
              <p class="mb-2">
                <span class="num">18</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Convert mockups into working code using HTML, CSS, JavaScript,
                Bootstrap and Vue 3.
              </p>
              <p class="mb-2">
                <span class="num">19</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Make sure web pages meet the project requirements, and look good
                on all screens from desktop to mobile.
              </p>
              <p class="mb-2">
                <span class="num">19</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Work on API integrations with backend developer.
              </p>
              <p class="mb-2">
                <span class="num">19</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Determine coding requirements based on project specifications.
              </p>
              <p class="h5 mt-3 mb-2">
                <span class="num">20</span>
                <span class="wrapper"
                  ><span class="badge rounded-pill bg-primary">HTML5</span
                  ><span class="badge rounded-pill bg-secondary">CSS3</span
                  ><span class="badge rounded-pill bg-success">JavaScript</span
                  ><span class="badge rounded-pill bg-danger">Vue JS</span
                  ><span class="badge rounded-pill bg-warning text-dark"
                    >Github</span
                  ><span class="badge rounded-pill bg-info text-dark"
                    >Firebase</span
                  ><span class="badge rounded-pill bg-light text-dark"
                    >Node</span
                  ><span class="badge rounded-pill bg-dark">Figma</span
                  ><span class="badge rounded-pill bg-primary"
                    >API integrations</span
                  ></span
                >
              </p>

              <p class="h5 mt-5 mb-2 blue">
                <span class="num">21</span>
                Front-end Web Developer
              </p>
              <p class="mb-2 yellow">
                <span class="num">22</span>
                Goldridge Web Design Studio
              </p>
              <p class="mb-2">
                <span class="num">23</span>
                <i>Feb 2019 - Aug 2020</i>
              </p>
              <p class="mb-2">
                <span class="num">24</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Determine task requirements and specifications.
              </p>
              <p class="mb-2">
                <span class="num">25</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Create/modify webpages using HTML, CSS, JavaScript, Materialize
                CSS and JQuery.
              </p>
              <p class="mb-2">
                <span class="num">26</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Make sure outputs look good on all screen sizes- from desktop to
                mobile.
              </p>
              <p class="mb-2">
                <span class="num">26</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Add functionalities to webpages using JavaScript.
              </p>
              <p class="mb-2">
                <span class="num">26</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                Integrate API connections to the front-end.
              </p>
              <p class="h5 mt-3 mb-2">
                <span class="num">25</span>
                <span class="wrapper"
                  ><span class="badge rounded-pill bg-primary">HTML5</span
                  ><span class="badge rounded-pill bg-secondary">CSS3</span
                  ><span class="badge rounded-pill bg-success">JavaScript</span
                  ><span class="badge rounded-pill bg-danger">WordPress</span
                  ><span class="badge rounded-pill bg-warning text-dark"
                    >Bootstrap</span
                  ></span
                >
              </p>
            </div>

            <div class="code-wrapper mt-5">
              <p class="h3 mb-4 green"><span class="num">26</span> Skills</p>
              <p class="mb-2">
                <span class="num">27</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <span class="content ms-3"
                  >HTML5, CSS3, JavaScript,
                  <span class="green">Vue JS</span></span
                >
              </p>
              <p class="mb-2">
                <span class="num">28</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <span class="content ms-3"
                  ><span class="blue">Bootstrap</span>, Materialize CSS</span
                >
              </p>
              <p class="mb-2">
                <span class="num">29</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <span class="content ms-3"
                  >Node, Firebase,
                  <span class="yellow">API integrations</span></span
                >
              </p>
              <p class="mb-2">
                <span class="num">30</span>
                <span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <span class="content pink ms-3">Figma</span>
              </p>
            </div>
          </div>
        </div>

        <!-- about -->
        <div class="sections" id="projects">
          <div class="wrapper">
            <h2 class="section-title">projects</h2>
            <div class="code-wrapper">
              <p class="h3 mb-4"><span class="num">28</span> Web/ Work</p>
              <div class="row mb-5">
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      href="https://main--engagement-tool.netlify.app/"
                      target="_blank"
                      ><div class="img-holder elt"></div
                    ></a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Engagement Approval Tool</b>
                      </p>
                      <p class="project-body">
                        A web app that digitises engagement approval processes.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-primary">HTML5</span
                        ><span class="badge rounded-pill bg-secondary"
                          >CSS3</span
                        ><span class="badge rounded-pill bg-success"
                          >JavaScript</span
                        ><span class="badge rounded-pill bg-danger"
                          >WordPress</span
                        ><span class="badge rounded-pill bg-warning text-dark"
                          >Bootstrap</span
                        ></span
                      >
                    </div>
                  </div>
                </div>
                <!-- <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <img
                      src="https://placehold.co/200"
                      class="card-img-top"
                      alt="..."
                    />
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Overtime Approval Tool</b>
                      </p>
                      <p class="project-body">
                        A tool for review and approval of employee overtime.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-primary">HTML5</span
                        ><span class="badge rounded-pill bg-secondary"
                          >CSS3</span
                        ><span class="badge rounded-pill bg-success"
                          >JavaScript</span
                        ><span class="badge rounded-pill bg-danger"
                          >WordPress</span
                        ><span class="badge rounded-pill bg-warning text-dark"
                          >Bootstrap</span
                        ></span
                      >
                    </div>
                  </div>
                </div> -->
              </div>
            </div>
            <div class="code-wrapper">
              <p class="h3 mb-4"><span class="num">29</span> Web/ Personal</p>
              <div class="row mb-5">
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      href="https://udemy-vue-firebase-sites-9b7b7.web.app/"
                      target="_blank"
                    >
                      <div class="img-holder chat"></div>
                    </a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Live Chat</b>
                      </p>
                      <p class="project-body">A simple live chat app.</p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-primary"
                          >HTML5/CSS3</span
                        ><span class="badge rounded-pill bg-success"
                          >Vue JS</span
                        ><span class="badge rounded-pill bg-danger"
                          >Firebase</span
                        ></span
                      >
                    </div>
                  </div>
                </div>
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      href="http://demo.imanila.ph/transway/"
                      target="_blank"
                      ><div class="img-holder transway"></div
                    ></a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Transway</b>
                      </p>
                      <p class="project-body">
                        A trucking and delivery services app.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-primary">HTML5</span
                        ><span class="badge rounded-pill bg-warning">CSS3</span
                        ><span class="badge rounded-pill bg-danger"
                          >WordPress</span
                        ></span
                      >
                    </div>
                  </div>
                </div>
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      href="http://demo.imanila.ph/homemade/"
                      target="_blank"
                    >
                      <div class="img-holder homemade"></div>
                    </a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Homemade</b>
                      </p>
                      <p class="project-body">
                        Find home for minimalist living.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-primary">HTML5</span
                        ><span class="badge rounded-pill bg-secondary"
                          >CSS3</span
                        ><span class="badge rounded-pill bg-danger"
                          >WordPress</span
                        ></span
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="code-wrapper">
              <p class="h3 mb-4"><span class="num">30</span> Figma/ Personal</p>
              <div class="row mb-5">
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      target="_blank"
                      href="https://www.figma.com/proto/LEjundVU2p2j0MbNvIzDmI/Bubbli---Hi-Fi-Prototype?page-id=0%3A1&type=design&node-id=1-2&viewport=396%2C143%2C0.2&t=1hkyC2qptZMb0uep-1&scaling=scale-down&starting-point-node-id=1%3A2&mode=design"
                    >
                      <div class="img-holder bubbli"></div>
                    </a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Bubbli - Laundry Booking</b>
                      </p>
                      <p class="project-body">
                        A luandry booking and delivery app.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-success"
                          >Figma</span
                        >
                      </span>
                    </div>
                  </div>
                </div>
                <div class="col-lg-3 col-md-6">
                  <div class="card">
                    <a
                      class="img-link"
                      target="_blank"
                      href="https://www.figma.com/proto/8pslR3cSRmlt3xnAjM93ot/Vocal-Notes?page-id=0%3A1&type=design&node-id=1-2&viewport=400%2C315%2C0.79&t=O402XUyO8c5vmCGg-1&scaling=scale-down&starting-point-node-id=1%3A2&mode=design"
                    >
                      <div class="img-holder vocal"></div>
                    </a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Vocal Notes</b>
                      </p>
                      <p class="project-body">
                        A watch app with live transcription.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-warning"
                          >Figma
                        </span>
                      </span>
                    </div>
                  </div>
                </div>
                <!-- <div class="col-lg-3 col-md-4 hidden">
                  <div class="card">
                    <a class="img-link" target="_blank" href="">
                      <div class="img-holder daily"></div>
                    </a>
                    <div class="hidden card-body">
                      <p class="card-text">
                        <b class="project-title">Daily Diary</b>
                      </p>
                      <p class="project-body">
                        Diary to track the beautiful things in life.
                      </p>
                      <span class="wrapper"
                        ><span class="badge rounded-pill bg-danger"
                          >Figma</span
                        ></span
                      >
                    </div>
                  </div>
                </div> -->
              </div>
            </div>
          </div>
        </div>

        <!-- about -->
        <div class="sections" id="contact">
          <div class="wrapper">
            <h2 class="section-title">contact</h2>
            <div class="code-wrapper">
              <p class="h5 mt-5 mb-2">
                <span class="num">31</span>Phone:
                <a class="a-link" href="tel:+639121930687">09121930687</a>
              </p>
              <p class="h5 mb-3">
                <span class="num">32</span>Email:
                <a
                  target="_blank"
                  href="mailto:markbalazo14@gmail.com"
                  class="a-link"
                  >markbalazo14@gmail.com</a
                >
              </p>
              <p class="h5 mb-3">
                <span class="num">33</span>CV Link:
                <a
                  target="_blank"
                  href="https://drive.google.com/file/d/18Ii5HNJ5Guk2GzL-bcXeGb5WAqe9fSII/view?usp=drivesdk"
                  class="a-link"
                  >here</a
                >
              </p>
              <p class="h5 mb-3"><span class="num">34</span>Socials:</p>
              <p class="mb-2">
                <span class="num">35</span
                ><span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <a
                  target="_blank"
                  href="https://www.linkedin.com/in/mark-balazo"
                  class="ms-3 a-link"
                  >LinkedIn</a
                >
              </p>
              <p class="mb-2">
                <span class="num">36</span
                ><span class="material-symbols-outlined">
                  radio_button_unchecked
                </span>
                <a
                  target="_blank"
                  href="https://github.com/markkirivera"
                  class="ms-3 a-link"
                  >Github</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import { onMounted, ref } from "vue";
export default {
  name: "HomeView",
  components: {},
  setup() {
    //   refs
    const blink = ref(true);
    const stack = ref("magic");
    const poetry = ref("poetry✨");

    let adj = [
      "an art 🎨",
      "challenging💪",
      "life🧑‍💻",
      "magic🪄",
      "poetry✨",
      "logic🤔",
      "creative🖌️",
      "systematic⚙️",
      "intricate🔍",
      "structured🧬",
    ];

    let arr = [
      "Vue JS",
      "HTML5",
      "CSS",
      "JavaScript",
      "Bootstrap",
      "Bulma",
      "WordPress",
      "Github",
      "APIs",
      "NodeJS",
    ];

    // functions
    const count = () => {
      // generate random number
      let x = Math.floor(Math.random() * arr.length + 1);
      stack.value = arr[x - 1];

      setTimeout(() => {
        poetry.value = adj[x - 1];
      }, 1000);
    };

    const blinkItem = () => {
      blink.value = !blink.value;
    };

    onMounted(() => {
      setInterval(count, 5000);
      setInterval(blinkItem, 600);
    });

    return { stack, poetry, arr, blink };
  },
};
</script>
