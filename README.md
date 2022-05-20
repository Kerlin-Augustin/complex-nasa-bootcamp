# 🚀 Project: Complex NASA API

This project lets you see the geographical locations and weather of all the Nasa Facilities in the country.

**Link to project:** https://kerlinaugustin-complexnasa-api.netlify.app/

![nasaBuilding](https://user-images.githubusercontent.com/102834611/169624268-779e08e5-85c7-44ca-9991-0a433576542f.jpeg)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Framework of choice

I passed a weather api through a fetch method to get latitude and longitude data. I then put a create element method that created li's. Those li's would only be created for every nasa facility and location there are. Then I put those facilities and locations into the innerTest of the li's. I then used the latitude and longitude information I got to pass into the parameters of a ewather api that I had. This allowed me to find the weather of the NASA facilities.

## Optimizations

I'm actually really pump about finding that if you put the data I got from the first fetch API into a for loop and add a length property to the data and increment it by 1 it would go through every latitude and longitude for you allowing you not to have to find and list data value individually.

## Lessons Learned:

createElement method allows you to create elements in the DOM from Javascript.
