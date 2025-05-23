        @keyframes gradient {
          0% {
            background-position: 0% 50%;
          }
          50% {
            background-position: 100% 50%;
          }
          100% {
            background-position: 0% 50%;
          }
        }

        .container {
          background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
          background-size: 400% 400%;
          animation: gradient 15s ease infinite;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .container {
            animation: none;
          }

          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>Hi there, my name is Nikola <div class="hi">👋</div></h1>
      </div>
    </div>


<img src="https://github.com/mishmark-bit/mishmark-bit/blob/main/head.png"/>
<main style="margin: -40px 0;">
  <h1 align="center">Hi there, I'm Mark<h1>
</main>
<img src="https://github.com/mishmark-bit/mishmark-bit/blob/main/footer.png"/>

<h1>Hello world!</h1>

h1 {
  color: red;
  animation: myanimation 2s infinite;
}

@keyframes myanimation {
  from {
    color: red;
  }
  to {
    color: yellow;
  }
}
