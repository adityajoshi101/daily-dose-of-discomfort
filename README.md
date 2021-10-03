# daily-dose-of-discomfort
My first website!
<html>

  <head>
    <h1 class="page-title">Daily Dose of Discomfort</h1>
    <meta charset="utf-8" />
    <link rel="stylesheet" type="text/css" href="main.css">
  </head>

  <body>
    <div class="page-description">
      <h3>Challenge yourself to complete one task everyday</h3>
    </div>
    <div class="TT">
      <h3>
        Today's Tasks:
      </h3>
      <ul>
        <li>Call a loved one</li>
        <li>Do 15 pushups</li>
        <li>Learn a new word in a different language</li>
      </ul>
      &nbsp;&nbsp;
    </div>

    <div class=task.random>
      <h2>

      </h2>
    </div>


    <div class="form">
      <form>
        <label for="email">Input your email to get notified daily:</label><br>
        <input type="text" id="email" name="email"><br>
        <input type="submit">
      </form>
    </div>
    </html>
  html,
body {
  min-height: 100%;
  display: flex;
  flex-direction: column;
  font-weight: 300;
  line-height: 1.5;
}

body {
  font-family: 'Lato', Courier New;
  background-image: url('https://i.pinimg.com/originals/a9/34/6e/a9346ef8a1ad0211f68309a62cd82919.png');
  background-position: center top;
  background-size: cover;
  text-align: center;
  display: flex;
  flex-wrap: wrap;
  justify-content: center
}

.page-title {
  text-align: center;
  font-weight: 100;


}

.page-description {

  text-align: center;

}

.form {

  text-align: center;
}

.TT {
  text-align: left;


}

/* FOOTER NAVIGATION */

nav {
  background-color: #FFF;
}

nav li {
  margin: 0;
  padding: 0 10px;
}

nav ul {
  display: inline;
}

.contact-btn {}

.contact-btn a {
  margin-right: 30px;
  padding: 8px 18px;
  border: 1px solid #204156;

}

.contact-btn a:active {
  position: relative;
  bottom: 2px;
}

nav a {
  height: 60px;
  line-height: 60px;
  color: #204156;
  text-decoration: none;
}
