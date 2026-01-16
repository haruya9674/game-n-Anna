<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Adjective Learning</title>

<style>
body{
  font-family: system-ui, sans-serif;
  text-align:center;
  background:#f4faff;
  padding:20px;
}
h1{margin-bottom:10px}

/* ===== back button ===== */
.back-menu{
  display:inline-block;
  margin-bottom:15px;
  padding:10px 18px;
  background:#555;
  color:white;
  border-radius:10px;
  text-decoration:none;
  font-weight:bold;
}
.back-menu:active{
  transform:scale(0.95);
}

/* ===== tabs ===== */
.tabs{
  display:flex;
  gap:6px;
  margin-bottom:20px;
}
.tab{
  flex:1;
  padding:10px;
  background:#ddd;
  border-radius:8px;
  cursor:pointer;
}
.tab.active{
  background:#87ceeb;
  font-weight:bold;
}

.section{display:none}
.section.active{display:block}

.word{
  font-size:36px;
  margin:25px 0;
  font-weight:bold;
}

/* ===== answer buttons ===== */
.btn{
  width:140px;
  font-size:20px;
  padding:14px 0;
  margin:10px;
  border:none;
  border-radius:10px;
  font-weight:bold;
  cursor:pointer;
}
.btn-yes{
  background:#4caf50;
  color:white;
}
.btn-no{
  background:#f44336;
  color:white;
}
.btn:active{
  transform:scale(0.95);
}

.result{
  font-size:22px;
  margin-top:10px;
  height:26px;
}
.score{
  margin-top:10px;
  font-weight:bold;
}

.list{
  max-width:500px;
  margin:auto;
}
.list div{
  background:white;
  padding:12px;
  margin:6px 0;
  border-radius:6px;
  cursor:pointer;
  box-shadow:0 2px 6px rgba(0,0,0,.1);
}
</style>
</head>

<body>

<!-- 🔙 Back to Menu -->
<a href="index.html" class="back-menu">← Back to Menu</a>

<h1>Adjective Learning</h1>

<div class="tabs">
  <div class="tab active" onclick="show('game')">Game</div>
  <div class="tab" onclick="show('adj')">Adjective List</div>
  <div class="tab" onclick="show('not')">Not Adjective List</div>
</div>

<!-- GAME -->
<div id="game" class="section active">
  <div class="word" id="gameWord">---</div>

  <button class="btn btn-yes" onclick="answer(true)">
    Adjective
  </button>

  <button class="btn btn-no" onclick="answer(false)">
    Not Adjective
  </button>

  <div class="result" id="result"></div>
  <div class="score" id="score">Score: 0</div>
</div>

<!-- ADJECTIVE LIST -->
<div id="adj" class="section">
  <h2>Adjectives</h2>
  <div class="list" id="adjList"></div>
</div>

<!-- NOT ADJECTIVE LIST -->
<div id="not" class="section">
  <h2>Not Adjectives</h2>
  <div class="list" id="notList"></div>
</div>

<script>
function speak(text){
  speechSynthesis.cancel();
  const u = new SpeechSynthesisUtterance(text);
  u.lang = "en-US";
  speechSynthesis.speak(u);
}

function show(id){
  document.querySelectorAll('.section').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  event.target.classList.add('active');
}

const words = [
  ["happy",true],["sad",true],["angry",true],["excited",true],
  ["friendly",true],["kind",true],["polite",true],["brave",true],
  ["big",true],["small",true],["tall",true],["short",true],
  ["fast",true],["slow",true],["clean",true],["dirty",true],
  ["bright",true],["dark",true],["quiet",true],["loud",true],
  ["safe",true],["dangerous",true],["easy",true],["difficult",true],
  ["strong",true],["weak",true],["early",true],["late",true],
  ["hot",true],["cold",true],["fresh",true],["old",true],
  ["teacher",false],["dog",false],["cat",false],["run",false],
  ["jump",false],["eat",false],["drink",false],["city",false],
  ["book",false],["music",false],["play",false],["write",false],
  ["read",false],["water",false],["car",false],["house",false],
  ["school",false],["child",false],["think",false],["walk",false]
];

let score = 0;
let current = null;

function next(){
  current = words[Math.floor(Math.random()*words.length)];
  document.getElementById("gameWord").textContent = current[0];
  document.getElementById("result").textContent = "";
}

function answer(isAdj){
  const correct = isAdj === current[1];
  document.getElementById("result").textContent = correct ? "Correct!" : "Wrong!";
  speak(correct ? "Correct" : "Wrong");
  if(correct) score++;
  document.getElementById("score").textContent = "Score: " + score;
  setTimeout(next,600);
}

const adjList = document.getElementById("adjList");
const notList = document.getElementById("notList");

words.forEach(w=>{
  const d = document.createElement("div");
  d.textContent = w[0];
  d.onclick = ()=>speak(w[0]);
  (w[1] ? adjList : notList).appendChild(d);
});

next();
</script>

</body>
</html>
