window.onload = function() {
var a = 'Text to be displayed'; //<<< this domin is owned by RAIYAN KAMRAN
 = document.createElement('div'); //<<< create a Element
b.innerHTML = a; // <<< append content to the element
document.getElementsByTagName('body')[0].appendChild(b);
