# Unify
Unify transmits audio from one computer to another wirelessly, like an invisible line-in audio jack. It supports a more seamless workflow across multiple, indepenent computers.

### To use it to share audio:
1. [Download](http://www.jeffblack.info/demos/Unify.zip) and unzip Unify on the machine you want to send from and the machine you want to send to.
2. Download and install a virtual audio cable on the machine you want to send audio from
    * I recommend https://www.vb-audio.com/Cable/
3. Route any audio you want sent to the virtual audio cable
    * This can be done using window's Sound Mixer Options page
4. Open Unify on the machine you want to send audio from
    * This is done by going into the Unify folder and opening the file Unify.exe
5. Select the audio device to stream from.
    * For our purposes, this will be CABLE Output (VB-Audio Virtual Cable)
6. Press start under the Send Audio section
7. Open Unify on the machine you want to receive audio on
8. On the receiving machine, enter the ip address and port that are shown on the sending machine's Unify app
9. Press start under the Receive Audio section
10. Enjoy wireless audio :)

Motivation for the project: I find myself in situations where I'm using my laptop and desktop at the same time. I would like to be able to link them together so I can share a single keyboard, mouse, and set of audio equipment. I use Synergy to share my keyboard and mouse inputs, you can use Synergy and Unify in tandem to achieve the same thing.

![unify_sender](https://user-images.githubusercontent.com/45664302/210140607-5ab44395-5f7f-49bd-920e-89e7899ecb7c.png)

![unify_receiver](https://user-images.githubusercontent.com/45664302/210140609-b4ff0d90-93a9-422e-b23b-c1275afd1f09.png)
