h1 to h6  will add headers of different sizes.

p is used to start a new paragraph.

a is used to add anchors.
The target attribute will determine where the page will open.
The default value is _self which will open the page in the same window.
_blank will open the page in a new window.
The title attribute will add a tooltip which will appear when you hover over the hyperlink.

img is used to add images.
The src attribute is used to add the image source. This could be a local file in a folder or an image url.
The alt attribute is used to add alternet text so that people using a screen reader can get an idea about the image. Its good practice to add them.
The height and width attribute will change the height and the width of the image. If only one of the is used, the other will chage proportionally. If both of them are used, then the image will ignore the original aspect ratio and resize according to the values.

audio tag is used add play audio files.
The src attribute is used to add the audio source.
Then there are these boolean attributes. They dont need any value, they just need to exist.
controls will add the audio player with controls for the user.
autoplay will play the audio automatically when the page is loaded.
muted will mute the player by default.
loop will loop the audio.
Multiple source tags containing different file formats can be nested inside the audio tag as backup just in case a browser does not support a perticuler file format.

video tag is almost the same as audio tag.
height and width works width video tag.

Text formatting is used to add some basic styles to some text.
b tag will make text inside that bold.
strong tag will also make text inside that bold, strong is used to mark important text.
i tag will make text inside that italic.
em tag will make text inside that bigger, i.e. emphasized.
marked tag will make text inside that highlited.
small tag will make text inside that small.
del tag will make text inside that crossed off.
ins tag will make text inside that underlined.
sub tag will make text inside that a subscript.
sup tag will make text inside that a superscript.

ul will make an unordered list. This will contain some li tags and the text will be in those li or list item tags. Each li represents a item in the list. 

ol is the same as ul.
In this case the attribute type will chage the way the list items are counted. It can be decimals, roman numbers, alphabet etc.

dl creates a description list. In this list, a list item is a pair of dt or description titles and dd or description definitions.
The definitions will be offset from the starting.

Lists can be nested in other lists.

table tag adds tabeles. tr or table row adds a row for the table.
th adds table headings.
td adds table data.
Each tr or td will created a new column for them.

th and td can have colspan attribute which is used to marge 2 or more cells in the table.

span is used to seperate a small portion of text to apply styles to it.
div adds a division in the page.
There are better ways to divide a page using simantic tags like article, header, main etc.

meta is a self closing tag.
meta contains data for the browser or the search engine.

iframe tag embedds other webpages in the page.
A lot of websites disables the use of iframes for security reasons.
Mainly used for ads.
YouTube videos are embedded using iframes in websites.

button tag adds button.
disabled is a boolean attribute to make the button disabled and unclickable.

form adds a form in the page. It can contain various inputs like name, passwords, buttons, radio, dropdown, email etc.
They can be linked with a label tag by changing the labels for attribute to the same as the elements id.
required is a boolean attribute that prevents the user from submitting the form without filling a perticuler field.
maxlength adds a charecter limit to text inputs.
placeholder attribute adds placeholder text in the field.
radio inputs must have same value under the name attribute to function as intended (only one can be selected).