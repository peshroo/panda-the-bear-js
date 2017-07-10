1. Panda the Bear is lying about their skills! Take the "time travel" skill off the page to satisfy your personal sense of justice. We'll remove it using removeChild().

var parent = document.querySelectorAll('.bar-default')[2];
var child = document.querySelector(#time-travel);
parent.removeChild(child);

1. That drawing of Pikachu is really cute. Let’s duplicate it using cloneNode() and insert it at the bottom of the .portfolio-container using insertAdjacentHTML() or appendChild().

var picture = document.querySelector('div#right-image.portfolio-image img')
var portfolioContain = document.querySelector('div.portfolio-container')
portfolioContain.appendChild(pikatchu.cloneNode())

2. Wow, that was so satisfying I think we should do it 10 more times. Use a for loop to help you do this.

for (i = 0; i < 10; i++) { portfolio.appendChild(pikatchu.cloneNode());}

3. Let’s add a message about when the page was last updated. We'll do this by appending a new <li> element to the <ul> in the sidebar (you might need to refresh the page to bring back the list items that we emptied out earlier).

var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);

var addListItem = document.createElement('li');
var bioTitle = document.createElement('span')
bioTitle.innerText = "Date Last Updated"
bioTitle.className = "bio-title"
var bioInfoDate = document.createElement('span');
bioInfoDate.innerHTML = Date();
bioInfoDate.className = "bio-date-info"
addListItem.appendChild(bioTitle)
addListItem.appendChild(bioInfoDate)
document.querySelector('ul.bio-info').appendChild(addListItem)
