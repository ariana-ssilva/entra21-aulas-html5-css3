# 🎞️ Media, CSS introduction 🎨

##  `<audio>` tag
The `<audio>` tag is an inline element that is used to embed sound files into a web page. It is a useful tag if you want to add audio such as songs, interviews, etc. on your webpage.

Syntax:
```html
<audio>
  <source src="sample.mp3" type="audio/mpeg">
</audio>
```
<br>

> Attributes: The various attributes that can be used with the `<audio>` tag are listed below:
> * Controls: Designates what controls to display with the audio player.
> * Autoplay: Designates that the audio file will play immediately after it loads controls.
> * Loop: Designates that the audio file should continuously repeat.
> * src: Designates the URL of the audio file.
> * muted: Designates that the audio file should be muted.

<br>

##  `<video>` tag
The HTML5 `<video>` element specifies a standard way to embed a video on a web page. 

Syntax:
```html
 <video src="" controls>   </video>
```
<br>

> Attributes that can be used with the “video” tag are listed below :
> * Autoplay: It tells the browser to immediately start downloading the video and play it as soon as it can.
> * Preload: It intends to provide a hint to the browser about what the author thinks will lead to the best user experience.
> * Loop: It tells the browser to automatically loop the video.
> * height: It sets the height of the video in CSS pixels.
> * width: It sets the width of the video in CSS pixels.
> * Controls: It shows the default video controls like play, pause, volume, etc.
> * Muted: It mutes the audio from the video.
> * Poster: It loads an image to preview before the loading of the video.
> * src: It is used to specify the URL of the video file.

<br>

##  `<iframe>` tag
The `<iframe>` tag specifies an inline frame.
An inline frame is used to embed another document within the current HTML document.

Example :
```html
<iframe src="error.jpg" width="30%" height="30%"></iframe>
```

Output:
 <iframe src="error.jpg" width="30%" height="30%"></iframe>
<br>

# CSS Introduction

## Style selector
Can be added on the html `<head>`. The instructions will affect just this document.

Example: 
```html
<style>
body{
color:red;
}
</style>
```

<br>

## Link selector
Can be imported on the html `<head>`. The instructions will affect the documents that also imported the file.

Example: 
```html
<link rel="stylesheet" href="style.css">
```

<br>

## Style attribute
The style attribute specifies an inline style for an element.
> The style attribute will override any style set globally, e.g. styles specified in the `<style>` tag or in an external style sheet.
Example: 
```html
<p style="color:red; border:1x solid black;">styled</p>
```

<br>

## .class Selector
The `.class` selector selects elements with a specific class attribute.

>To select elements with a specific class, write a period (.)` character, followed by the name of the class.


Example: 
```html
.class {
  css declarations;
}
```

<br>

## #id Selector
The `#id` selector styles the element with the specified id.


Example: 
```html
#id {
  css declarations;
}
```

<br>







