---
layout: page
title: Developer Resources
---

## Open Source

On our [github page](https://github.com/ffAudio/){:target="_blank"} there are a variety of open source resources, like metering components or an analyser.
We also have some little or sometimes bigger snippets, that we used to get a better understanding of the JUCE API. This is, how the open source [Frequalizer Free](https://github.com/ffAudio/Frequalizer/){:target="_blank"} came to life.

### ff_meters

![ff_meters](/img/meters_screenshot.png){:style="float: right;margin-right: 7px;margin-top: 7px; width: 25%"}

The `ff_meters` module is a free to use module to be used with the JUCE classes for audio. The whole painting can be adapted to your needs, in terms of colours and layout.

This component fits into audio processing, it measures peak and RMS values and offers a Component to display a meter in a thread safe way.

This project is published under the BSD 3-clause license, so it is free to use in your projects at no charge.

- [ff_meters API]({{ site.baseurl }}/ff_meters/)
- [ff_meters github](https://github.com/ffAudio/ff_meters/)

### ffLayouts

The layouts module allows to layout subcomponents according to a nested tree in horizontal and vertical lines. It allows margins around components, different stretch factors and text descriptions for components or groups, without the need to write code, once the updateGeometry() hook is added to the resized() method.

The ffLayouts has an unfinished editor. It is planned to move to a new, more complete layout engine, allowing CSS methods like grid and flexbox.

- [ffLayouts API]({{ site.baseurl }}/ffLayouts/)
- [ffLayouts github](https://github.com/ffAudio/ffLayouts/)

## Further projects

We start now to add more advanced engines and offer these on a dual licensing, for open source/private and commercial use. Stay tuned!

## JUCE

For our developments we use most of the times [JUCE](https://juce.com){:target="_blank"}, since it works best for our audio applications and plugins.
While developing, we often face pieces, that we need so often, that we create a reusable solution and publish it. We believe in an exchange between professionals, so we can learn from each other.

