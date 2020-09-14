---
layout: page
title: Plugin Gui Magic
fastspring: foleysfinest.onfastspring.com/popup-foleysfinest
---

PluginGuiMagic: A WYSWYG runtime design system for JUCE Plugins
---------------------------------------------------------------

JUCE is a framework, that allows to write cross platform audio applications and DAW Plugins.
Adding the foleys_plugin_magic module allows to have a generated UI, that can be edited at runtime using advanced layout and styling options.
It also adds visualisers to display signals, levels and spectra with no extra coding involved. 

![FoleysSynth Screenshot](/img/FoleysSynth.png)

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

Licenses
--------

PluginGuiMagic is free to use for non-commercial projects under the BSD-V2 (3 clause) license, see [License](https://github.com/ffAudio/foleys_gui_magic/blob/master/LICENSE.md)

If you are selling plugins or applications using *foleys_gui_magic*, you are required to buy a license. The selling page will be online soon, meanwhile please get in touch with [daniel@foleysfinest.com](mailto:daniel@foleysfinest.com?Subject=PluginGuiMagic%20License)

The commercial license is per developer/designer who works on the project(s):

### Annual license

119.00 USD (*)    
equals 9.92 USD per month    
for one developer or designer

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-annual">Buy an annual license</a>

### Half year license

69.00 USD (*)    
equals 11.50 USD per month    
for one developer or designer

### Quarterly license

39.00 USD (*)    
equals 13.00 USD per month    
for one developer or designer


* Prices don't include VAT


Documentation
-------------

You find the API documantation here: [PluginGuiMagic (doxygen)]({{ site.baseurl }}/PluginGuiMagic/)

Github repository
-----------------

Find the module to add to your project here: [https://github.com/ffAudio/foleys_gui_magic](https://github.com/ffAudio/foleys_gui_magic/)

There is also a repository containing several example projects to get an idea from: [https://github.com/ffAudio/PluginGuiMagic/](https://github.com/ffAudio/PluginGuiMagic/)
To clone use the `--recurse-submodules` flag:
```
git clone --recurse-submodules https://github.com/ffAudio/PluginGuiMagic.git
```

