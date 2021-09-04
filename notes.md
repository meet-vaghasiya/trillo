1. font-size in html vs body:
   - if you mension font-size in body{font-size:62.5%}. and not mesion font-size in element. than it will take font-size:1 rem = 10px. becuase it inherit from body.
   - but if you mesion font-size in eleement , than 62.5% will not work. it take element font-size. suppose you give 1.6rem  here 1rem is 16px in root element.not from body. so it will return font-size 25.9px.
   - so always use font-size in root for convert default rem.

2. if sass is compile all partials. than make foldere struture like this. https://stackoverflow.com/questions/24203318/sass-watch-not-recompiling
3. diff between sass variable and scss variable?
4. svg file from sprite only work in server.
5. give `image to display:block. it will remove thin line.`
6. **svg act as inline-bock.** so it will have line-height. so even if we do align-items:center it not ecnter excalty. which difficult to even see because only 2-3px gap. to solve this issue give `line-height:0` or set `parent to display:flex.`
7. use `currentColor` property to color border-bottom or normal border. it will take current text color automaticallly and if you change in hover border color also change automatically. `border-bottom: 1px solid currentColor;`
8. if you increse padding than will create gap between border and innerText.
9. if you want to change color of background image than use background mask property.but it only work in modeern browser.
10. 