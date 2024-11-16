# Introduction to CSS

### What is CSS?

Cascading Style Sheets is the language we use to style and HTML Document. It describes how HTML elements should be displayed.

### An Interesting Anecdote from the PAST:

[Marc Andreessen](https://en.wikipedia.org/wiki/Marc_Andreessen) is the founder of Mosaic, he later founded Netscape and now the very famous venture capital firm Andreesen Horowitz. He once wrote in an email to someone that there is no way to format their HTML documents the way they would do it in MS Word.

### What is the [History of CSS](https://www.w3.org/Style/CSS20/history.html)?

Håkon Wium Lie proposed the 
In 1996 a new recommendation was proposed by the W3C which was led by [Håkon Wium Lie](https://en.wikipedia.org/wiki/H%C3%A5kon_Wium_Lie) who is known as the father of CSS. This recommendation allowed the programmers to attach style such as font colors and spacing to HTML documents. And this breakthrough allowed the developers to separate the styling from the content. It allowed the developers to have modularity.

The W3C consortium responded by releasing a new version of HTML, HTML 3.2 and this came out in 1997 which allowed new html tags such as the <font> that allowed the developers to define the font size, the color and the font face. However all the major updates that came up in HTML 3.2 is now deprecated, because it turned out to be a nightmare for the developers to work with HTML. As HTML was never intended to contain tags for formatting a web page. HTML was created to describe the content of a web page. The structure and the content of the websites really get cluttered and working with HTML used to be troublesome by using HTML 3.2 formatting elements.


### Ways to add CSS to an HTML Document:
1. Inline CSS: We can add CSS to any HTML element using the style attribute.However, this method of adding CSS isn't recommended as if we would want a couple of elements to share the same style we would need to manually go and change the style attribute for each one of the element which is definitely tedious.
2. Internal CSS: There's a special HTML tag by the name Style tag within which we can mention the selector of any HTML tag and then write the desired CSS within a block of curly braces which will make all specified elements share the mentioned CSS properties. However in case of a multi-page website using internal CSS isn't recommended. 
3. External CSS: In order to use an external css file we simply create a css file with the .css extension and then go about using the link tag to link our external css file with the required html files. In side the link tag we write two attributes one is the 'rel' attribute which stands for relationship and the second attribute is 'href' which mentions the path of the CSS file to import the designs and style from.

