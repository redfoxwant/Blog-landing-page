<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <body>
    <header>
          <img class="logoImg" src="./assets/img/2.png">  
          <img class="icons" src="./assets/icons/twitter.png">
          <img class="icons" src="./assets/icons/figma.png">
          <img class="icons" src="./assets/icons/dribbble.png">
          <img class="icons" src="./assets/icons/github.png">
     </header>

    <main>
      <article class="mainArticle">
        <section class='mainSection'>
          <img  src="./assets/cards/4.jpg">
        </section>
        <aside class="mainArticleTxt">
        <div class="articleTop">
          <span><b>Front-end</b> - 1 Hour Ago</span>
        </div>
        <h2>Optimizing CSS for faster page loads</h2>
        <p>Not long ago I decided to improve the loading times of my website. It already loads pretty fast, but I knew there was still room for improvement and one of them was CSS loading. I will walk you through the process and show you how you can improve your load times as well.</p>
        <p>To see how CSS affects the load time of a webpage we first have to know how the browser converts an HTML document into a functional webpage...</p> 
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div>
        </aside>
      </article>

      <article class="subArticle">
        <section class="subSection">  
          <img src="./assets/cards/1.jpg"> 
          <div class="articleTop">
          <span><b>Front-end</b> - 1 Hour Ago</span>
          </div>
          <h2>Css Grid</h2>
          <p>The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.</p>
       <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div>
        </section>

        <section class="subSection">
        <img src="./assets/cards/2.jpg"> 
        <div class="articleTop">
          <span><b>Front-end</b> - 2 Months Ago</span>
        </div>
        <h2>Colors in Css</h2>
        <p>Colors play a vital role in making a web page usable or not. In CSS, we can control the foreground and background color of an element with the color and background properties.</p> 
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div> 
        </section>

        <section class="subSection">
        <img src="./assets/cards/3.jpg"> 
        <div class="articleTop">
          <span><b>Front-end</b> - 2 Months Ago</span>
        </div>
        <h2>Css Variables</h2>
        <p>CSS variables are custom properties that cascade normally and even inherit. They start with a reserved -- prefix, and there are no real rules about their value.</p>  
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div>
        </section>

        <section class="subSection">   
          <img src="./assets/cards/1.jpg">
          <div class="articleTop">
          <span><b>Front-end</b> - 1 Month Ago</span>
        </div>
        <h2>Css Grid</h2>
        <p>>The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.</p>
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div>
        </section>

        <section class="subSection">  
          <img src="./assets/cards/2.jpg">
          <div class="articleTop">
          <span><b>Front-end</b> - 2 Months Ago</span>
        </div>
        <h2>Colors in Css</h2>
        <p>Colors play a vital role in making a web page usable or not. In CSS, we can control the foreground and background color of an element with the color and background properties.</p>
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div> 
        </section>

        <section class="subSection">
        <img src="./assets/cards/3.jpg">   
        <div class="articleTop">
          <span><b>Front-end</b> - 2 Months Ago</span>
        </div>
        <h2>Css Variables</h2>
        <p>CSS variables are custom properties that cascade normally and even inherit. They start with a reserved -- prefix, and there are no real rules about their value.</p>
        <div class="articleBottom">
          <span>3 min read</span>
          <a class="linkTag" href="">Read Full--></a>
        </div>
        </section>
       
      </article>
    </main>

    <footer>  
      <b class="footer1">Join our Team of Writers</b>
      <p class="footer2">On dadas, writers earn a living doing what they love.</p>
      <p class="footer2">Getting started is easy. Just pay a one time <b>$25 fee</b> and everything is ready to go</p>
      <button>JOIN US</button>
    </footer>
  </body>

</template>

<style>
#app{
  
}
body{
  display: flex;
  position: relative;
  width: 1144px;
  height: 1925px;
  background: white;
  border: ;
  font-family: sans-serif;
  margin-left: 50px;

}
header{
  width: 1110px;
  height: 100px;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 10px;
  gap: 20px;


  position: absolute;
  top: 0px;

  border: ;
  
}
.icons{
  width: 25px;
  height: 25px;
  position: relative;
  left: 835px;
  cursor: pointer;
}
.logoImg{
  width: 95px;
  height: 95px;
}
.articleTop{
  color: #4B4B4B;
  font-weight: 700;
  font-size: 12px;
  
}
.articleBottom{
  display: flex;
  justify-content: space-between;
  gap: 160px;
}
.linkTag{
  color:#1473E6 ;
  font-weight: 700;
  font-size: 12px;
  align-items: center;
}
.mainArticle{
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  width: 1144px;
  height: 296px;
  align-items: flex-start;
  padding: 8px;
  gap: 16px;
  position: absolute;
  top: 148px;
  background: ;
  border: ;
  border-radius: 5px;
}
.mainSection{
  width: 500px;
  height: 280px;
  border:;
  flex: none;
  order: 0;
  flex-grow: 0;
}
.mainArticleTxt{
  border: ;
}
.subArticle{
  position: absolute;
  display: flex;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
  width: 1140px;
  height: 850px;
  top: 480px;
  border:;
  background: white;
  
}
.subSection{
  position: relative;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 8px;
  width: 350px;
  height: 435px;
  background: ;
  border:1px solid #F5F5F5 ;
  border-radius: 5px;
  margin-left: 23px; 
  margin-top: 15px;
  }

footer{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 10px 55px;
 
  position: absolute;
  width: 1040px;
  height: 200px;  
  top: 1550px;

  background: ;
}
.footer1{
  font-weight: 600 ; 
  font-size: 36px;
  color: #2C2C2C;
  margin-bottom: 25px;

}
.footer2{
  font-weight: 500;
  font-size: 20px;
  color: #6E6E6E;
  margin-top: -10px;
}
button{
  color: white;
  background: black;
  cursor: pointer;
  width: 190px;
  height: 50px;
  padding: 12px 55px;
  border-radius: 5px;
  font-weight: 500;
  font-size: 18px;
  line-height: 21px;
  margin-top: 15px;
}

</style>
