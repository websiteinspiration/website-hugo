+++
title = "About Me"
date = "2020-04-30"
[ author ]
  name = "Jakub Duchniewicz"
+++

## Hi there!
My name is Jakub Duchniewicz and this is my personal space :) \
I am currently pursuing MSc in Embedded Systems at University of Turku, Finland as a part of EIT Digital Programme.

I have graduated from Warsaw University of Technology with the highest degree for my thesis: *"FPGA based hardware accelerator for musical synthesis for Linux system"*.

There will be (or already are) several posts dedicated to this topic: [Posts]. Feel free to comment on them, or drop me an email/DM me.

## What's in here?
On this website you can find some thoughts of mine on several topics ranging from:

* Microcontrollers and FPGA's 
* Game Engines 
* Machine Learning
* Linux and other OS's topics
* Systems Programming

Please feel free to reach out to me, or leave a comment, I am always eager to have a chat or give a helping hand!

## BSc Thesis:
### *"FPGA based hardware accelerator for musical synthesis for Linux system"*

You can view the .pdf [here].

**Abstract**: Work focuses on realizing audio synthesizer in a System on Chip, utilizing FPGA
hardware resources. The resulting sound can be polyphonic and can be played directly
by an analog connection and is returned to the Hard Processor System running Linux
OS. It covers aspects of sound synthesis in hardware and writing Linux Device Drivers
for communicating with the FPGA utilizing DMA. An optimal approach to synthesis is
researched and assessed and LUT-based interpolation is asserted as the best choice for
this project. A novel State Variable IIR Filter is implemented in Verilog and utilized. Four
waveforms are synthesized: sine, square, sawtooth and triangle, and their switching can
be done instantaneously. A sample mixer capable of spreading the overflowing amplitudes
in phase is implemented. Linux Device Driver conforming to the ALSA standard is written
and utilized as a soundcard capable of generating the sound of 24 bits precision at 96kHz
sampling speed in real time. The system is extended with a simple GPIO analog sound
output through 1 pin Sigma-Delta DAC.

**Keywords**: FPGA, Sound Synthesis, SoC, DMA, SVF

### Little bit more
Lately, I have been digging more into Machine Learning with [fastai], ultimately wanting to deploy my own models on microcontrollers/FPGA's, so expect some content on that soon'ish.

Moreover, I am intensively learning Rust, and I am engaged in development of Error handling guidelines, as well as, stabilizing some features related to it in the Rust language.

I am an active developer of [PolyEngine], and if you would like to join us don't hesitate! 
Currently it undergoes some restructurization and implementation of Editor and Vulkan rendering engine (we used OpenGL based one so far), so if you are specialized in either Qt or Vulkan -- we need you! (We welcome you anyway :heart:)

[PolyEngine]: https://github.com/PolyEngineTeam/PolyEngine/
[Posts]: https://jduchniewicz.com/posts/
[fastai]: https://course.fast.ai/
[here]: https://jduchniewicz.com/FPGA-synth.pdf
