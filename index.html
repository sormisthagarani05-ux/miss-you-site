<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Tap When You Miss Me 💗</title>

<style>
body {
  margin: 0;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: #ffd6e0;
  font-family: "Poppins", cursive;
  text-align: center;
  padding: 15px;
}

h1 {
  color: #ff4d88;
}

.heart {
  font-size: 100px;
  cursor: pointer;
  animation: pulse 1.5s infinite;
}

@keyframes pulse {
  0% {transform: scale(1);}
  50% {transform: scale(1.1);}
  100% {transform: scale(1);}
}

.counter {
  margin: 10px;
  color: #ff4d88;
  font-size: 20px;
}

textarea {
  width: 90%;
  max-width: 300px;
  height: 80px;
  border-radius: 10px;
  border: none;
  padding: 10px;
  resize: none;
  margin-top: 10px;
}

button {
  margin-top: 8px;
  padding: 8px 14px;
  border: none;
  border-radius: 10px;
  background: #ff4d88;
  color: white;
}

.history {
  margin-top: 15px;
  font-size: 13px;
  max-width: 320px;
  text-align: left;
  color: #ff4d88;
}
</style>
</head>

<body>

<h1>Tap when you miss me 💗</h1>

<div class="heart" onclick="tapHeart()">💖</div>

<div class="counter" id="todayCount"></div>

<textarea id="note" placeholder="write something... (max 100 words) 💌"></textarea>
<br>
<button onclick="saveNote()">Save 💕</button>

<div class="history" id="history"></div>

<script>
const today = new Date().toISOString().split("T")[0];

function getData() {
  try {
    return JSON.parse(localStorage.getItem("missData")) || {};
  } catch {
    return {};
  }
}

function saveData(data) {
  try {
    localStorage.setItem("missData", JSON.stringify(data));
  } catch {
    alert("Storage not available 😭");
  }
}

function tapHeart() {
  let data = getData();

  if (!data[today]) data[today] = { taps: 0, notes: [] };

  data[today].taps++;
  saveData(data);
  updateUI();
}

function saveNote() {
  let data = getData();
  let text = document.getElementById("note").value.trim();

  if (!text) return;

  let wordCount = text.split(/\s+/).length;
  if (wordCount > 100) {
    alert("Keep it under 100 words pls 🥺");
    return;
  }

  if (!data[today]) data[today] = { taps: 0, notes: [] };

  data[today].notes.push(text);
  saveData(data);

  document.getElementById("note").value = "";
  updateUI();
}

function updateUI() {
  let data = getData();

  let taps = data[today]?.taps || 0;
  document.getElementById("todayCount").innerText =
    `Today: ${taps} taps 💕`;

  let html = "<b>History 💭</b><br>";

  Object.keys(data).sort().reverse().forEach(date => {
    html += `<br>${date} → ${data[date].taps} taps`;

    data[date].notes.forEach(n => {
      html += `<br>💌 ${n}`;
    });
  });

  document.getElementById("history").innerHTML = html;
}

updateUI();
</script>

</body>
</html>
