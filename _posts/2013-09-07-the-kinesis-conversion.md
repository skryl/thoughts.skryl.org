---
layout: post
title: The Kinesis Conversion
tags:
  - keyboards
  - typing
redirect_from:
  - /post/60613686455/the-kinesis-conversion
  - /post/60613686455
---

I recently decided to undertake yet another keyboard modification project. You may be familiar with the popular [Kinesis Advantage](https://deskthority.net/wiki/Kinesis_Advantage) ergonomic keyboard. Yes, the one with the crazy contoured shape. Well, mine has been lying dormant in the back of the closet for months due to the fact that I hate the feel of the Cherry Brown switches which it ships with from the factory (you can get it with Cherry Reds also but I do not like them either). Having taken a peek inside the case of the Advantage, a potential switch swap (to Cherry Blues) did not appear too difficult, so I finally made the move to order some parts and do the swap.

To figure out what parts I needed for the swap I simply called tech support and asked. The support guy I spoke to was extremely helpful. He told me exactly what I would need to do the switch swap and made the order for me. It came out to around $14 total and he even threw in a free set of blue home row key caps! This was probably the best tech support experience I have ever had.

<!--more-->

### The parts list

- 68 new Cherry Blue switches - This is the most expensive part of the swap. Unless you can get a better deal, these run around $1 per switch.
- 68 small diodes - $1 total
- Left and Right PCB - $7 each
- Left and Right plastic key support - Free
- Left and Right thumb cluster PCB and ribbon cable - Free


### Tools you will need

- Phillips screwdriver
- Soldering iron and an optional desoldering iron (or desoldering braid)

### The Process

Once you have all the parts, begin by unscrewing the bottom of the Kinesis shell and seperate the two halves by unplugging the USB controller cable from the main PCB.

![Process 1]({{ "/assets/images/20130907/04.jpg" | absolute_url }})

You can pull out the main key wells by unplugging the white ribbon cable and removing 3 screws from each side.

![Process 2]({{ "/assets/images/20130907/02.jpg" | absolute_url }})

Notice that the switches in the key wells are first mounted inside the plastic support and only then soldered onto the flexible PCB. Do the same when building the replacement key wells by inserting all the switches into the plastic support before doing any soldering.

![Process 3]({{ "/assets/images/20130907/03.jpg" | absolute_url }})

Make sure all the switch housings are snapped into the support and none of the switches are crooked or rotated incorrectly (see photos).

![Process 4]({{ "/assets/images/20130907/05.jpg" | absolute_url }})

Starting with the switches at the bottom of the finger strips, solder each one to the PCB going up the strip (You may need to remove the bottom most switches temporarily to make it easier to align the PCB as I have done in the photo).

![Process 5]({{ "/assets/images/20130907/06.jpg" | absolute_url }})

Once all the switches have been soldered to the PCB you will need to add small diodes to the bottom of each switch with the black stripe facing left. These diodes are not visible on the stock PCBs since they are built into the stock Cherry switches (your switches most likely do not include the diodes).

![Process 6]({{ "/assets/images/20130907/07.jpg" | absolute_url }})

The diodes are oriented the same way on both the left and right PCBs.

![Process 7]({{ "/assets/images/20130907/09.jpg" | absolute_url }})

Once all the diodes are in place you are done with one key well. Now repeat the above steps for the other side.

![Process 8]({{ "/assets/images/20130907/10.jpg" | absolute_url }})

Because the thumb cluster keys are PCB mounted (with no supports), there are two ways to swap their switches. One way is to simply rebuild each thumb cluster from spare parts like we did with the key wells. The other (possibly quicker) way is to pop off the key caps and take apart each switch, replacing the insides with those of the replacement switches. Because I had the parts and the time I decided to build each cluster from parts.

![Process 9]({{ "/assets/images/20130907/12.jpg" | absolute_url }})

Building the thumb clusters is fairly self explanatory. Insert and solder all the switches. Then add the diodes and the ribbon cables and you are done.

The tricky part is removal of the old thumb clusters. It requires the removal of the main PCB (a single screw in the middle) and desoldering the thumb cluster ribbon cables. (A $15 desoldering iron from Radio Shack will make your life much easier)

![Process 10]({{ "/assets/images/20130907/15.jpg" | absolute_url }})

Replace the old thumb clusters with the new ones, re-attach the main PCB and re-assemble the main key wells. You are officially done with the swap, but before putting everything back together make sure to connect the keyboard to a computer and test each key individually to confirm that it works (using a tool like KeyCodes for OSX).

![Process 11]({{ "/assets/images/20130907/19.jpg" | absolute_url }})

The swap takes a couple of hours and is well worth it if you prefer the feel of the Cherry Blue switches.

{% include share.html %}