# Technical-Take-Home-Challenge
Universal Color Translator
# Features
<li>Color Name Input: Enter the name of a color.</li>
<li>Hex Code Output: Displays the hex code for the given color.</li>
<li>Error Handling: Shows appropriate messages if the input is blank or if the color is not found in the predefined list.</li>

# Coding Languages used
HTML, CSS and Javascript
<li>HTML: structure of the webpage</li>
<li>CSS: styling and layout of the page</li>
<li>Javascript: Functionality of variables and to handle input and output</li>

# Project Setup
1. Open the HTML file
<li>Open 'index.htm' in your web browser or you can also download the raw file on the top right corner</li>

# Code explanation

<li>colorToHex: A var created to map color names to their respective hex codes</li>
<li>getHexCode: A Function that retrieves user input from the text field </li>
<li>The .value.trim() line removes leading and trailing whitesapce and retrives the current value of an input field , if this line was not added, an error message would appear "The color [object HTMLInputElement] was not found"</li>
<li>The .toLowerCase() line allows the color name input to be case-insensitive so that users can type "Red", "RED", or any other variation.</li>
<li>innerHTML is used to retrieve to string of id="result" </li>
<li>Checks if the input is empty and shows an error message if so</li>
<li>Looks up the hex code in the variable colorToHex to display the result or an error message if the color is not found</li>

# How to use 
1. Enter color name : Red, Green, Blue
2. Click the Get hex code button
3. View result
<li>The hex code will display below the button</li>
<li>If the input is blank or the color is not found, an error message will be shown</li>
   




