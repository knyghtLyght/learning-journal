# Day 3

Not as tired today. Diet shift seems to have passed. Waking up was eaiser but sleep still isn't good. On time today too. Tuesday trafic seems anomalously bad. 

Git works. I was able to pull from my home system no problem. 

## What we learned today

- CSS
  - The box model holds that each element has a box around it that can be styled. also makes for great imagry when moving things around.
    - You can actually set a border to help you see where shit is.'
  - CSS will cascade from top to bottom. Most general to least.
  - CSS should also be organized in the same way. Most general styling first followed by more spesific.
  - When targeting an element make sure you are acting on the element you want and not it's container. 
    - li display: in-line as an example.
  - Color can be writen in hex, RGBA or plain text when avalible
  - The ID selector uses #id
    - section id='test' = #test
  - The class selector uses .class
    - section class='test' = .test
  - inheritance selectors
    - .nav li selects all the li in the nav class
    - .nav > li selects direct decendents only. So only li's in the nav class itself nothing nested.
    - Works with type tags too
      nav li instead of .nav li
  - Margin refers to adding space outside the elements "box"
  - Padding refers to adding space inside the elements "box"
  - Margin short hand can take up to 4 attributes. 
    - top, right, bot, left
    - top, right/left, bot
    - top/bot, right/left
  Border short hand can take 3 attributes
    - width, style, color
  
- HTML
  - ul = unordered list
  - ol = ordered list
  - both take li for list items
  - For loops
    - for(Start; condition; increment){code;}
    - for(var i = 0; i < array.length; i++){code;}
  - While loops
    - may never run depending on condition
    - while(condition){code;}
  - Do while loops
    - code will always run at least once
    - do{code} while(condition);

- Git
  - Pull will download and merge files
  - git pull origin master
  - pull target is based on the repo you're in. 