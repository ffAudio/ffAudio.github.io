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

If you are selling plugins or applications using *foleys_gui_magic*, you are required to buy a license. 

**Save 20% introduction offer on annual and perpetual licenses! Use the code FOLEYS-WEBSITE-2020 on checkout. Valid until 31.October 2020 (UTC)**


The commercial license is per developer/designer who works on the project(s):

<div style="display:flex; flex-direction:row">
<div>
<h3>Annual license</h3>

119.00 USD (*)<br/> 
equals 9.92 USD per month<br/>
per developer or designer<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-annual">Buy</a>
</div>

<div>
<h3>Half year license</h3>

69.00 USD (*)<br/>
equals 11.50 USD per month<br/>
per developer or designer<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-halfyear">Buy</a>
</div>

<div>
<h3>Quarterly license</h3>

39.00 USD (*)<br/>
equals 13.00 USD per month<br/>
per developer or designer<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-quarterly">Buy</a>
</div>

<div>
<h3>Perpetual license</h3>

339.00 USD (*)<br/>
per developer or designer<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-perpetual-license">Buy</a>
</div>
</div>

(*) You will see the local price with the applicable VAT added when you click on the buy link (you can still cancel)


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

