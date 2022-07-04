# Video and Audio Content

1. Web developers have wanted to use video and audio on the Web for a long time, ever since the early 2000s when we started to have bandwidth fast enough to support any kind of video (video files are much larger than text or even images.) In the early days, native web technologies such as HTML didn't have the ability to embed video and audio on the Web, so proprietary (or plugin-based) technologies like Flash — and later, Silverlight (both of which are now obsolete) — became popular for handling such content. This kind of technology worked OK, but it had a number of problems, including not working well with HTML/CSS features, security issues, and accessibility issues.

2. **src**: In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the      same way.
   **controls**: Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the      controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the          interface must include a way to start and stop the media, and to adjust the volume.
   
3. Fallback content is displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older            browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way          regardless of what browser they are using.
  
# A Complete Guide to Grid
  
1. Grid lays items out in a set grid that you can size while Flex lays items out in relation to one another
  
2. Grid Container: The element on which display: grid is applied. It’s the direct parent of all the grid items
   Grid Item: The children (i.e. direct descendants) of the grid container
   Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”)    and reside on either side of a row or column
  
# Responsive Images
  
1. This allows images to adjust as the browser moves or has its size adjusted
  
2. img: the element that contains an image link
   srcset: defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated      from the previous one by a comma
   sizes: defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are      true
  
3. When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's      CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to      implement solutions like srcset. For example, you couldn't load the <img> element, then detect the viewport width with JavaScript, and then dynamically    change the source image to a smaller one if desired. By then, the original image would already have been loaded, and you would load the small image as      well, which is even worse in responsive image terms.







