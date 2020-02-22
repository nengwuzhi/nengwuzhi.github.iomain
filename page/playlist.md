---
title: 歌单
date: 2019-02-21 16:14:00
type: "playlist"
---

<link rel="stylesheet" href="APlayer.min.css">
<div id="aplayer"></div>
<script src="APlayer.min.js"></script>

const ap = new APlayer({
    container: document.getElementById('aplayer'),
    audio: [{
        name: 'name',
        artist: 'artist',
        url: 'url.mp3',
        cover: 'cover.jpg'
    }]
});

{% meting "523845661" "netease" "playlist" "theme:#FF4081" "mode:circulation" "mutex:true" "listmaxheight:340px" "preload:auto" %}
