---
layout: posts
title: Electronic Wind Instrument - Pasokhene
discription: Another return of mouth organ - modulating the powersupply
categories: Instrunment
tags: electronics 
inlink1: 
inlink1Title: 
exlink1: 
exlink1Title: 

---


## New Idea and Lorre-Mill residency

I was in Baltimore for the weekend for a short short residency at the home of double-knot, Lorre-Mill. Will agreed to help me and work together on a new idea we have been talking about for few months on the design of the electronc mouth organ. We built a entirely new prototype to try out the idea. Our agenda was this:

1. Simplify and adjust the breath sencor opamp circuit
2. Try LM13700 for VCA
3. Power supply modulation with LM317

The big idea to try was this, modulating the powersupply with the oscilator - which is powered by the modulated powersupply. Will this loop of ripple produce some compeling effect on the output? 


---

## The flute and internal pressure

The acoustic flute make sounds in a folloing way described in this nice Yamaha website here --> [how the flutes work](https://www.yamaha.com/en/musical_instrument_guide/flute/mechanism/mechanism002.html). 

1. the breath cuts the air to inside of the flute and outside of the flute, creating the vibration 
2. Air that goes into flute will increse the pressure, traveling down to the end of the tube, and bounce back, and try to come out of the origin. 
3. This decrease the pressure of the section of the tube, lets the air in more 4) and so on

So this idea of reverbration of internal pressure resulting in tone, can we simulate something similar idea electrically on the centikhene? Can we modulate the entire powersuply by it's own sound that is being produced? It is not a simulation of how flute works but rather taking the idea of reverbration of internal pressure producing an effect. In this case not the air pressure but voltages. 

<div class="dataimage">
	<img src="/assets/img/idea.svg">
</div>



## Connectors! 

Since moving my studio, I have gotten rid of many of my materials and tools. One of the things I forgot about is the usfulness of the connectors. Will has helped me put together some connectors with ribbon cables to make the prototyping process easier. It is a simple and ovious things but I have forgotten that by taking little extra time to make the prototype "nice" it chnages the prototyping experience and process alot more flexible for further experimentations. 

Also using connectors to stack the boards, and connecting horizontally also techniques I have forgotten. This is prompting me to think of prototyping process in modules. 


<div class="dataimage">
	<img src="/assets/img/block_diagram.svg">
</div>

## LM13700 for VCA 

In previouse iteration, I was controlling the amplitude of the oscilators with diodes, which turned out to be little noizy and somewhat unstable. Now Will introduced me to use [LM13700 Dual Operational TransConductance Amplifiers](https://www.ti.com/product/LM13700) for a Voltage Controled Amplifier. 


<div class="dataimage">
	<img src="/assets/img/lm13700.png">
</div>




## Power supply modulation with LM317 adjustable voltage regulator











