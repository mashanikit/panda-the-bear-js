1. var image = document.querySelector('img.profile-image');
image.src = "http://static.boredpanda.com/blog/wp-content/uploads/2016/07/fox-faces-roeselien-raimond-red-mr-fox.jpg";
"http://static.boredpanda.com/blog/wp-content/uploads/2016/07/fox-faces-roeselien-raimond-red-mr-fox.jpg"

2. var skyImage = document.querySelector('#left-image');
skyImage.src = "http://wallpapercave.com/wp/hZqKsuk.jpg";

1a. var image = document.querySelector('img') image.src = "https://placebear.com/400/400"

1b. var pic = document.querySelectorAll('#left-image.portfolio-image img') pic.src = "https://placebear.com/325/255"

var title = document.querySelector('h1') title.innerText = "Melina"

heading = document.querySelector('h1.highlight') heading.innerText = 'Melina'

var body = document.querySelector('body') body.style.color = "red"

var highlight = document.querySelector('.highlight') highlight.style.color = "blue"

var h1 = document.querySelector('h1') h1.style.fontFamily = "monospace"

var icon = document.querySelectorAll('.action-icon-bg') icon.style.backgroundColor = "purple"

changed one without All, couldn't change both (cannot set property

of undefined)

var el = document.querySelector('#name') el.setAttribute("placeholder", "identify yourself")

var msg = document.querySelector('#message') msg.setAttribute("placeholder", "state your business")

el.setAttribute("value", "your nemesis")

var mail = document.querySelector('#email') mail.setAttribute("value", "koalathebear@gmail.com")

var button = document.querySelector('#submit') button.setAttribute("value", "en garde!")

button.disabled = true;

var info = document.querySelector('form') info.reset();
