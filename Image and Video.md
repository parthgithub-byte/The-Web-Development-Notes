***1] Image tag***
:

The image tag is primarily used for two purposes:
- Informative purpose: It means, the image is a primary source of information to be delivered by the content. It may be given with text or captions to elaborate it further and may be presented as a self explaining entity on the web page.
- Decorative purpose: In modern times, different formats of imges are used to make the webpages look attractive, interactive and modest. It may contain backgrounds, logos, animations, gifs, png images, etc.

The `<img>` tag contains of the two main attributes: `src=''` and `alt=''`.
The source tag mentions the source of the image. It can be in a computer directory or a website attributed to the image.
The alternative tag mentions the substitute text to be displayed on the screen when the image cannnot be loaded (network issue or inaccessible source).
The `<img`> tag is a self closing tag and ideally written as `<img/>`.

Eg of the image tag: `<img src="Pokemon.png" alt="Pokemon" />` Displays: <img src="Pokemon.png" alt="Pokemon" />
Now above file will be displayed as it is in the directory.
To show a distant server server file, use the link to the image.
Eg: `<img src="https://static.wikia.nocookie.net/pokemon/images/f/f3/Ho-oh_%28MS020%29.png/" alt="Pokemon" >` 
Displays: <img src="https://static.wikia.nocookie.net/pokemon/images/f/f3/Ho-oh_%28MS020%29.png/" alt="Pokemon" >

**Other attributes**
- To resize the image in terms of pixels, we can use the height and pixel attributes:
Eg: `<img src="Pokemon.png" alt="Pokemon" height="400" width="600" >` 
Displays
<img src="Pokemon.png" alt="Pokemon" height="400" width="600" >
However, we see that, resizing both height and width almost always distorts the aspect ratio. We can resize the image with any of one parameter and the aspect ratio is preserved.

Eg: `<img src="Pokemon.png" alt="Pokemon" width="600px" >` 
Displays
<img src="Pokemon.png" alt="Pokemon" width="600px" >

- Image Title: Like for most other elements, mentioning the value of the title="" attribute gives additioal on the image. Hower on the image to see it.
Eg: `<img src="Pokemon.png" alt="Pokemon" width="600px" title="Ho-Oh Legendary pokemon">` shows it like:

![Image](imagetitle.png)