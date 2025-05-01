```
Qun. What is Media tags ?

Ans: HTML5 introduced 5 most popular media element tags i.e.<img> <audio>, <video>, <source>, <embed>, <track>. These media element tags changed the entire development using HTML.

*** some Media Tag ***

1.<img> tag:- HTML img tag is used to display image on the web page. HTML img tag is an empty tag that contains attributes only, closing tags are not used in HTML image element.

Syntax of <img> tag:
<img src= "url"> 


2.<audio> tag:- The <audio> tag is used to embed sound content in a document, such as music or other audio streams.
-> The <audio> tag contains one or more <source> tags with different audio sources. The browser will choose the first source it supports.
-> The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element.
-> There are three supported audio formats in HTML: MP3, WAV, and OGG.

Attributes of Audio tag:-

1.autoplay:-Specifies that the audio will start playing as soon as it is ready
2.controls:-Specifies that audio controls should be displayed (such as a play/pause button etc)
3.loop:-	Specifies that the audio will start over again, every time it is finished
4.muted:-	Specifies that the audio output should be muted
5.preload:- Specifies if and how the author thinks the audio should be loaded when the page loads
6.src:- 	URL	Specifies the URL of the audio file

Example
Play a sound file:
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>


3.<video> tag:- The <video> tag is used to embed video content in a document, such as a movie clip or other video streams.
-> The <video> tag contains one or more <source> tags with different video sources. The browser will choose the first source it supports.
-> The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.
->There are three supported video formats in HTML: MP4, WebM, and OGG.

Attributes of Video tag:-

autoplay	Specifies that the video will start playing as soon as it is ready
controls	Specifies that video controls should be displayed (such as a play/pause button etc).
height		Sets the height of the video player
loop		Specifies that the video will start over again, every time it is finished
muted		Specifies that the audio output of the video should be muted
poster		Specifies an image to be shown while the video is downloading, or until the user hits the play button
preload:-	Specifies if and how the author thinks the video should be loaded when the page loads
src	:-      Specifies the URL of the video file
width:- 	Sets the width of the video player.

Example:- Play a video

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>

4.<Iframe> Tag </Iframe> :- HTML Iframe is used to display a nested webpage (a webpage within a webpage). The HTML <iframe> tag defines an inline frame, hence it is also called as an Inline frame.
-> An HTML iframe embeds another document within the current HTML document in the rectangular region.
-> The webpage content and iframe contents can interact with each other using JavaScript.

Iframe Syntax
An HTML iframe is defined with the <iframe> tag:

<iframe src="URL"></iframe>  
Here, "src" attribute specifies the web address (URL) of the inline frame page.


 