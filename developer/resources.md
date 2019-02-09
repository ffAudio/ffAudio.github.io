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

To measuere a stream a single line of code is sufficient:

```
void processBlock (AudioSampleBuffer& buffer, MidiBuffer&) override
{
    meterSource.measureBlock (buffer);
    // ...
}
```

- [ff_meters API]({{ site.baseurl }}/ff_meters/)
- [ff_meters github](https://github.com/ffAudio/ff_meters/)

## Further projects

We start now to add more advanced engines and offer these on a dual licensing, for open source/private and commercial use. Stay tuned!

## JUCE

For our developments we use most of the times [JUCE](https://juce.com){:target="_blank"}, since it works best for our audio applications and plugins.
While developing, we often face pieces, that we need so often, that we create a reusable solution and publish it. We believe in an exchange between professionals, so we can learn from each other.

