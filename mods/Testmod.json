{
  "name": "InvertScreen",
  "author": "Charles",
  "description": "Inverts all screen colors using CSS filters.",
  "code": "function InvertScreen() {
  console.log("InvertScreen is running");

  const invertStyle = document.createElement('style');
  invertStyle.id = 'invert-screen-style';
  invertStyle.textContent = `
    html {
      filter: invert(1) hue-rotate(180deg) !important;
    }
  `;
  document.head.appendChild(invertStyle);
}

function InvertScreen_stop() {
  console.log("InvertScreen stopped");

  const style = document.getElementById('invert-screen-style');
  if (style) style.remove();
}
"
}
