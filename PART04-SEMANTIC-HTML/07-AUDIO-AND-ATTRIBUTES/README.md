Audio and Attributes
====================

Now that we learned about text-based content, let us dig into `<audio>`! Surely everyone needs `<audio>`--- how else would you listen to your Korean hip hop?

The `<audio>` element is used to embed audio content into a document. Like `<video>`, `<audio>` uses `src` to link the audio source.
````html
<audio>
  <source src="iAmAnAudioFile.mp3" type="audio/mp3">
</audio>

````

In this example, we created an `<audio>` element. Then we created a `<source>` element to encapsulate our audio link. In this case, `iAmAnAudioFile.mp3` is our audio file. Then we specified the type by using `type` and named what kind of audio it is. Although not always necessary, it's recommended that we state the type of audio as it helps the browser identify it more easily and determine if that type of audio file is supported by the browser.

We linked our audio file into the browser but now we need to give it controls. This is where *attributes* come in. Attributes provide additional information about an element.

Attributes allow us to do many different things to our audio file. There are many attributes for `<audio>` but today we're going to be focusing on `controls` and `src`.

-   `controls`: automatically displays the audio controls into the browser such as play and mute.

-   `src`: specifies the URL of the audio file.

As you might have noticed, we already used the `src` attribute. Most attributes go in the opening tag of `<audio>`. For example, here's how we could add both autoplay functionality and audio controls:
````html
<audio autoplay controls>
````

You can find other attributes here: [Useful attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio#Attributes).

# Instructions

1. In the code editor, create an `<audio>` tag with the attribute `controls` directly under the commented line.

2. Add a source for the audio inside the `<audio>` tag by using this code:
`<source src="" type="audio/mp3">`
Use the following URL as the source for the audio:
`<https://codecademy-content.s3.amazonaws.com/courses/Semantic+HTML/dogBarking.mp3>`
