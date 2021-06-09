# Homework-1
HW-1 Refactoring Code
## Name of Assignment
Homework-1 
## Purpose
In HW-1 I was asked to refactor the code to make it meet accessibility standards. I was also asked to consolidate the CSS if I saw it necessary.  
## My Experience
After reading many html articles on semantic html, I was able to read the starter code and immedialety see the changes needed to occur.
Understanding the benefits of having semantic tags in html helped me understand why these changes are needed. Semantic html allows screen readers to read through 
code more easily and for search engines to optimize the page appropriately. 
## Changes Made to the original code
At line 11 I switched the first div to the header  and did the same to their closing tags. 
At line 13 the div tag was replaced by nav as it has the code to the navigation bar on the page. The css was affected by this change so the same needed to be done on lines 27, 35, 39.
At line 27, I wrapped the div tag with a section tag.
At line 28 the div tag was replaced with the more descriptive main tag. This change had no affect on the CSS 
 At line 29 the class needed to be switched to and ID in order for the user to be sent to Search Engine Optimize button section of the page after clicking the button. 
Lines 83, 110, 122 on CSS needed the "." to be turned into a "#" since it the attribute was switched to an id.
Images on lines 30,37,44,54,61 and 68 were given the alt attribute.
The opening and closing div tag at line 52 was changed into an aside html semantic.
The opening and closing div tag line 74 was changed to the footer tag. 
The changes made in the css were made because the styling did no match the flow of the html page. I switched the css styling so the styling for the main tag of the html showed up before the aside css styling elements. 
Comments were added to make clear what styling the styling was doing and for what html element.
In the CSS I was able to consolidate the code from 3 css styling elements to one by using  ".content h2" to style the H2's using their parent class of .content. I was able to do the same with their img styling,since they all have the same value size of 200px and the styling of the box elements in the main tag. The same was done for the class of benefits to style the images using the parent tag, instead of the three classess individually. I also used the parent class of benefits to code CSS for the H3 headings.
## Link to the app
https://janetiqal.github.io/Homework-1/
## Screen shots of working application
First half of broswer
<img width="1439" alt="Screen Shot 2021-06-06 at 4 29 38 PM" src="https://user-images.githubusercontent.com/84414488/120940758-7c964c80-c6e4-11eb-9487-e6ec511004f6.png">
Second half of brower
<img width="1439" alt="Screen Shot 2021-06-06 at 4 27 30 PM" src="https://user-images.githubusercontent.com/84414488/120940686-1ad5e280-c6e4-11eb-8e3b-c40263e6d245.png">

## Created by
Janet Iqal
