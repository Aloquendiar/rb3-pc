---
title: Nintendo Wii Guitar Hero Les Paul Guitars (Raphnet)
sidebar: controllers_sidebar
permalink: ctrls_ghraphgtr_wii
folder: instruments
tags: [wii, guitars, english]
summary: "How to setup Nintendo Wii Les Pauls on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/wii.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/wiilpcontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* **Tilt is busted on this controller!**
    * It's suggested to mod your guitar into a wired one with a solution like [[RetroCultMods' Solderless DIY RGB Kit]](https://www.etsy.com/listing/1505287559/solderless-diy-rgb-kit-for-guitar-hero){:target="_blank"}.
* This was tested with a Raphnet "Classic controller to USB adapter".
	* If the controller doesn't work at all, try installing [[Raphnet's management tool]](https://www.raphnet-tech.com/products/adapter_manager/index.php){:target="_blank"}.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://rb3pc.milohax.org/ctrls#gamepads){:target="_blank"}.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I map my guitar?</a>
                            </h4>
                        </div>
                        <div id="how-to-map-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Click on the Pads icon at the top of RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>It’s suggested to create a new configuration by clicking <code>Add Configuration</code> at the top right of the <code>Pads</code> window.<br>
This is so you can change configuration profiles in case you want to play games that don’t use instruments.<br>
<img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/padlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping the Rock Band Hofner"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## Pad Information

| Handlers | Devices |
|:--------:|:-------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Guitar Hero |

## Mappings

**UNMAP THE FOLLOWING** or guitar solos will auto-strum!  
Use Right Click to unmap a button.

| **RPCS3** | **Guitar** |
|:--------:|:-----------:|
| L2 | Solo Modifier |

**Map** the following:

* Guitar Hero controllers tend to misbehave and **refuse to map sometimes. If you try mapping a button and always get "U+" or something similar, click "Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

| **RPCS3**          | **Controller** |
|:------------------:|:---------------------:|
| Cross | ![Green Fret](https://rb3pc.milohax.org/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://rb3pc.milohax.org/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Yellow Fret](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Blue Fret](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](https://rb3pc.milohax.org/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://rb3pc.milohax.org/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://rb3pc.milohax.org/images/btns/gtrs/sbd.png "Strumbar Down") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Whammy Bar") |
| Start | ![Plus](https://rb3pc.milohax.org/images/btns/ctrls/wii/plu.png "Plus") |
| Select | ![Minus](https://rb3pc.milohax.org/images/btns/ctrls/wii/min.png "Minus") |
| PS Button | ![Home](https://rb3pc.milohax.org/images/btns/gtrs/home.png "Home") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20Guitar%20(Raphnet).7z){:target="_blank"}

<!-- Profile Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-use-profiles">How do I use profiles?</a>
                            </h4>
                        </div>
                        <div id="how-to-use-profiles" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>This is not recommended if you're using multiple controllers at once. </b> {{include.content}}</div>
<p>After downloading the profile,</p>
<ol>
<li>Extract the .7z file.</li>
<li>Drag the <code>input configs</code> folder into the <code>configs</code> folder where you have RPCS3 in.</li>
</ol>
<p><img src="https://rb3pc.milohax.org/images/instruments/instrepoinstall.gif" alt="A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder." title="Installing a configuration from the Instrument Repo"></p>
<p>After that, you can select the profile in the <strong>“Pads”</strong> menu.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofile.png" alt="A screenshot of RPCS3's Gamepad Settings, showing the cursor over a profile." title="Gamepad Settings"></p>
<p>Most of the time, these controller profiles should work out of the box. If they don’t, try changing the controller listed in “<code>Devices</code>”, next to the “<code>Refresh</code>” button until it receives an input. You can edit this while the game is running.</p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Profiles End -->

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrwiilpmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Mapped by [[GamerPerson22]](https://www.youtube.com/channel/UCC5SlXPlnlGwBG7w6mvfx8g){:target="_blank"}