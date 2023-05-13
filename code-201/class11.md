# Class 11 Notes

This reading covered video and audio content. Explaining all the different functions that can be added to these features a lot more than you would normally think about. It also explained how a grid is created and manipulated to place items. Finally I learned there was a way to accommodate for different screensize by simply providing a set of images in different sized best suited for different screens and using the browser to display the best fit.

Fallback content must be placed inside the video tags.

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
2. Describe the use of the src and controls attributes in the `<video>` element.
3. Why is it important to have fallback content inside the `<video>` element?
4. Write a very short story where `<audio>` and `<video>` are characters.

## Response

1. The ability to use video and audio has become more incluse with features like providing transcripts.
2. Src works the same way in videos as it does for images, creates a path to file. Controls are important to manipulate the start, stop, and adjust the volume.
3. Fallback content is important in case the video cannot be played. It can provide a link to the video making it more accessible to users with older browsers.
4. Audio and video are very similar. They are a great asset but not supported by every browser. Both use controls and both need a source.

## Guide to Grid

1. How does Grid layout differ from Flex?
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

## Responses

1. Grid layout builds a grid and positions based off numbering where flex makes adjustments based on the area available for parent element.
2. The grid container is like other containers in HTML, exception being that it uses a grid format. Grid lines help identify the lines in a grid based off numbering/naming. Grid item is the child of the parent (grid container) and is anything placed inside the grid.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
2. Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.
3. How is srcset more helpful for responsive images than CSS or JavaScript?

## Answers

1. There are other things to consider like resolution and bandwidth.
2. Attributes srcset and sizes are used to provide the browser additional images and hints as to which one to use.
**srcset** defines the set of images and size for each one. **Sizes** are set media conditions like screensize (helps provide 'hint' to browser).
3. It is more helpful because it provides alternative image sizes based on available screen size, there are multiple options instead of a fixed setting.

## Resources

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content>

<https://css-tricks.com/snippets/css/complete-guide-grid/>

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images>

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML>

<https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies>

## Things I want to know more about

How to look at view port sizes as opposed to pixels
