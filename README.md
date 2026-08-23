# Experimental-Study-of-Buck-and-Jones-Converters
Experimental study of **thyristor choppers**, focusing on the **Jones chopper** and its forced commutation. The project analyzes waveforms with R-L loads, the effects of inductance and switching frequency on current ripple, and the sizing of chopper components.
<h3>Objectives</h3>

<ul>
  <li>Observe the waveforms for an <strong>R-L load</strong>.</li>
  <li>Study the effect of the <strong>smoothing inductor</strong> and switching frequency on load current ripple.</li>
  <li>Determine the appropriate ratings of the <strong>thyristor chopper components</strong>.</li>
</ul>
<h3>Theoretical Background</h3>

<h4>1. Buck Converter and Jones Converters </h4>

<ul>
  <li>
    <strong>t<sub>on</sub></strong>: conduction time of the chopper switch H.
  </li>
  <li>
    <strong>T</strong>: chopper switching period.
  </li>
  <li>
    <strong>&alpha;</strong>: duty cycle, defined as
    <strong>&alpha; = t<sub>on</sub>/T</strong>, with
    <strong>0 &lt; &alpha; &lt; 1</strong>.
  </li>
</ul>
<h4>Buck Converter</h4>
<p align="center">
  <img src="Buck_converter.png"
       alt="Buck Converter"
       width="700">
</p>

<h4>Jones Converter</h4>
<p align="center">
  <img src="jones_converter_1.png"
       alt="Jones Converter"
       width="700">
</p>
<p align="center">
  <img src="jones_converter_2.png"
       alt="Jones Converter Second Configuration"
       width="700">
</p>
