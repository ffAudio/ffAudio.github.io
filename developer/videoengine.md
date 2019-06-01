---
layout: page
title: Video Engine
---

We present a video engine to implement video playback, editing and writing with JUCE
------------------------------------------------------------------------------------

JUCE is a framework, that allows to write cross platform audio applications. To make it possible to create applications, where you can edit audio AND video in the same environment, we created an engine, that reads video files, allows creating video generators, playing back and writing videos.

The engine offers a range of classes, that represent audio visual media. The classes are: 

- AVMovieClip: a movie read from a file like mp4, mov or other
- ImageClip: a still image
- AudioClip: an audio from a file with no images
- ComposedClip: This renders a sequence of other clips together

Inside a ComposedClip, each included clip goes through processing, where you can add audio plugins and Video effects, such as pan&zoom, colour adjustments etc.
This is extensible, so you can write your own video effects as well.

Features available
------------------

We will add features as we go, these are the ones, that are already finished:

- Reading of video files, video and audio synchronous
- Normalise different sample rates and frame rates
- Compositing of multiple videos or still images in layers (paint on top)
- Alpha blending of clips to create different transitions
- Audio plugins for clips
- Automatable parameters for video composition
- Video plugins for image processing / colour adjustments etc.

The rendering is done in software to be independent from any hardware constraints. We plan somewhere in the future to add hardware accellerated processing.

![VideoEditor Screenshot](/img/VideoEditor.png)

Licenses
--------

The engine is available for licensing. The code is published under the GPL-3 License and under a commercial license. That allows you to either use the code in your own GPL projects, or you can get a commercial license.

We offer different commercial packages:

### Personal License

- Available to individuals with yearly fundings of less than 50 tsd. US-Dollar in total
- Also available for educational institutions like schools and universities
- Mandatory Splashscreen "powered by _Foleys Finest Audio_"
- Mandatory user counter
- Free of charge, no minimum comittment

### Small Business License

- Available for companies with yearly fundings of less than 200 tsd. US-Dollar in total
- 40 US-Dollar (excl. VAT) per month and developer
- billed quarterly, cancellation possible after 12 months
- No splashscreen
- No user counter

### Enterprise License

- For companies or teams with more than 200 tsd. US-Dollar total yearly fundings
- No splashscreen
- No user counter
- _Get in touch for a quote_

Documentation
-------------

You find the API documantation here: [foleys_video_engine]({{ site.baseurl }}/foleys_video_engine/)\\
The sources of the engine are available via [github - ffAudio](https://github.com/ffAudio/foleys_video_engine/)\\
We provide also a repository with a few demo programs ready to build: [Example sources](https://github.com/ffAudio/VideoExamples/)

