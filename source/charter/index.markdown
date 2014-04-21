---
layout: charter
title: "Project Charter and Other Good Stuff"
date: 2014-04-12 12:08
comments: true
sharing: true
footer: true
---

### A Brief Overview

Otto is your personalized, robot bartender. Simply send a drink order to Otto from your phone, tablet, or computer and the drink will be prepared otto-matically to your tastes.
<!--more-->
### Our Approach – Otto

Otto has three key components: the liquor, the mixers, and the glass. The liquor will be gravity fed and regulated via solenoids hooked up to the Arduino. The mixers are a little trickier since by and large they need to be refrigerated. To address this, we'll keep the mixers in a minifridge beneath the main unit (where they are also regulated by solenoids) and pumped upwards by a powerful peristaltic pump. The glass will ideally remain stationary and be fed by the appropriate tubes.

On the software side of things, the Arduino will be hooked up to a Raspberry Pi functioning as a server running node.js. Here we'll host a website that allows users to order their drinks and interface with Otto easily and conveniently.

The team members are Rustin Manafian, Chris Weller, and Ryne Chaloux. Everyone on the team is equally experienced in the skills required for this project, so the roles are fluid and adaptable. Individual ownership of various parts of the project can be determined as the need for it arises, but this project will be managed as a pseudo-flat organization.

### Objectives, Milestones and the "What" of Otto

Ideally by the end of our 10 week sprint, we'd like to have a deliverable, bar tending robot capable of making basic cocktails and getting you drunk for $500 or less. A rough outline of what this might entail on the production side of things would be to start by opening and closing the valves, get excited once we've figured out how to rig up all the mixers, and offer up a toast once our first shot's been poured.

Any potential long term goals would be centered around getting the user liquored up faster, cheaper, and in a more stylish way.

The primary deliverable would be...

__06/06/14__ Otto, the project we've been rambling on about.

We will all be held equally responsible for this.

### Constraints, Risk and Feasibility, and Other Excuses

Seeing as none of us have taken on a hardware project of this stature, simply learning all the necessary components of circuit design and implementation is one such risk taken with this project. However, after a cursory search when we came up with the project (and now further in, having been entrenched in hardware design for the past 3 weeks), we have determined that while ambitious, this project is feasible.

Other potential stumbling blocks include lack of viable suppliers or back ordered supplies, tight budgets, design issues such as where and how to mount what, and various things of that nature. Thankfully we've already mitigated most of these concerns. We've set a soft budge we've all agreed upon of roughly $500, we've bought and sourced parts from local suppliers, and we're actively consulting people with light years more experience than us in the food safe hardware field.

##Group Management

**What are the major roles in your group’s management?**

There are no management roles. Everybody is as much in charge as everybody else. We strive to be a flatly organized team.

**How will decisions be made? By leader, consensus?**

Decisions will be made by consensus. An odd number ensures tie breaking, and if anyone's on the fence, [Random.org](http://random.org) is here to save the day.

**How will you communicate? Email, meetings in the lab, discussion board?**

We will communicate through Google Hangouts and texting on top of meeting in person once or more a week as needed. We're all guaranteed to be on campus at various times throughout the week, and we've set up a Google Calendar that reflects this.

**How will you know when you’re off schedule, and how will you deal with schedule slips?**

Seeings as our milestones are laid out already, it's fairly negligible for us to check against them in our weekly meetings. If we aren't actively making progress on any one milestone from week to week, we'll know we've got a problem. Should we have schedule slips, we'll deal with them on a case by case basis.

But realistically, if Otto isn't working as we'd hoped by when we'd hoped, we'll just retroactively edit our schedule so that we can be back on schedule.

**Who is responsible for which deliverables and milestones?**

Everybody is equally responsible. Everyone in the group is expected to volunteer to work towards finishing the project.

**Who will produce the weekly group status reports?**
Probably Rustin. He has the best handwriting.

##Project Development

**What are the development roles and who will handle them?**
There are no specific roles. Everyone on the team will volunteer to do whatever needs to get done.

**What hardware/software will you use? What do you have available? What do you need?**

We need an Arduino, Raspberry Pi, various solenoid valves, peristaltic pump, resistors, transistors, diodes, LEDs, a power supply, a mini fridge, connecting tubing and hardware, and probably some more stuff that we'll figure out later. This is all subject to change.

**If there is software/hardware that is needed, provide a justification for its cost. Where will you order it? When will it arrive?**

This hardware is necessary because without it we can't build Otto. We've already ordered and received most of it. A lot of stuff is available in San Diego. All of it is available from America to shorten shipping times and reduce lead content.

**How will you do testing?**

By getting very drunk.

**How will you do documentation?**

By getting very drunk.

##Project Schedule

**1** &nbsp;Open/close solenoid (Completed! - April 11th)<br>
**2** &nbsp;Connect solenoid to bottle (~~Expected - April 19~~) (Completed! - April 20th)<br>
**3** &nbsp;Consistently dispense one ounce (~~Expected - April 20~~) (Completed! - April 20th)<br>
**4** &nbsp;Rig up all 6 liquor solenoids (Expected - April 25)<br>
**5** &nbsp;Dispense from multiple sources into glass (Expected - April 26)<br>
**6** &nbsp;LEDs up in this bitch (Expected - April 26)<br>
**7** &nbsp;Run peristaltic pump with just one mixer (Expected - May 1)<br>
**8** &nbsp;Extend pump setup with 6 mixers and their respective solenoids (Expected - May 3)<br>
**9** &nbsp;More LEDs (Expected - May 3)<br>
**10** Mount everything (Expected - May 21)<br>
**11** Make an AMF (our benchmark drink) (Expected - May 30)<br>
**12** Make it pretty (optional) (Expected - June 4)<br>

These steps are ordered by both priority and logical ordering. The way this project is structured, it doesn't exactly lend itself to specific key and sub milestones. All are necessary and integral to delivering the promised tangible aside from the adornment of LED's and making it pretty, and the sub tasks are so minute (ie soldering wires) that their inclusion would defeat the purposes of an abstracted, at-a-glance calendar.
