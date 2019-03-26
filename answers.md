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
