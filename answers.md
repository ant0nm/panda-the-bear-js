# Part 1
* Question 1
```javascript
// get the profile image first
var profileImage = document.querySelector('.profile-image');
// change its src property
profileImage.src = "https://placebear.com/g/400/400";
```

* Question 2
```javascript
var photographyImage = document.querySelector('.photography');
photographyImage.src = "https://picsum.photos/325/225/?image=83";
```

* Question 3
```javascript
var mainHeading = document.querySelector('h1.highlight');
mainHeading.innerText = "Anton Moiseev";
```

* Question 4
```javascript
var employmentHeading = document.querySelector('#employment .info-title');
employmentHeading.innerHTML = '<i class="icon-suitcase"></i> &nbsp; Experience';
```

* Question 5
```javascript
document.body.style.background = 'grey';
```

* Question 6
```javascript
var highlightElements = document.querySelectorAll('.highlight');
highlightElements.forEach((element) => element.style.color = 'teal');
```

* Question 7
```javascript
var h1 = document.querySelector('h1');
h1.style.fontFamily = 'monospace';
```

* Question 8
```javascript
var sideBarIcons = document.querySelectorAll('.action-icon-bg');
sideBarIcons.forEach((icon) => icon.style.backgroundColor = "teal");
```

* Question 9
```javascript
var nameInput = document.querySelector('input#name');
nameInput.placeholder = 'identify yourself';
```

* Question 10
```javascript
var messageInput = document.querySelector('textarea');
messageInput.placeholder = 'state your business';
```

* Question 11
```javascript
var nameInput = document.querySelector('input#name');
nameInput.value = 'your nemesis';
```

* Question 12
```javascript
var emailInput = document.querySelector('input#email');
emailInput.value = 'koalathebear@gmail.com';
```

* Question 13
```javascript
var submitInput = document.querySelector('input#submit');
submitInput.value = 'En garde!';
```

* Question 14
```javascript
var submitInput = document.querySelector('input#submit');
submitInput.disabled = true;
```

* Question 15
```javascript
var sideBar = document.querySelector('aside');
var bioInfo = document.querySelector('.bio-info');
sideBar.removeChild(bioInfo);
```

# Part 2
* Question 1
```javascript
var timeTravelDiv = document.querySelector('div#time-travel');
timeTravelDiv.parentNode.parentNode.removeChild(timeTravelDiv.parentNode);
```

* Question 2
```javascript
var pikachuImage = document.querySelector('.portfolio-image#right-image img');
var dupPikachuImage = pikachuImage.cloneNode(true);
var portfolioContainer = document.querySelector('.portfolio-container');
portfolioContainer.appendChild(dupPikachuImage);
```

* Question 3
```javascript
let portfolioContainer = document.querySelector('.portfolio-container');
let pikachuImage = document.querySelector('.portfolio-image#right-image img');
for (let i = 1; i <= 10; i++) {
  let dupPikachuImage = pikachuImage.cloneNode(true);
  portfolioContainer.appendChild(dupPikachuImage);
}
```

* Question 4
```javascript
const listItem = document.createElement('li');
listItem.classList.add('bio-info-item');
const leftSpan = document.createElement('span');
leftSpan.classList.add('bio-info-title');
const rightSpan = document.createElement('span');
rightSpan.classList.add('bio-info-value');
rightSpan.classList.add('bio-info-time');
var lastUpdated = document.createTextNode('Page last updated on');
var dateTextNode = document.createTextNode(new Date());
leftSpan.appendChild(lastUpdated);
rightSpan.appendChild(dateTextNode);
listItem.appendChild(leftSpan);
listItem.appendChild(rightSpan);
var bioInfo = document.querySelector('.bio-info');
bioInfo.append(listItem);
```
