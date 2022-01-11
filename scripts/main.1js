// var myHeading = document.querySelector('h1');
// myHeading.textContent = 'Привет, мир!';

// let myVariable;
// myVariable = 'Bob';
/*
var myVariable = 'Bob';
myVariable;
myVariable = 'Steve';
myVariable;

var myVariable1 = 'TEXT';
var myVariable2 = 10;
var myVariable3 = true;
var myVariable4 = [1, 'Bob', 'Steve', 10, false];
myVariable4[0];
var myVariable5 = document.querySelector('h1');
*/

// var iceCream = 'chocolate';
// if (iceCream === 'choclate') {
//     alert('О да, я люблю шоколадное мороженное!');
// } else {
//     alert('О нет, но я всё равно его люблю!');
// }

// function multiply(num1, num2) {
//     var result = num1 * num2;
//     return result
// }

// alert(multiply(4, 84))

// document.querySelector('html').onclick = function() {
//     alert('АУЧ! Перестань тыкать в меня!')
// }

var myImage = document.querySelector('img');

myImage.onclick = function() {
    var mySrc = myImage.getAttribute('src');
    if (mySrc === 'images/firefox-icon.svg') {
        myImage.setAttribute('src', 'images/chrome-icon.svg');
    } else {
        myImage.setAttribute('src', 'images/firefox-icon.svg')
    }
}

var myButton = document.querySelector('button');
var myHeading = document.querySelector('h1');

function setUserName() {
    var myName = prompt('Пожалуйста введите ваше имя.');
    localStorage.setItem('name', myName);
    myHeading.textContent = 'Мозила - это молиза, ' + myName;
}

if(!localStorage.getItem('name')) {
    setUserName;
} else {
    var storedName = localStorage.getItem('name');
    myHeading.textContent = 'Мозила - это молиза, ' + storedName;
}

myButton.onclick = function() {
    setUserName();
}