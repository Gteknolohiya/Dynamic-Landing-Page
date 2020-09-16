README v1.0 / 16 SEPTEMBER 2020

# Dynamic-Landing-Page

## Introduction

Dynamic landing page is a webpage where you can set your name and the task that you are going to do for the day. It also show what time it is.

## Usage
You just need to put your name and your task for today. 

## How to create it?
1. First, create a placeholder for time, greeting, name, and focus and style it using CSS.
2. Create DOM elements. Create a function that show the time(function showTime()). 
3. Create variable that have "new Date()" method. Then use this variable to get the hour(today.getHours()), minutes(today.getMinutes()), and seconds(today.getSeconds()). 
4. Next, create a variable that holds the condition that set if it is PM or AM(const amPm = hour >= 12 ? 'PM' : 'AM';). 
5. Make it a 12hr format(hour = hour % 12 || 12;).
6. Create options whether you show the AM-PM or not. (const showAmPm = true;)
7. Create a new function that put zero to the time.(function addZero(n))
8. Output the time in the html. (time.innerHTML)
9. Create function that set background and greeting. (function setBgGreet())
10. Create function that get the name from the local storage. (function getName())
11. Create a function that set the name to the local storage. (function setName(e))
12. Create function that get the focus from the local storage. (function getFocus())
13. Create a function that set the focus to the local storage. (function setFocus(e))
14. Create event listener that if you click enter button or click anywhere in the background, the name and focus will save to your local storage.
15. Run the functions.


## Important Notes
- new Date() method is used to set the date.
- .getHours() method is used to get the hour.
- .getMinutes() method is used to get the mins.
- .getSeconds() method is used to get the secs.
- To make the time a 12 hr format, use this: hour = hour % 12 || 12;
- setTimeout() method is used to set the timeout of the function.
- parseInt() method converts string to an integer.
- localStorage.getItem() get the item from the local storage.
- localStorage.setItem() set the item to the local storage.
- 'Keypress' in event listener is used if you want to enter a key.
- 'Blur' in event listener is used if you want to enter anywhere.

 
## Contributing

To contribute in this project, just contact me on my fb page Gteknolohiya or email me at gteknolohiya@gmail.com.

## Help

If you have some questions, just message me on my fb page.

### Requirements

There's no specific requirements.

### Installation

Go to https://gteknolohiya.github.io/Dynamic-Landing-Page

### Configuration

N/A

## Credits

Credits to Traversy Media for the tutorial of this app.

## Contact

FB page: https://facebook.com/gteknolohiya
Email: gteknolohiya@gmail.com

## License

N/A
