---
theme: seriph
background: images/cover.jpg
colorSchema: light
fonts:
  sans: 'Noto Sans Japanese'
  serif: 'Noto Serif Japanese'
  mono: 'JetBrains Mono'
layout: cover
title: マルチメディアと表現 &#8544;
title-template: '%s- マルチメディアと表現&#8544'
class: text-center
transition: slide-left
mdc: true
---

# マルチメディアと表現 &#8544;

## Lesson01 test

---
layout: iframe-right
url: https://editor.p5js.org/dmhashi/full/bdOymDj9N
---

# p5.js コードテスト

```javascript{*}{maxHeight:'400px'}
let size = 50;
let x,y;
let r=0;


function setup() {
  createCanvas(400, 400);
  rectMode(CENTER);
  frameRate(10);
  angleMode(DEGREES);
}

function draw() {
  background(220);
  for(x = size/2; x<400; x+=size){
      for(y = size/2; y<400; y+=size){
    push();
      translate(x, y);
      rotate(mouseX);
      scale(2);
      rect(0,0,size/2,size/2);
    pop();
      }
  }
r+=1
}

```
---
layout: image-right
image: images/Programming-cuate.svg
---

# 画像貼り付け
画像貼り付けのテストです。

- item 1
- item 2
- item 3

---
layout: end
---

終わり