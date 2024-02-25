### Hi there 👋
<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        :root {
    --Text: #E6E9F4;
    --Background: #090A0E;
    --Brand-Primary: #1E38E2;
    --Brand-Seconday: #283772;
    --Brand-Accent: #495BCF;

    --neutral-02: #E8E8E8;
    --neutral-01: #FAFAFA;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    width: 100vw;
    /* sets the default rem value to 10px from 16px */
    font-size: 10px;
    overflow-x: hidden;
}

body {
    background-color: var(--Background);

    color: var(--Text);
    font-family: "Montserrat", sans-serif;
    font-size: 1.6rem;
    font-style: normal;
    font-weight: 500;
    line-height: 2.4rem;
    letter-spacing: 0.4rem;
}

main {
    display: none;
}

.back_ellipse {
    width: 28.7rem;
    height: 28.7rem;
    border-radius: 28.7rem;
    background: var(--Brand-Accent);
    box-shadow: 0px 4px 4px 200px rgba(0, 0, 0, 0.25);
    filter: blur(113.5px);
    z-index: -1;
    position: absolute;

}

#contact-cont {
    display: flex;
    width: 100vw;
    justify-content: end;

    margin-top: 7.5rem;
}

.btn_primary_default {
    margin-right: 13rem;

    color: inherit;
    font-weight: 700;
    letter-spacing: 0.3rem;
    text-transform: uppercase;

    display: inline-flex;
    padding: 1.4rem 1.8rem;
    justify-content: center;
    align-items: center;
    gap: 0.8rem;
    border-radius: 1.2rem;
    border: 2px solid var(--Brand-Accent);
    background: var(--Brand-Primary);
    box-shadow: 4px 6px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25) inset;
}

.btn_primary_default:hover {
    cursor: pointer;
    border: 2px solid rgba(73, 91, 207, 0.25);
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25) inset, 4px 6px 4px 0px rgba(0, 0, 0, 0.25);
}

.btn_primary_default:focus {
    border: 2px solid rgba(73, 91, 207, 0.25);
}


.rpart,
.lpart {
    z-index: 1;
}

.window,
.mwing {
    z-index: 2;
}

.fire {
    z-index: -1;
}

.rocket {
    width: 100px;
    height: 100px;

    animation: rocket_fly_by 2000ms ease-in-out 70ms;

    top: -64vh;
    left: 100vw;
    opacity: 1;
}

.rocket,
.lwing,
.lpart,
.mwing,
.window,
.rwing,
.rpart,
.burner,
.fire {
    position: absolute;
}


.window {
    top: 18px;
    left: 196px;
}

.rpart {
    top: 9px;
    left: 29px;
}

.mwing {
    top: 96px;
    left: 26px;
}

.rwing {
    top: 120px;
    left: 160px;
}

.lwing {}

.burner {
    top: 172px;
    left: -10px;
}

.fire {
    top: 192px;
    left: -86px;
}


@keyframes rocket_fly_by {
    0% {
        top: 94vh;
        left: -20vw;
    }

    100% {
        top: -64vh;
        left: 100vw;
        opacity: 0;
    }
}

main {
    animation: fadeIn 2s;
    gap: 6rem;
}

@keyframes fadeIn {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

.intro {
    display: flex;
    flex-direction: column;
    gap: 4rem;
}

.heading {
    margin-left: -10rem;
    display: inline-flex;
    gap: 11.6rem;
}

.profile_pic {
    width: 17rem;
    height: 17rem;
    border-radius: 17.2rem;
}

.salutation {
    display: flex;
    width: 27.6rem;
    flex-direction: column;
    align-items: flex-start;
    gap: -0.6rem;
}

.salutation>h1 {
    width: 26.9rem;

    font-size: 6.4rem;
    font-weight: 600;
    line-height: 7.8rem;
    letter-spacing: 0.25rem;
}

.name {
    color: var(--Brand-Primary);
    font-style: italic;
    font-weight: 800;
    letter-spacing: 0.9rem;
}

.salutation>p {
    color: var(--Text);
    font-size: 2rem;
    font-weight: 900;
    line-height: 2.5rem;
    letter-spacing: 0.6rem;
}

.brief_intro {
    width: 78rem;
    flex-shrink: 0;
}

.main-content {
    width: 100vw;

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

    gap: 10rem;
}

h3 {
    color: var(--Brand-Accent);
    font-size: 2.4rem;
    font-style: normal;
    font-weight: 700;
    line-height: 2.9rem;
    letter-spacing: 0.6rem;
}

#lang-and-tools {
    display: flex;
    width: 78rem;
    flex-direction: column;
    align-items: flex-start;
    gap: 3rem;
}

.lang_icons {
    overflow: hidden;
    width: 78rem;
    height: 7rem;
    padding: 0.5rem 0rem;

    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: flex-start;
    gap: 2.4rem;
}

.lang_icons>img {
    animation: slide 10000ms 1ms infinite alternate-reverse;
}

@keyframes slide {
    0% {
        transform: translateX(50rem);
    }

    50% {
        transform: translateX(0rem);
    }

    100% {
        transform: translateX(100rem);
    }
}

#about_me {
    width: 78rem;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 3rem;
    flex-shrink: 0;
}

#connect_with_me {
    display: flex;
    width: 78rem;
    flex-direction: column;
    align-items: center;
    gap: 3rem;
}

.social_icons {
    display: flex;
    width: 78rem;
    height: 7rem;
    justify-content: center;
    align-items: center;
    gap: 2rem;
}

.end_graphic {
    width: 79rem;
    display: inline-flex;
    padding-bottom: 8rem;
    align-items: center;
    gap: 5.5rem;
}
      </style>

      <div class="container">
        <main>
      <!-- background ellipses -->
      <div class="back_ellipse"></div>
      <div class="back_ellipse"></div>
      <!-- contact btn -->
      <div id="contact-cont">
        <button type="button" class="btn_primary_default">Contact me!</button>
      </div>
      <!-- main-content -->
      <div class="main-content">
        <div class="intro">
          <!-- salutation -->
          <div class="heading">
            <img
              class="profile_pic"
              src="public/images/Profile picture.svg"
              alt=""
              srcset=""
            />
            <div class="salutation">
              <h1>Hi! i am</h1>
              <h1 class="name">Vinner</h1>
              <p>a web developer</p>
            </div>
          </div>
          <p class="brief_intro">
            If you are looking for a web developer who can create a website that
            is both beautiful and functional, I encourage you to contact me. I
            am passionate about creating websites that are both beautiful and
            functional. I work closely with my clients to understand their needs
            and goals.
          </p>
        </div>

        <div id="lang-and-tools">
          <h3>Languages and tools i Know:</h3>
          <div class="lang_icons">
            <img src="public/icons/c++.png" alt="" srcset="" />
            <img src="public/icons/css.png" alt="" srcset="" />
            <img src="public/icons/ejs.png" alt="" srcset="" />
            <img src="public/icons/github.png" alt="" srcset="" />
            <img src="public/icons/html.png" alt="" srcset="" />
            <img src="public/icons/js.png" alt="" srcset="" />
            <img src="public/icons/nodejs.png" alt="" srcset="" />
            <img src="public/icons/python.png" alt="" srcset="" />
            <img src="public/icons/react-native.png" alt="" srcset="" />
            <img src="public/icons/sass.png" alt="" srcset="" />
            <!-- repeating for continuous flow  -->
            <img src="public/icons/c++.png" alt="" srcset="" />
            <img src="public/icons/css.png" alt="" srcset="" />
            <img src="public/icons/ejs.png" alt="" srcset="" />
            <img src="public/icons/github.png" alt="" srcset="" />
            <img src="public/icons/html.png" alt="" srcset="" />
            <img src="public/icons/js.png" alt="" srcset="" />
            <img src="public/icons/nodejs.png" alt="" srcset="" />
            <img src="public/icons/python.png" alt="" srcset="" />
            <img src="public/icons/react-native.png" alt="" srcset="" />
            <img src="public/icons/sass.png" alt="" srcset="" />
          </div>
        </div>
        <div id="about_me">
          <h3>About Me:</h3>
          <p>
            I am currently pursuing Computer Applications from Chandigarh
            University I have a keen interest in WEB3 and WEB applications and
            just how the web works in general. I have designed and developed a
            few projects for clients that included developing a e-commerce
            application in React .
          </p>
        </div>
        <div id="connect_with_me">
          <h3>Connect with me:</h3>
          <div class="social_icons">
            <img src="public/icons/github.png" alt="" srcset="" />
            <img src="public/icons/instagram.png" alt="" srcset="" />
            <img src="public/icons/linkedin.png" alt="" srcset="" />
          </div>
        </div>
        <div class="end_graphic">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="316"
            height="27"
            viewBox="0 0 316 27"
            fill="none"
          >
            <path
              d="M1 11.3945C161.245 -19.3301 153.757 49.5507 315 11.3945"
              stroke="#D6D6D6"
              stroke-width="6"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="42"
            height="40"
            viewBox="0 0 42 40"
            fill="none"
          >
            <path
              d="M2.80523 15.8386L16.9639 2.40603C18.4164 1.02805 20.6639 0.936187 22.224 2.19103L38.9483 15.6432C40.8304 17.1571 40.9516 19.981 39.2062 21.6506L22.5024 37.6281C20.863 39.1963 18.2489 39.0885 16.7441 37.3908L2.56488 21.3937C1.13451 19.78 1.24082 17.3228 2.80523 15.8386Z"
              fill="#E8E8E8"
              stroke="black"
              stroke-width="2"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="317"
            height="27"
            viewBox="0 0 317 27"
            fill="none"
          >
            <path
              d="M1.5 11.3945C161.745 -19.3301 154.257 49.5507 315.5 11.3945"
              stroke="#D6D6D6"
              stroke-width="6"
            />
          </svg>
        </div>
      </div>
    </main>

    <div class="rocket">
      <svg
        class="lwing"
        xmlns="http://www.w3.org/2000/svg"
        width="175"
        height="96"
        viewBox="0 0 175 96"
        fill="none"
      >
        <path
          d="M121.357 0.063174L174.463 28.0222L81.6991 95.2489L0.57292 66.9749L121.357 0.063174Z"
          fill="#FB5A21"
        />
      </svg>
      <svg
        class="lpart"
        xmlns="http://www.w3.org/2000/svg"
        width="308"
        height="211"
        viewBox="0 0 308 211"
        fill="none"
      >
        <path
          d="M56.7389 191.177L76.544 176.824L96.3492 162.472L307.604 9.37339C307.604 9.37339 272.164 -11.9241 194.677 12.2833C150.1 26.2095 112.671 44.9968 75.285 67.4101C51.2597 81.8133 28.4395 100.026 4.83646 119.559L15.2169 133.883L2.0135 143.451L14.1807 160.24L0.977298 169.809L30.332 210.315L43.5354 200.746L56.7389 191.177Z"
          fill="#DCDFD9"
        />
      </svg>
      <svg
        class="mwing"
        xmlns="http://www.w3.org/2000/svg"
        width="163"
        height="117"
        viewBox="0 0 163 117"
        fill="none"
      >
        <path
          d="M129.853 1.71156L162.034 0.156042L150.538 30.2543L0.971627 116.879L129.853 1.71156Z"
          fill="#FB5A21"
        />
      </svg>
      <svg
        class="window"
        xmlns="http://www.w3.org/2000/svg"
        width="81"
        height="82"
        viewBox="0 0 81 82"
        fill="none"
      >
        <circle
          cx="40.5902"
          cy="41.028"
          r="35.2857"
          transform="rotate(54.0689 40.5902 41.028)"
          fill="#00D5CC"
          stroke="#5B6575"
          stroke-width="10"
        />
      </svg>
      <svg
        class="rpart"
        xmlns="http://www.w3.org/2000/svg"
        width="279"
        height="256"
        viewBox="0 0 279 256"
        fill="none"
      >
        <path
          d="M26.7388 182.177L46.544 167.824L66.3492 153.471L277.604 0.373376C277.604 0.373376 287.431 41.5387 240.726 108.221C213.858 146.582 184.462 176.455 151.586 205.091C130.459 223.494 106.025 239.48 80.083 255.785L69.4141 241.064L56.2107 250.632L43.7055 233.377L30.502 242.945L0.331957 201.315L13.5354 191.746L26.7388 182.177Z"
          fill="#F9F1F9"
        />
      </svg>
      <svg
        class="rwing"
        xmlns="http://www.w3.org/2000/svg"
        width="107"
        height="160"
        viewBox="0 0 107 160"
        fill="none"
      >
        <path
          d="M106.191 63.916L92.7712 0.0768502L0.00728742 67.3035L6.05412 159.317L106.191 63.916Z"
          fill="#FB5A21"
        />
      </svg>
      <svg
        class="burner"
        xmlns="http://www.w3.org/2000/svg"
        width="70"
        height="82"
        viewBox="0 0 70 82"
        fill="none"
      >
        <path
          d="M20.6919 0.694397L69.4497 67.9737L42.0295 81.6263L0.659221 24.5408L20.6919 0.694397Z"
          fill="#5B6575"
        />
      </svg>
      <svg
        class="fire"
        xmlns="http://www.w3.org/2000/svg"
        width="124"
        height="117"
        viewBox="0 0 124 117"
        fill="none"
      >
        <path
          d="M89.1614 10.8308C97.0105 21.6615 102.444 29.1596 115.727 47.4884C130.346 67.6605 61.2335 94.6047 57.6109 89.6059C53.9883 84.6072 20.8938 88.26 20.8938 88.26C20.8938 88.26 36.4788 60.4464 31.0449 52.9483C25.6109 45.4502 75.5993 -7.88318 89.1614 10.8308Z"
          fill="#E36018"
        />
        <path
          d="M91.4676 14.0131C97.9516 22.9601 102.441 29.1542 113.413 44.2954C125.49 60.9593 72.8186 80.0129 69.826 75.8835C66.8334 71.7541 41.2775 73.4795 41.2775 73.4795C41.2775 73.4795 52.3691 51.7953 47.8802 45.6012C43.3913 39.4071 80.2641 -1.44633 91.4676 14.0131Z"
          fill="#FFAE44"
        />
        <path
          d="M94.9267 18.7862C99.3632 24.9079 102.435 29.146 109.942 39.5058C118.205 50.9074 82.9316 63.3899 80.884 60.5645C78.8365 57.7391 61.6592 58.6962 61.6592 58.6962C61.6592 58.6962 68.9398 44.0831 65.8685 39.845C62.7971 35.6069 87.2612 8.20878 94.9267 18.7862Z"
          fill="#FCE25E"
        />
      </svg>
    </div>

      </div>
    </div>
  </foreignObject>
</svg>









<!--
**Conceal34/Conceal34** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
