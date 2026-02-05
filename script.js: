const yesBtn = document.getElementById("yes");
const noBtn = document.getElementById("no");
const response = document.getElementById("response");

const noResponses = [
  "Think again… love like this doesn’t knock twice 💫",
  "Are you sure? Even the stars would disagree 🌌",
  "No? That word feels too cold for Valentine’s warmth ❄️❤️",
  "Gentle reminder: saying yes could change everything 🌹",
  "Don’t be shy… the heart knows what it wants 💕",
  "Mature thought: happiness is rare, don’t push it away 🌟",
  "Naughty whisper: you’ll regret missing this kiss 😏💋",
  "Poetic plea: roses wilt, but my love won’t 🌹",
  "Playful tease: come on, you know you want to 😜",
  "Final chance: rethink before Cupid flies past 🏹"
];

let noClickCount = 0;

yesBtn.addEventListener("click", () => {
  response.textContent = "I can’t wait to see you 💖✨";
  response.classList.add("show");
});

noBtn.addEventListener("click", () => {
  response.textContent = noResponses[noClickCount % noResponses.length];
  response.classList.add("show");
  noClickCount++;
});
