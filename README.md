# HTML-CSS
Anitha

WHAT IS HTML?

The coding that organizes a web page's content is called HTML (HyperText Markup Language). Content could be organized, for instance, using pictures and data tables, a series of paragraphs, or a list of bulleted points.
HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on. 
The main parts of our element are as follows:
1.	The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
2.	The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
3.	The content: This is the content of the element, which in this case, is just text.
4.	The element: The opening tag, the closing tag, and the content together comprise the element.

Nesting elements

•	You can put elements inside other elements too — this is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a <strong> element, which means that the word is to be strongly emphasized:
•	HTMLCopy to Clipboard
•	<p>My cat is <strong>very</strong> grumpy. </p>
•	You do however need to make sure that your elements are properly nested. In the example above, we opened the <p> element first, then the <strong> element; therefore, we have to close the <strong> element first, then the <p> element. The following is incorrect:
•	HTMLCopy to Clipboard
•	<p>My cat is <strong>very grumpy. </p></strong>
•	The elements must open and close correctly so that they are clearly inside or outside one another. If they overlap as shown above, then your web browser will try to make the best guess at what you were trying to say, which can lead to unexpected results. So don't do it!
•	<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However, these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
•	<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.
•	<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
•	<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this, and it can help avoid some problems later on.
•	<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
•	<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
•	<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

HTML Headlines
•	HTML provides six levels of headlines <h1> to <h6> with <h1> being the largest and <h6> being the smallest.


Unit 5: Working with Graphics and Images
Images

We use the img attribute when dealing with Images in HTML, as we know that the web will be very dull without images. 
There are four attributes that need to be included for every image:
1. The source attribute (SRC), which instructs the browser which image file to load, comes first. 
2. The image's text description is provided via the alt attribute (ALT). 
3. The width and height properties are the last ones that control the image's size. All four of these qualities should therefore be present in every image.

Images are one of the most common types of media used in web design.
To display an image on a webpage, you use the <img> tag with the src attribute to specify the URL or file path of the image.
Example: <img src="image.jpg" alt="Description of image">

Unit 6: HTML working with Media
Working with media in HTML involves incorporating various types of multimedia content, such as images, audios, videos and other interactive elements into webpages.
Here's a breakdown of how media can be integrated into HTML:

Audio:

HTML introduced the <audio> tag for embedding audio content directly into webpages.
. You can specify the source of the audio file using the src attribute.
. Additional attributes like controls, autoplay, loop, and preload control the playback behavior of the audio.
. Example: <audio src="audio.mp3" controls></audio>

Video:

. Similar to audio, HTML5 provides the <video> tag for embedding video content.
. You can specify multiple video sources using the <source> tag nested inside the <video> tag. This allows the browser to choose the best-supported format.
. Attributes like controls, autoplay, loop, preload, width, and height can be used to control the video's appearance and behavior.

Working with Captions and Subtitles:
Although adding audio and video to a website is incredibly fantastic, not everyone can hear or understand it. Some people may have intermittent hearing loss or have trouble understanding content because of a variety of different conditions while others may be deaf. It's not always convenient for individuals who are able to hear to listen. 
In that way, it's important to add captions and subtitles to audio or video content in HTML.

1. Use the <track> element inside <audio> or <video> tags.
2. Specify the source of the caption or subtitle file using the "src" attribute.
3. Use the "kind" attribute to define the type of text track. e.g captions / subtitles.
4. Include 'src lang' to specify the language and 'label' for user friendly description.
5. Caption and subtitle files are typically in web format
6. Ensure accuracy, synchronization, and readability for accessibility.
7. Test across browsers and deuces for compability and accessibility.

Embedding media via Iframes:
Refers to taking content from one site and placing it within the middle of another's site page. 
HTML provides other tags and methods for embedding media such as <iframe> for embedding external web content, <embed> for embedding plugins like Flash, and <object> for embedding multimedia objects.
Example:
<iframe src= "https: //www.youtube.com/embed/VIDEO_ID" width="560" height="315" frameborder="0" allowfullscreen>
</iframe>

Unit 7: HTML Content Identification
Involves uniquely identifying elements in HTML.
It is done using 'id' attribute for individual identifying and 'class' for grouping.

HTML Language support:
Supports multiple languages in content using 'lang' attribute.
Helps indicating the language used in the content for accessibility and search engine optimization.

HTML Generic elements:
Generic elements like div and span are used for content structuring in HTML.
They have no inherent meaning and are styled or scripted as needed. 
Div: It is used for division or sectioning a document.
Span: Used for applying styles to inline elements or groupingn inline elemnets for scripting purposes.

Unit 8: HTML Integration

