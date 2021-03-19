const zdjecie = new Image(300, 300);
zdjecie.src = 'img1.png' , 'img1.png';
document.getElementById('app').appendChild(zdjecie);


const paragraf = document.createElement('p')
paragraf.setAttribute('id' , 'par1')
paragraf.innerText = "Pasjans – układanka karciana, zwana także samotnikiem przy użyciu jednej, dwu lub rzadziej większej liczby talii kart, zazwyczaj dla jednej osoby, w celu ułożenia ich według ustalonych wcześniej reguł w określone sekwencje lub inne uporządkowane układy, bezpośrednio kartami lub za pomocą kart wirtualnych"
const app = document.getElementById('app')
app.appendChild(paragraf)

document.getElementById('app').className = 'gridgrid';
