1.  Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.

var image = document.querySelector('img');
image.src = "images/self-portrait-snowbg.jpg"

1. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

var leftImage = document.querySelector('#left-image img')
leftImage.src = "images/pikachu-drawing.jpg"

2. Select the heading that says "Panda the Bear" and change it to your own name.

var heading = document.querySelector('h1')
heading.innerText = "Roopesh";

3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

var employment = document.querySelector('#employment h3');
employment.innerText = 'Jobs';

4. Change the colour of the body.

var body = document.querySelector('body');
body.style.color = 'blue'

5. Change the colour used by the highlight class.

var highlight = document.getElementsByClassName('highlight');
$(".highlight").css ('color' , 'red');

6. Change the font family of the h1 to 'monospace'.

var font = document.querySelector('h1');
font.style.fontFamily = "monospace";

7. Find a way to select the round icons in the sidebar and then change their colour.

var roundIcon = document.querySelectorAll('.action-icon-bg');
roundIcon.forEach(function(item) { item.style.backgroundColor = 'blue' })

8. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".

var textInput = document.querySelectorAll('input[placeholder = "Name"]');
textInput[0].placeholder = "Identify Yourself"

9. Change the placeholder attribute of the message field to "state your business".

var textArea = document.querySelectorAll('textarea[placeholder = "Message"]');
textArea[0].placeholder = "State Your Business"

10. Give the name field a "value" attribute of "your nemesis".

var nameField = document.querySelector('input[type = "text"]');
nameField.value = "Your Nemesis";

11. Change the value attribute of the email field to "koalathebear@gmail.com".

var emailField = document.querySelector('input[type = "email"]');
emailField.value = "koalathebear@gmail.com"

12. Change the value of the submit button on the contact form to "En garde!".

var submitButton = document.querySelector('input[type = "submit"]');
submitButton.value = "En garde";

13. We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).

var submitButton = document.querySelector('input[type = "submit"]');
submitButton.disabled = "Disabled!"

14. We should help Panda protect their privacy by clearing their personal details from the sidebar. You can use reset() to do this.

var form = document.querySelector("form");
form.reset();
