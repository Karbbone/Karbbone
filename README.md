<style>
h3 {
    position: relative;
    display: inline-block;
}

.fav::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #eb3636;
    border-radius: 10px;
}
.bdd::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #24ca4a;
    border-radius: 10px;
}
.lang::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #3facee;
    border-radius: 10px;
}
.tool::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #dede15;
    border-radius: 10px;
}
.current::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 3px;
    background-color: #fea122;
    border-radius: 10px;
}
.element {
    display: inline-block;
    background-color: white;
    padding: 7px;
    margin-top: 10px;
    margin-bottom: 10px;
    transition: transform 0.1s, padding 0.3s, margin 0.3s;
    border: 3px solid;
    border-radius: 50%;
}
.element img {
    width: 45px;
    height: 45px;
}

.element:hover {
    transform: scale(1.2);
    padding:10px;
    margin-left:5px;
    margin-right:5px;
    margin-top:5px;
    margin-bottom:5px;
}
#fav > .element {
    border-color:#eb3636;
}
#bdd > .element {
    border-color:#24ca4a;
}
#lang > .element {
    border-color:#3facee;
}
#tool > .element {
    border-color:#dede15;
}
#current > .element {
    border-color:#fea122;
}

@import "compass/css3";

.seperator-wrapper {
  width: 70%;
  margin-left: auto;
  margin-right: auto;
}

.seperator {
  height: 3px;
  animation: rotate 3s infinite linear;
  margin-bottom: 10px;
}


@keyframes rotate {
  from {
    background-position: -3000px;
  }
  to { 
    background-position: 0px;
  }
}

.gradient {
    background: -webkit-linear-gradient(left,  rgba(48,255,144,1) 0%,rgba(237,45,237,1) 25%,rgba(201,152,38,1) 50%,rgba(48,255,230,1) 75%,rgba(48,255,144,1) 100%);
}
</style>

![MasterHead](./jungle-fond-foret-nature.jpg)

<section class="seperator-wrapper">
  <div class="seperator gradient">
  </div>
</section>

<h1 align="center">Hi 👋 ! I'm Clément Maillet</h1>
<h2 align="center">I'm a student developer from France</h3>

- 🧠 Student at **IUT DE VANNES**
- 😀 Personality : **Calm, Thirst for knowledge**
- 📫 You can contact me at **clement.maillet56@gmail.com**

<h3 align="left" class="fav">Favorites languages & Tools & Frameworks:</h3>
<div style="text-align: left;" id="fav">
    <a href="https://www.java.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg"
                alt="java" style="vertical-align: middle;">
    </a>
    <a href="https://www.mysql.com/" target="_blank" rel="noreferrer" class="element">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg"
            alt="mysql" style="vertical-align: middle;">
    </a>
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg"
        alt="react" style="vertical-align: middle;"/>
    </a>
</div>
<h3 align="left" class="bdd">BDD:</h3>
<div style=""  id="bdd">
    <a href="https://www.influxdata.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/influxdb/influxdb-original-wordmark.svg"
        alt="influxdb" style="vertical-align: middle;">
    </a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg"
        alt="mongodb" style="vertical-align: middle;">
    </a>
    <a href="https://www.mysql.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg"
        alt="mysql" style="vertical-align: middle;">
    </a>
    <a href="https://neo4j.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/neo4j/neo4j-original-wordmark.svg"
        alt="neo4j" style="vertical-align: middle;">
    </a>
    <a href="https://www.sqlite.org/index.html" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original-wordmark.svg"
        alt="sqlite" style="vertical-align: middle;">
    </a>
</div>

<h3 align="left" class="lang">Languages:</h3>
<div style="text-align: left;" id="lang">
    <a href="https://isocpp.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg"
            alt="c++" style="vertical-align: middle;">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
            alt="css3" style="vertical-align: middle;">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
            alt="html5" style="vertical-align: middle;">
    </a>
    <a href="https://www.java.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original-wordmark.svg"
            alt="java" style="vertical-align: middle;">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer" style="border-radius: 50%" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
            alt="javascript" style="vertical-align: middle;border-radius: 25%">
    </a>
    <a href="https://www.php.net/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg"
            alt="php" style="vertical-align: middle;">
    </a>
    <a href="https://www.python.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg"
            alt="python" style="vertical-align: middle;">
    </a>
</div>

<h3 align="left" class="tool">Tools & Frameworks:</h3>
<div style="text-align: left;"id="tool">
    <a href="https://developer.android.com/studio" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/androidstudio/androidstudio-original-wordmark.svg"
            alt="android studio"style="vertical-align: middle;">
    </a>
    <a href="https://getbootstrap.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original-wordmark.svg"
            alt="bootstrap" style="vertical-align: middle;">
    </a>
    <a href="https://www.docker.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg"
            alt="docker" style="vertical-align: middle;">
    </a>
    <a href="https://expressjs.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg"
            alt="express" style="vertical-align: middle;">
    </a>
    <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original-wordmark.svg"
            alt="fastapi" style="vertical-align: middle;">
    </a>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original-wordmark.svg"
            alt="git" style="vertical-align: middle;">
    </a>
    <a href="https://nodejs.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"
            alt="node.js" style="vertical-align: middle;">
    </a>
    <a href="https://www.npmjs.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/npm/npm-original-wordmark.svg"
            alt="npm" style="vertical-align: middle;">
    </a>
    <a href="https://www.postman.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg"
            alt="postman" style="vertical-align: middle;">
    </a>
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg"
        alt="react" style="vertical-align: middle;"/>
    </a>
   <a href="https://swagger.io/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swagger/swagger-original-wordmark.svg"
            alt="swagger"style="vertical-align: middle;">
    </a>
    <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg"
            alt="tailwindcss" style="vertical-align: middle;">
    </a>
    <a href="https://vuejs.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg"
            alt="vue.js" style="vertical-align: middle;">
    </a>
    <a href="https://webpack.js.org/" target="_blank" rel="noreferrer" class="element">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/webpack/webpack-original.svg"
            alt="webpack" style="vertical-align: middle;">
    </a>
</div>

<h3 align="left" class="current">Currently learning:</h3>
<div style="text-align: left;" id="current">
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer" style="border-radius: 50%" class="element">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"
        alt="typescript" style="vertical-align: middle;border-radius: 25%">
</a>
</div>
