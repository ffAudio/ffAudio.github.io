---
layout: page
title: Plugin Gui Magic
subtitle: PluginGuiMagic allow you to design you audio plugin GUI with mouseclicks at runtime
fastspring: foleysfinest.onfastspring.com/popup-foleysfinest
share-img: https://foleysfinest.com/img/EqualizerExample-og.png
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

PluginGuiMagic is free to use for non-commercial projects under the BSD-V2 (3 clause) license, see [License](/files/PluginGuiMagic-license-document.pdf){:target="_blank"}

If you are selling plugins or applications using *foleys_gui_magic*, you are required to buy a license. 

The commercial license is per developer/designer who works on the project(s):

<div style="display:flex; flex-direction:row">
<div style="product">
<h3>Annual</h3>

119.00 USD (*)<br/> 
equals 9.92 USD per month<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-annual">Buy</a>
</div>

<div style="text-align:center">
<h3>Half year</h3>

69.00 USD (*)<br/>
equals 11.50 USD per month<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-halfyear">Buy</a>
</div>

<div style="text-align:center">
<h3>Quarterly</h3>

39.00 USD (*)<br/>
equals 13.00 USD per month<br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-quarterly">Buy</a>
</div>

<div style="text-align:center">
<h3>Perpetual</h3>

339.00 USD (*)<br/><br/>

<a href='#' data-fsc-action="Add,Checkout" data-fsc-item-path-value="pluginguimagic-perpetual-license">Buy</a>
</div>
</div>

(*) You will see the local price with the applicable VAT added when you click on the buy link (you can still cancel)    
(**) The licenses are sold via [Fastspring](https://fastspring.com/){:target="_blank"}

The full code is publicly available, please test before buying a license!

Documentation and support forum
-------------------------------

You find the API documentation here: [PluginGuiMagic (doxygen)]({{ site.baseurl }}/PluginGuiMagic/){:target="_blank"}

Support for PluginGuiMagic is available via the community driven [forum](https://forum.foleysfinest.com/c/pluginguimagic/). Please look around, sign up and ask questions, give feedback, report bugs, simply get in touch!

If you need personal assistance, this can only be given on a paid basis. Please write to [developer@foleysfinest.com](mailto:developer@foleysfinest.com) explaining your issue to get a quote.

Github repository - Downloading
-------------------------------

Find the module to add to your project here: [https://github.com/ffAudio/foleys_gui_magic](https://github.com/ffAudio/foleys_gui_magic/){:target="_blank"}
You will see a green download button labelled "Code". There are the URLs to clone the repository (recommended) or to download it as zip.
Make sure the folder has the right filename `foleys_gui_magic`, some clients append a suffix like the branchname, which will stop Projucer from recognising the module.

There is also a repository containing several example projects to get an idea from: [https://github.com/ffAudio/PluginGuiMagic/](https://github.com/ffAudio/PluginGuiMagic/)
To clone use the `--recurse-submodules` flag:
```
git clone --recurse-submodules https://github.com/ffAudio/PluginGuiMagic.git
```

Happy designing!

