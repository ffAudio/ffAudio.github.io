---
layout: page
title: Plugin Gui Magic
subtitle: PluginGuiMagic allows you to design your audio plugin GUI with mouseclicks at runtime
share-img: https://foleysfinest.com/img/EqualizerExample-og.png
---

PluginGuiMagic: A WYSWYG runtime design system for JUCE Plugins
---------------------------------------------------------------

JUCE is a framework, that allows to write cross platform audio applications and DAW Plugins.
Adding the foleys_plugin_magic module allows to have a generated UI, that can be edited at runtime using advanced layout and styling options.
It also adds visualisers to display signals, levels and spectra with no extra coding involved. 

NEW: PluginGuiMagic is from Version 1.4.0 licensed under the permissive BSD V3 3-clause license. That means it can be used in any project, including closed source and commercial products.

![FoleysSynth Screenshot](/img/FoleysSynth.png)

PluginGuiMagic is not just for prototyping, the layout, visualisations and styling can be used in the final product.

Features
--------

The module will display an editor panel attached outside of the ProcessorEditor you are editing. In three resizeable sections it displays the Components as tree structure (DOM), a property editor to adjust settings and colours in a CSS manor and a palette of available Components.
You can add your own bespoke Components without modifying the code to be available for the designer.

These are some of the already available Components:

- Slider
- ToggleButton, TextButton
- ComboBox
- Label
- XY-Dragger
- LevelMeter, Plot
- MidiKeyboardComponent
- WebBrowserComponent

And those Visualisers are already present:

- LevelMeter
- Oscilloscope
- Frequency Analyser
- IIR FrequencyResponsePlot

![Equalizer Screenshot](/img/EqualizerExample.png)

Documentation and support forum
-------------------------------

You find the API documentation here: [PluginGuiMagic (doxygen)]({{ site.baseurl }}/PluginGuiMagic/){:target="_blank"}

Support for PluginGuiMagic is available via the community driven [forum](https://forum.foleysfinest.com/c/pluginguimagic/). Please look around, sign up and ask questions, give feedback, report bugs, simply get in touch!

If you need personal assistance, this can only be given on a paid basis. Please write to [developer@foleysfinest.com](mailto:developer@foleysfinest.com) explaining your issue to get a quote.

Github repository - Downloading
-------------------------------

Find the module to add to your project here: [https://github.com/ffAudio/foleys_gui_magic](https://github.com/ffAudio/foleys_gui_magic/){:target="_blank"}
You will see a green download button labelled "Code". There are the URLs to clone the repository (recommended) or to download it as zip.

NEW in 1.4.0: The foleys_gui_magic repository contains the module in the folder modules. Just add the module in that subdirectory to your juce project.    
In the repository you will also find the examples in the Examples folder and unit tests in the Tests folder.



Licenses
--------

PluginGuiMagic is from Version 1.4.0 licensed under the permissive BSD V3 3-clause license. That means it can be used in any project, including closed source and commercial products.

**BSD 3-Clause License**

Copyright (c) 2019, Foleys Finest Audio - Daniel Walz
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.



Happy designing!

