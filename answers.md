# Question 1A:
let profileImg = document.querySelector('.profile-image');
profileImg.src = 'https://static.turbosquid.com/Preview/000309/875/UJ/3d-panda-bamboo-bear_D.jpg';


# Question 1B:
let photographyImg = document.querySelector('.photography');
photographyImg.src = 'https://methods.sagepub.com/images/virtual/visual-research-methods/image46.jpg';


# Question 2:
let headerOne = document.querySelector('h1.highlight');
headerOne.innerText = 'Adam Weiler';


# Question 3:
let employmentHeader = document.querySelector('#employment h3.info-title');
employmentHeader.innerText = 'Something else';


# Question 4:
let ourBody = document.querySelector('body');
ourBody.style.backgroundColor = '#0F6A3F'


# Question 5:
let highlightClass = document.querySelectorAll('.highlight');

for (let x = 0; x < highlightClass.length; x++) {
    highlightClass[x].style.color = 'red';
}
    

# Question 6:
let headerOne = document.querySelector('h1.highlight');
headerOne.style.fontFamily = 'Monospace';


# Question 7:
let actionIcons = document.querySelectorAll('.action-icon-bg');

for (let x = 0; x < actionIcons.length; x++) {
    actionIcons[x].style.backgroundColor = '#006400';
}


# Question 8:
let formName = document.querySelector('#name');
formName.placeholder = 'Identify Yourself!';


# Question 9:
let formMessage = document.querySelector('#message');
formMessage.placeholder = 'State your Business!';


# Question 10:
let formName = document.querySelector('#name');
formName.value = 'Your Nemesis';


# Question 11:
let formEmail = document.querySelector('#email');
formEmail.value = 'koalathebear@gmail.com';


# Question 12:
let formButton = document.querySelector('#submit');
formButton.value = 'En Garde!';


# Question 13:
let formButton = document.querySelector('#submit');
formButton.disabled = true;


# Question 14:
let personalInfo = document.querySelectorAll('.bio-info-value');

for (let x = 0; x < personalInfo.length; x++) {
    personalInfo[x].innerText = '';
}
