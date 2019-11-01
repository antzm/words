# words

## Learning words

### Learning new words from English to another language and vice versa.

This app helps you to learn new words in any language you would like to.  

The app contains only a few sample words, but it can be easily expanded to include the words of your choise, in the languages of your choice.  

The app was initially build in order to help Greek students to learn English words. For this reason, the app contains two arrays with English-Greek words. As the app can be easily customized in the languages of your choice, it also includes an array with French-English word and an array with French-Greek words.

Also, included is a sample array to demonstrate the proper syntax in order to create an array of words in the languages of your choice.

## Background information

This web-app is built using HTML, CSS and JavaScript. Usually, the code is separated in diffentt files but for simplicity, the complete code has been included in a single HTML file, where there are sections for the CSS and the JavaScript code.

This has the advantage that the file can be easily edited, used and shared, as it is a single file without any dependencies. If downloaded, it will work without internet connection.

If used through a web-page, an internet connection will only be needed to initially acces the web-app, while after that, there is no need for an internet connection, as the web-app does not access the internet at any point because all the data needed are stored inside the single file.

## Editing the included words

The web-app contains a few sample words but it's very easy to edit this inforamtion and include your own words. If you are familiar with JavaScript, the process is obvious, but even if you don't know anything about programming, it would be very easy to update this information.  

First though, you will need to know a few basic things on JavaScript arrays, as all the words are stored in arrays.  

In JavaScript, an array is simply a collection of data. To make an array, you declare it using the statement "const" and you give it a name and then you include your data, seperated by commas, inside square brackets. At the end of the array, you add a semicolon ";" e.g.:

const myArray = [1, 2, 3, 4, 5];

Each of those numbers 1, 2, 3, 4 and 5 is called an item of the array. Those items can be various things, besides numbers.  

For example, they can be other arrays like:

const myArray = [1, [10, 12, 24], 3, [15, 215, 26], 5];

or

const myArray = [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12], [13, 14, 14]];

which could also be written (for better readability) as:

const myArray = [
	[1, 2, 3], 
	[4, 5, 6], 
	[7, 8, 9], 
	[10, 11, 12], 
	[13, 14, 14]
];

Arrays could also contain strings. In such a case, the strings have to be included inside quotes. Either double "double quotes" or single 'single quotes'. Single quotes are usually prefered, as they make the array easier to be read by people.

Here's an example:

const myArray = ['one', 'two', 'three', 'four', 'five'];

or 

const myArray = ["one", "two", "three", "four", "five"];  


Arrays could also contain a combination of numbers and strings:

const myArray = ['one', 2, 'three', 4, 'five'];

