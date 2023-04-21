# Getting started with Resolume

<div>

<figure><img src=".gitbook/assets/swirl_logo.gif" alt="Augmenta x Resolume"><figcaption><p>Example project using Augmenta in Resolume</p></figcaption></figure>

 

<figure><img src=".gitbook/assets/swirl_realLife.gif" alt=""><figcaption><p>Plugin Resolume used at an art residency in Thaîland</p></figcaption></figure>

</div>

## Resolume

[Resolume](https://resolume.com/) Arena is one of the reference tools in live performance and video installations for editing and publishing live images, vijing and video mapping. It allows you to create and play VJ sets and videomappings for scenic or architectural dressing and multimedia shows.

It's a very popular software that can get you to prototype or build interactive content in minutes without any coding skills, or nodals tools, just Resolume VJ skills !

## Video tutorial

{% embed url="https://youtu.be/Qzfy7O9xvTw" %}

This video shows how to open the example in Resolume and how to set up Augmenta Fusion to send data to it.

## Written tutorial

Prerequisites:

* Having [Resolume](https://resolume.com/) Arena 7+ installed on your computer
* Having [Augmenta simulator](https://augmenta.tech/downloads) installed on your computer

### Install

Download the Augmenta Resolume plugin [here](https://github.com/Augmenta-tech/Augmenta-Resolume/releases/latest)

Drag'n drop each effect into resolume and click on install

<figure><img src=".gitbook/assets/install_plugin.gif" alt=""><figcaption></figcaption></figure>

Activate OSC input

<figure><img src=".gitbook/assets/activate_OSC-input.gif" alt=""><figcaption></figcaption></figure>

### Use

**Note** : This is a beta feature, not yet available in the simulator, so we use Fusion instead

Start Fusion and setup your scene size and resolution

Add a Generator or "Add manually..." a source

If you have a manual source, set the local port to 12000, open the Augmenta Simulator and add the number of points you want

In Augmenta Fusion, add a Resolume output

<figure><img src=".gitbook/assets/output.gif" alt=""><figcaption></figcaption></figure>

⚠️ Start Resolume and **set your composition to the same resolution of Fusion**

<figure><img src=".gitbook/assets/compisition.gif" alt=""><figcaption></figcaption></figure>

Drag 'n drop Augmenta dots. Points should be moving !

<figure><img src=".gitbook/assets/simulator_Resolume.gif" alt=""><figcaption></figcaption></figure>

### Limitation

Augmenta Resolume effect currently supports a maximum of 20 tracked objects.

###
