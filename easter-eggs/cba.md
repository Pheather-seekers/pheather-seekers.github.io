---
layout: default
title: Club of Bird Aficionados
permalink: /easter-eggs/cba
---

# **Crazy Bird Aficionados**

<img id="night-heron-img" src="https://github.com/Pheather-seekers/photos/blob/main/1.webp?raw=true" alt="" style="width:85%" />

<script>
(function() {
var imgs = [
{ src: 'https://github.com/Pheather-seekers/photos/blob/main/1.webp?raw=true', weight: 1 },
{ src: 'https://github.com/Pheather-seekers/photos/blob/main/2.webp?raw=true', weight: 1 },
{ src: 'https://github.com/Pheather-seekers/photos/blob/main/3.webp?raw=true', weight: 1 },
];
var totalWeight = 0;
for (var i = 0; i < imgs.length; i++) {
totalWeight += imgs[i].weight;
}
var pick = imgs[0].src;
var random = Math.random() * totalWeight;
for (var i = 0; i < imgs.length; i++) {
random -= imgs[i].weight;
if (random < 0) {
pick = imgs[i].src;
break;
}
}
var el = document.getElementById('night-heron-img');
if (el) el.src = pick;
console.log("正在随机把一张夜鹭的图片选择出来")
})();
</script>
