javascript
// Light/Dark mode toggle
const btn = document.getElementById('toggle-theme');
btn.addEventListener('click', () => {
  document.body.classList.toggle('dark-mode');
});

// Optional: Add dark mode styles in CSS


Add this at the end of your style.css for dark mode:

css
.dark-mode {
  background: #181818;
  color: #f4f4f4;
}
.dark-mode header, .dark-mode footer {
  background: #222;
}
.dark-mode section {
  background: #232323;
  color: #f4f4f4;
}

