# mmakademia-slide

A videók háttere fekete, a képeké enyhe szürke:
```
.fotorama__stage__frame.fotorama__active {
    background-color: #F5F5F5;
}

.fotorama__stage__frame--video.fotorama__loaded {
    background-color: #000000;
}
```
1. a fotorama.js hqdefault.jpg thumbnail kérése maxresdefault.jpg -re lett módosítva
2. a fotorama beállításai:
```
data-width="930" 
data-height="523" 
data-thumbheight="80" 
data-thumbwidth="80" 
data-thumbfit="cover" 
data-fit="scaledown" 
data-nav="thumbs" 
data-max-width="100%" 
data-hash="true"
```
