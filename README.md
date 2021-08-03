## PAC MAN coding assignment
![](https://media.giphy.com/media/A8NkSPltT13H2/giphy.gif)

Working Code Live: [Responsive PAC MAN movement](https://ajdxpro.github.io/pac-man/)

I made it responsive to the current dynamic window size by adding a line to the
`function checkPageBounds(direction, imgWidth, pos, pageWidth) {
  pageWidth = window.innerWidth;
  if (direction == 0 && pos + imgWidth > pageWidth) direction = 1;
  if (direction == 1 && pos < 0) direction = 0;

  return direction;
}`
