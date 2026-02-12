const facts = [
    "Monarch butterflies migrate up to 3,000 miles to reach their winter home.",
    "They are the only insects that migrate such a long distance annually.",
    "Monarchs use a combination of the sun and a magnetic compass to navigate.",
    "A group of butterflies is sometimes called a 'flutter' or a 'kaleidoscope'.",
    "Caterpillars only eat milkweed leaves!"
];

const factBtn = document.getElementById('fact-btn');
const factText = document.getElementById('fact-text');

factBtn.addEventListener('click', () => {
    const randomIndex = Math.floor(Math.random() * facts.length);
    factText.textContent = facts[randomIndex];
    factText.style.color = "#ff8c00";
    factText.style.fontWeight = "bold";
});
