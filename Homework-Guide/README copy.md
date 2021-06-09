# Homework-1
<p>HW-1 Refactoring Code to make it meet accessibility standards. </p>
<p>At line 11 I switched the first div to the header  and did the same to their closing tags. </p>
<p>At line 13 the div tag was replaced by nav as it has the code to the navigation bar on the page. The css was affected by this change so the same needed to be done on lines 27, 35, 39.</p>
<p>At line 27, I wrapped the div tag with a section tag.
<p> At line 28 the div tag was replaced with the more descriptive main tag. This change had no affect on the CSS </p>
<p> At line 29 the class needed to be switched to and ID in order for the user to be sent to Search Engine Optimizebutton section of the page after clicking the button. Lines 137, 110, 122 on CSS needed to be turned the </p>
<p></p>
<p>Images on lines 30,37,44,54,61 and 68 were given the alt attribute.</p>
<p>The opening and closing div tag at line 52 was changed into an aside html semantic.</p>
<p>The opening and closing div tag line 74 was changed to the footer tag. </p>
<p> The changes made in the css were made because the styling did no match the flow of the html page. I switched the css styling so the styling for the main tag of the html showed up before the aside css styling elements. Comments were added to make clear what styling the styling was doing and for what html element. </p>
<p>In the CSS I was able to consolidate the code from 3 css styling elements to one by using  ".content h2" to style the H2's using their parent class of .content. I was able to do the same with their img styling,since they all have the same value size of 200px and the styling of the box elements in the main tag. The same was done for the class of benefits to style the images using the parent tag, instead of the three classess individually. I also used the parent class of benefits to code CSS for the H3 headings. </p>