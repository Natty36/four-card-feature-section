<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&display=swap"
      rel="stylesheet"
    />
    <link rel="icon" href="./images/favicon-32x32.png" />
  </head>
  <body>
    <div class="con">
      <h1 class="e1">Reliable, efficient delivery</h1>
      <h1 class="e2">Powered by Technology</h1>
      <p class="e3">
        Our Artificial Intelligence powered tools use millions of project data
        points to ensure that your project is successful
      </p>
      <div class="de">
        <div class="d1 d">
          <h1>Supervisor</h1>
          <p>Monitors activity to identify project roadblocks</p>
          <img src="./images/icon-supervisor.svg" alt="supervisor" />
        </div>
        <div class="d9d">
          <div class="d2 d">
            <h1>Team Builder</h1>
            <p>
              Scans our talent network to create the optimal team for your
              project
            </p>
            <img src="./images/icon-team-builder.svg" alt="team builder" />
          </div>
          <div class="d3 d">
            <h1>Karma</h1>
            <p>Regularly evaluates our talent to ensure quality</p>
            <img src="./images/icon-karma.svg" alt="karma" />
          </div>
        </div>
        <div class="d4 d">
          <h1>Calculator</h1>
          <p>
            Uses data from past projects to provide better delivery estimates
          </p>
          <img src="./images/icon-calculator.svg" alt="calculator" />
        </div>
      </div>
    </div>
  </body>
</html>


style >>>

/* ===== RESET ===== */
:root {
  --color-primary: #0080ff;
  --color-primary-dark: #0065cc;
  --color-accent: #fa5757;
  --color-muted: #9194a1;
  --color-dark: #19192e;
  --color-black: #000;
  --color-off-white: #f7f7f7;
  --color-white: #fff;
  --color-border: #e0e0ee;
  --pad: 2rem;
  --radius-sm: 1rem;
  --radius-md: 2rem;
  --radius-lg: 4rem;
  --desktop-width: 900px;
  --transition: 0.25s ease;
}

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Cairo", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
}

a {
  text-decoration: none;
  color: inherit;
  display: inline-block;
}

button {
  background: transparent;
  border: none;
  cursor: pointer;
}

ul,
ol {
  list-style: none;
}

html {
  font-size: 62.5%;
  scroll-behavior: smooth;
  scroll-padding-top: 4rem;
}

body {
  font-size: 1.6rem;
  line-height: 1.5;
  background-color: hsl(0, 0%, 99%);
  background-size: contain;
  background-position: bottom center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  min-height: 100vh;
  margin: 0;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* end reset */

.con {
  gap: 3rem;
  width: 50%;
  max-width: 1440px;
  border-radius: 2rem;
  position: relative;
  /* overflow: hidden; */
  margin-bottom: 3rem;
}
.e1 {
  color: hsl(212, 6%, 44%);
  font-weight: 200;
  text-align: center;
  font-size: 3rem;
}
.e2 {
  color: hsl(234, 12%, 34%);
  font-weight: 600;
  text-align: center;
}
.e3 {
  color: #9194a1;
  font-weight: 200;
  text-align: center;
  margin-top: 2rem;
  margin-bottom: 4rem;
}
.de {
  display: flex;
  gap: 2rem;
  justify-content: center;
  align-items: center;
}
.d9 {
  display: flex;
  gap: 2rem;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.d {
  padding: 3rem;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  background-color: white;
  width: 33rem;
  height: 22rem;
  flex-shrink: 0;
  border-radius: 2rem;
  display: flex;
  flex-direction: column;
}

.d h1 {
  font-size: 2.3rem;
}
.d p {
  font-size: 1.5rem;
  color: hsl(234, 12%, 34%);
}
.d img{
  width: 5rem;
  height: 5rem;
  align-self: flex-end;
  margin-top: 1rem;
}

.d9d{
  display: flex;
  flex-direction: column;
  gap: 2rem;
  justify-content: center;
  align-items: center
}

.d1 {
  border-top: 5px solid hsl(180, 62%, 55%);
}
.d2 {
  border-top: 5px solid hsl(0, 78%, 62%);
}
.d3 {
  border-top: 5px solid hsl(34, 97%, 64%);
}
.d4 {
  border-top: 5px solid hsl(212, 86%, 64%);
}
@media (max-width:768px) {
  .con{
    width: 90%;
    margin-top: 3rem;
  }
  .e1{
    font-size: 2.4rem;
  }
  .e2{
    font-size: 2.5rem
  }
  .e3{
    font-size: 1.5rem;
  }
  .de{
    flex-direction: column;
  }
  .d9d{
    flex-direction: column;
  }
}