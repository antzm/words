# Words

## Learning words

### Learning new words from English to another language and vice versa.

This app helps you to learn new words in any language you would like to.  

The app contains only a few sample words, but it can be easily expanded to include the words of your choice, in the languages of your choice.  

The app was initially build in order to help Greek students to learn English words. For this reason, the app contains two arrays with English-Greek words. As the app can be easily customized in the languages of your choice, it also includes an array with French-English word and an array with French-Greek words.

Also, included is a sample array to demonstrate the proper syntax in order to create an array of words in the languages of your choice.

## Background information

This web-app is built using HTML, CSS and JavaScript. Usually, the code is separated in different files but for simplicity, the complete code has been included in a single HTML file, where there are sections for the CSS and the JavaScript code.

This has the advantage that the file can be easily edited, used and shared, as it is a single file without any dependencies. If downloaded, it will work without internet connection.

If used through a web-page, an internet connection will only be needed to initially access the web-app, while after that, there is no need for an internet connection, as the web-app does not access the internet at any point because all the data needed are stored inside the single file.

## Editing the included words

The web-app contains a few sample words but it's very easy to edit this information and include your own words. If you are familiar with JavaScript, the process is obvious, but even if you don't know anything about programming, it would be very easy to update this information.  

First though, you will need to know a few basic things on JavaScript arrays, as all the words are stored in arrays.  

In JavaScript, an array is simply a collection of data. To make an array, you declare it using the statement "const" and you give it a name and then you include your data, separated by commas, inside square brackets. At the end of the array, you add a semicolon ";" e.g.:

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

Arrays could also contain strings. In such a case, the strings have to be included inside quotes. Either double "double quotes" or single 'single quotes'. Single quotes are usually preffered, as they make the array easier to be read by people.

Here's an example:

const myArray = ['one', 'two', 'three', 'four', 'five'];

or

const myArray = ["one", "two", "three", "four", "five"];  


Arrays could also contain a combination of numbers and strings:

const myArray = ['one', 2, 'three', 4, 'five'];

## Word Arrays

This web-app uses arrays to store the foreign words and their meanings.

For simplicity and readability, each line holds only one foreign word and next to it, the meaning or the meanings of that word.

e.g. in the following array we can see a few French words and their translation to English with one or more words:

const myWords = [  
	['bateau', 'boat', 'ship'],  
	['soleil', 'sun', 'sunlight'],  
	['voyage', 'trip', 'journey'],  
	['merci', 'thanks', 'thank you'],  
	['bon', 'good', 'right', 'kind'],  
	['salut', 'hi', 'hello', 'bye'],  
	['nouveau', 'new', 'fresh'],  
	['école', 'school'],  
	['gentil', 'kind', 'good', 'nice'],  
	['professeur', 'teacher', 'professor']  
];  

So, following this conversion, it's rally easy to create new arrays with words.

## Customizing the web-app's interface

The simple interface is in English and if you are comfortable with coding, you could easily change it to your own language. Even though if you have no experience at all with coding, you can easily change the selection on the top, for either "English words" or "Greek Words" to your own preferences.

To do that, simply go to the place of the HTML code where those phrases appear, and replace the text with the languages of your choice.

![screenshot with the code for the radio buttons for selecting English or Greek words](imgs/radio-buttons.PNG)

As you can see in the above image, you only need to replace the white text (English words, Greek words) with the text of own choice.
