### Hi! I'm Maris Botero 🦄

<p><em>Machine Learning Engineer🤓</br>
<p>I play with data, I paint with light and sometimes I take care of plants<p>

</em></p>

<div class="heart heart-bg"></div>
<div class="heart heart-main"></div>

<style>
body {
  width: 100%;
  height: 100%;
  min-width: 500px;
  min-height: 500px;
  overflow: hidden;
}

.heart {
  position: absolute;
  width: 100px;
  height: 90px;
  top: 50%;
  left: 50%;
  margin-top: -45px;
  margin-left: -50px;
  
  &:before,
  &:after {
    content: '';
    position: absolute;
    top: 0;
    width: 50px;
    height: 80px;
    background: #fc2e5a;
    border-radius: 50px 50px 0 0;
  }
  
  &:before {
    left: 50px;
    transform: rotate(-45deg);
    transform-origin: 0 100%;
  }
  
  &:after {
    left: 0;
    transform: rotate(45deg);
    transform-origin: 100% 100%;
  }
}

.heart-bg {
  animation: heart-anim 1s linear .4s infinite;
  
  &:before,
  &:after {
    background-color: #ff7693;
  }
}

.heart-main {
  animation: pounding .5s linear infinite alternate;
}

@keyframes pounding {
  0% {
    transform: scale(1.5);
  }
  100% {
    transform: scale(1);
  }
}

@keyframes heart-anim {
  46% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.3);
  }
  52% {
    transform: scale(1.5);
  }
  55% {
    transform: scale(3);
  }
  100% {
    opacity: 0;
    transform: scale(50);
  }
}
</style>
<!--
**marisbotero/marisbotero** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
