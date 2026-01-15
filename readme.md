<!-- 🐍 Nokia Style Moving Snake Border Animation (NEW ADDITION) -->
<p align="center">
<svg width="100%" height="140" viewBox="0 0 900 140" xmlns="http://www.w3.org/2000/svg">

  <!-- Border -->
  <rect x="5" y="5" width="890" height="130"
        fill="none" stroke="#2f81f7" stroke-width="2" rx="12"/>

  <!-- Snake head -->
  <rect width="16" height="16" fill="#7ee787">
    <animateMotion
      dur="10s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

  <!-- Snake body -->
  <rect width="14" height="14" fill="#58a6ff">
    <animateMotion
      dur="10s"
      begin="0.4s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

  <rect width="12" height="12" fill="#58a6ff">
    <animateMotion
      dur="10s"
      begin="0.8s"
      repeatCount="indefinite"
      path="
        M 10 10
        L 880 10
        L 880 120
        L 10 120
        L 10 10
      " />
  </rect>

</svg>
</p>

<p align="center"><i>Nokia-style snake moving endlessly around the border</i></p>

<!-- 🐍 END OF NEW ADDITION -->


<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&center=true&vCenter=true&width=500&lines=Projects+with+C+Language;Learning+C+by+Building+Projects;Logic+%7C+Practice+%7C+Growth" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Simple C projects built to improve logic and problem-solving skills</strong>
</p>

<hr>

<h2>🎯 About This Repository</h2>

<p>
This repository contains my <strong>C programming projects</strong> created during
my learning journey. Each project focuses on <strong>logic building</strong>,
clear understanding of concepts, and beginner-friendly implementation.
</p>

<hr>

<h2>🎮 Project 1: Number Guessing Game</h2>

<p>
In this game, the <strong>computer generates a random number under 100</strong>.
The user has to guess the correct number.
</p>

<ul>
  <li>If the guessed number is <strong>greater</strong>, the program displays <b>"Think Lower"</b></li>
  <li>If the guessed number is <strong>smaller</strong>, the program displays <b>"Think Higher"</b></li>
  <li>The game continues until the correct number is guessed</li>
</ul>

<hr>

<h2>🐍 Project 2: Snake, Water & Gun Game</h2>

<p>
This is a simple logic-based game inspired by <strong>Rock, Paper, Scissors</strong>.
The user plays against the computer.
</p>

<ul>
  <li>Snake drinks Water → Snake wins</li>
  <li>Water drowns Gun → Water wins</li>
  <li>Gun kills Snake → Gun wins</li>
</ul>

<p>
The computer randomly selects its choice, and the winner is decided using
<strong>if–else logic</strong>.
</p>

<!-- 🔥 ANIMATION BLOCK STARTS HERE 🔥 -->

<hr>

<!-- 🐍 WORKING Nokia Snake Animation (GitHub Safe) -->
<p align="center">
<svg width="900" height="120" viewBox="0 0 900 120" xmlns="http://www.w3.org/2000/svg">

  <!-- Border -->
  <rect x="5" y="5" width="890" height="110"
        fill="none" stroke="#2f81f7" stroke-width="2" rx="10"/>

  <!-- Snake head -->
  <rect y="15" width="14" height="14" fill="#7ee787">
    <animate attributeName="x"
             from="10" to="860"
             dur="6s"
             repeatCount="indefinite" />
  </rect>

  <!-- Snake body 1 -->
  <rect y="15" width="12" height="12" fill="#58a6ff">
    <animate attributeName="x"
             from="0" to="850"
             dur="6s"
             begin="0.4s"
             repeatCount="indefinite" />
  </rect>

  <!-- Snake body 2 -->
  <rect y="15" width="10" height="10" fill="#58a6ff">
    <animate attributeName="x"
             from="-20" to="830"
             dur="6s"
             begin="0.8s"
             repeatCount="indefinite" />
  </rect>

</svg>
</p>

<p align="center"><i>Nokia-style snake moving continuously</i></p>


<h2 align="center">🎞 Snake • Water • Gun Animation</h2>

<p align="center">
<svg width="520" height="180" viewBox="0 0 520 180" xmlns="http://www.w3.org/2000/svg">

  <!-- Gun kills Snake -->
  <g>
    <text x="40" y="50" font-size="22">🔫 Gun</text>
    <text x="200" y="50" font-size="18">kills</text>
    <text x="330" y="50" font-size="22">🐍 Snake</text>
    <animate attributeName="opacity"
             values="0;1;1;0"
             begin="0s"
             dur="3s"
             repeatCount="indefinite"/>
  </g>

  <!-- Snake drinks Water -->
  <g>
    <text x="40" y="100" font-size="22">🐍 Snake</text>
    <text x="200" y="100" font-size="18">drinks</text>
    <text x="330" y="100" font-size="22">💧 Water</text>
    <animate attributeName="opacity"
             values="0;0;1;1;0"
             begin="1s"
             dur="3s"
             repeatCount="indefinite"/>
  </g>

  <!-- Water destroys Gun -->
  <g>
    <text x="40" y="150" font-size="22">💧 Water</text>
    <text x="200" y="150" font-size="18">destroys</text>
    <text x="330" y="150" font-size="22">🔫 Gun</text>
    <animate attributeName="opacity"
             values="0;0;0;1;1;0"
             begin="2s"
             dur="3s"
             repeatCount="indefinite"/>
  </g>

</svg>
</p>

<p align="center"><i>Looping animation representing Snake–Water–Gun logic</i></p>

<!-- 🔥 ANIMATION BLOCK ENDS HERE 🔥 -->

<hr>

<h2>🏥 Project 3: Medical Store Management System</h2>

<p>
This project is a <strong>console-based medical store management system</strong>
written in C.
</p>

<ul>
  <li>Add new medicines</li>
  <li>View available medicines</li>
  <li>Search medicine by ID</li>
  <li>Manage quantity and price</li>
</ul>

<p>
This project uses <strong>structures, loops, and if–else statements</strong>
to manage data in a simple way.
</p>

<hr>

<h2>🛠 Concepts Used</h2>

<ul>
  <li>if–else statements</li>
  <li>Loops</li>
  <li>Functions</li>
  <li>Structures</li>
  <li>Basic input/output</li>
</ul>

<hr>

<p align="center">
  <strong>👨‍💻 Author:</strong> Nayandeep Chouhan <br>
  🌱 Learning C Programming step by step
</p>

<p align="center">
  ⭐ Thanks for visiting my repository ⭐
</p>
