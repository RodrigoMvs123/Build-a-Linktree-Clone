# Build-a-Linktree-Clone

https://www.youtube.com/watch?v=GRgt5efpmdM 
https://stock.adobe.com/

https://raw.githubusercontent.com/RodrigoMvs123/Build-a-Linktree-Clone/main/README.md


https://github.com/RodrigoMvs123/Build-a-Linktree-Clone/blame/main/README.md

index.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinkTree Clone</title>
    <link rell="stylesheet" href="styles.css"/>
</head>
<body>
    
 
<header>
    <div class="sharebutton"></div>
</header>
 
 
<div class="Container"></div>
<img 
src="https://pbs.twimg.com/profile_images/1340988467417927682/ifHWLY9C_400x400.png" 
alt="Ania Kubow Avatar" />
 
<div class="image-container">
</div>
 
 
<h1>@Aniakubol</h1>
 
 
<a class="title" href="https://youtube.com/aniakubow"></a>
<div class="icon">https://pics.freeicons.io/uploads/icons/png/16216358401530103330-512.png</div>
 
<p>YouTube</p>
 
<div class="tile-share-button"><p>YouTube</p>
 
    <div class="tile-share-button">https://pics.freeicons.io/uploads/icons/png/5942736241540882609-512.png</div>
    
    <a class="tile" href=""></a> 
    <div class="icon"></div>
    <p></p>
    <div class="tile-share-button" link="https://youtube.com/aniakubow"></div>
 
<a class="tile" href=""></a> 
<div class="icon"></div>
<p></p>
<div class="tile-share-button"></div>
<div class="icon">https://as2.ftcdn.net/v2/jpg/04/83/36/97/1000_F_483369745_d9uQmdRaUGrZjuZC95rh10o64eYunK6c.jpg</div>
 
<p>Twitter</p>
 
<div class = "tile-share-button" link="https://twitter.com/ania_kubow" 
<div class="tile-share-button" https://pics.freeicons.io/uploads/icons/png/5942736241540882609-512.png</div>
 
<a class="title" href="https://twitter.com/ania_kubow"></a>
<class=tile" href= https://bytes.dev/r?=ania"></div>
<div class="icon">https://pics.freeicons.io/uploads/icons/png/20642841761530177259-512.png</div>
 
<p>Coding Tips! </p>
 
<div class="tile-share-button">https://pics.freeicons.io/uploads/icons/png/5942736241540882609-512.png</div>
 < div class="tile-share-button" link = " https://bytes.dev/r?=ania "
<script src="app.js"></script> 
 
 
 
</body>
</html>



styles.css

styles.css
body {
    margin: 0;
    padding: 0;
    background-color: rgb(10, 10, 10);
    color: rgb(240, 240, 240);
    display: flex;
    align-items: center;
    flex-direction: column;
    width: 100vw;
    font-family: Verdana, Tahoma, sans-serif;
 
 
}
 
 
header {
    width: 95%;
    max-width: 788px;
    display: flex;
    justify-content: flex-end;
    padding: 12px;
    margin-top: 15px;
 
}
 
 
.share-button {
    width: 40px;
    height: 40px;
    border-radius: 20px;
    background-color: rgb(240, 240, 240);
}
 
 
.container {
    width: 91%;
    max-width: 680px;
    margin: 10px;
    flex-direction: column;
    align-itmes: center;
 
 
} 
 
 
h1 {
    font-size: 20px;
    margin-bottom: 30px;
 
}
 
 
a {
    text-decoration: none;
    color:rgb(240, 240, 240);
 
}
 
 
.tile {
    width: 100%;
    background-color: rgb(37, 37, 37)
    margin: 7px;
    border-radius: 17px;
    justify-content: space-between;
}
 
 
.tile:hover {
    transition: cubic-bezier(.07, 1.41, .82, 1.41,) 0.2s;
    transform: scale(1.02);
}
 
.tile-share-button {
    margin: 8px;
    width: 40px;
    height: 40px;
    boder-radius: 20px;
    background-color: rgb(52, 52, 52);
}
 
 
.share-button svg {
    margin-left: 12px;
    margin-top: 10px;
    color:rgb(0, 0, 0);
}
 
.image-container  {
    height: 96px;
    width: 96px;
    border-radius: 48px;
    overflow: hidden;
    
}
 
 
.image-container img {
    height: 100%;
 
}
 
.icon {
    margin: 4px 8px;
    width: 44px;
    height: 44px;
 
}



app.js 

app.js
const shareButtons = document.querySelectorAll('.tile-share-buttom')  
console.log(shareButtons)
 
async function copyText(e) {
// prevent button going to the side 
 
e.preventDefault()
const link = this.getAttribut('link')
console.log(link)
try {
    await navigator.clipboard.writeText('link')
    alert("Copie the text:" + link  )
} catch (err) {
 
    console.error(err)
}   
 
 
}
 
shareButtons.forEach(shareButton => 
    shareButton.addEventListener)('click', copyText)) 
 



