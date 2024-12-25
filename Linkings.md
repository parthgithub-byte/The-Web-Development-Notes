**Linkings**
In HTML, linking refers to creating connection between various sources such as web pages, files, or external resources.
This is primarily done using the `<a>` tag for hyperlinks and `<link>` or `<script>` for other rsource linking.
---
***Using the `<a>` tag:***
The anchor tag `<a>` is used to create clickable links that direct direct users to other webpages, sections, files or actions.
*Syntax:*  

`<a href`=`"URL`>Link test `</a>`
Eg:  
`<a href`=`"https://www.google.com"` >Click to search `</a>`  
Displays as:  <a href`="https://www.google.com" >Click to search </a>

***Types of links:***  
- 1. Internal links: Link to another page in the same website (or another page on the directory):
Eg: In our case, let's just link to another one of the html page in our repo.
`<a` href="Lists.html">Click to see the types of lists.`</a>` displays:  [Click to see the types of lists.](Lists.html)  
This also means that we can link a text to an internal file in our system or repository.
Eg. `<a` href="Lists.md">Click to learn about lists in detail.`</a>` i.e. <a href="Lists.md">Click to learn about lists in detail.</a>  
or <a href="Pokemon.png">Pokemon!</a>  

- 2. External links: Similar to internal linking, by pasting the hyperlink of a website, we can link to a remote page or file. Eg: `<a` `href="https://www.pw.live">`India's most affordable and quality learning platform`</a>` displays:  
<a href="https://www.pw.live">India's most affordable and quality learning platform</a>

Now, in both the above cases, on clicking the links, the page is opened in the same tab, but for better user experience it's good to open the links in the new tab. This can be achieved by using the target attribute set to "_blank" value. By default target is set to the "_self" value, i.e. the linked page opens in the same tab.  
Eg: `<a` `href="https://www.pw.live"` `target="_blank">`India's most affordable and quality learning platform`</a>` displays: <a href="https://www.pw.live" target="_blank">India's most affordable and quality learning platform</a>.

- 3. Linking to the mails: The syntax to linking a text to "compose mai to an email address is as: `<a` href="mailto:emailid@xyz.com">Alternate text`</a>`  
Eg: <a href="mailto:orgjee@iitk.ac.in">Contact For queries`</a>` is displayed as<a href="mailto:orgjee@iitk.ac.in">Contact For queries</a>  

- 4. Phone Call links on supported devices: Eg: `<a` href="tel:108">Call for medical emergency`</a>` Displays:  <a href="tel:108">Call for medical emergency</a>

- 5. File links: We have seen that we can access the local files directly using linking, but one can actually directly download the downloadable files. Syntax: `<a` href="/file/path" `download`>Download File`</a>`. Now, lets' see how to download the above opened Pokemon picture.  
`<a` href="Pokemon.png" download>Pokemon.png`</a>` displays as:  
<a href="Pokemon.png" download>Pokemon.png</a>  

Thus, we just have to add the download attribute in the `<a>` tag to download the internal files in the system instead of just navigating them.



