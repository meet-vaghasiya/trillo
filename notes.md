1. font-size in html vs body:
   - if you mension font-size in body{font-size:62.5%}. and not mesion font-size in element. than it will take font-size:1 rem = 10px. becuase it inherit from body.
   - but if you mesion font-size in eleement , than 62.5% will not work. it take element font-size. suppose you give 1.6rem  here 1rem is 16px in root element.not from body. so it will return font-size 25.9px.
   - so always use font-size in root for convert default rem.

2. if sass is compile all partials. than make foldere struture like this. https://stackoverflow.com/questions/24203318/sass-watch-not-recompiling
3. 