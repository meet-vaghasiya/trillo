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
10. if you want html entity direclty using css ( by ::before,::after ) sudo element. than diff iso code reuqired in content property.  
11. if order property use to rearrange order of flex-item. so in responsive if you want second flex item to take 100% width and move in another row, than use `flex-basis:0 0 100%;` and in parent `flex-warp:wrap.` and in second item `order:1` . 
12. some propery is not supprt in other browser. so we require two condition if browser supprt than do this , or do another . for this sass has @support method please see that. in this project we use for mask- property  in description list.
13.  in build of sass to css, sass include lot's of webkit prefix, for if browser not support , so it's better to use sass in all project. 