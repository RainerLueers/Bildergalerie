---
title: Bildergalerie
---  
# Hier ein paar Bilder

<p align="left">
<input type="button" value="zurück" onClick="if (i>0) { LoadPic(--i) };">
<input type="button" value="vor" onClick="if (i<pictures.length-1) { LoadPic(++i) };">
</p>
<p align="left">
<img name="image" src="foto1.jpg">
</p>
<script type="text/javascript">
pictures = new Array("foto1.jpg", "foto2.jpg", "foto3.jpg", "foto4.jpg", "foto5.jpg");
var i = 0;
function LoadPic(a) {
document.images['image'].src = pictures[a];
}
</script>
