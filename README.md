# HTML 5 Video &amp; Audio

HTML5 supports `<video>` and `<audio>` elements that can easily be embedded into HTML files.

`<video>`  
  `<source src="SampleVideo.mp4" type="video/mp4">`  
  `<source src="SampleVideo.ogv" type="video/ogv">`  
  Your browser does not support HTML5 video.  
`</video>`

`<audio>`  
`<source src="SampleSong.mp3" type="audio/mpeg">`  
`<p>Your browser does not support HTML5 audio.</p>`  
`</audio>`

### Video Attributes:
* controls: displays audio controls for playing sound
* autoplay: makes the audio play automatically on page load
* loop: makes the audio repeat automatically
* muted: mutes the audio in the video
* height: specify height of the video
* width: specify the width of the video

### Audio Attributes:
* controls: displays audio controls for playing sound
* autoplay: makes the audio play automatically on page load
* loop: makes the audio repeat automatically
* preload: used to buffer large files (can take 3 values: none, auto or metadata)
