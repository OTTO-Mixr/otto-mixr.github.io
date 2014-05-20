---
layout: post
title: "The Story So Far Part 2: Final Milestone Update"
date: 2014-05-19 22:49:51 -0700
comments: true
categories: 
---

For the purposes of this report, we’ll be referring to our revised list of milestones. Throughout the quarter, our list of milestones has grown longer and longer to the point that the original list of milestones is comical. Additionally, some of our original milestones weren’t thought through very well. For example, some are in fact dependent on the whole project being done so they are redundant as milestones. For another example, consider the milestone we had of hooking up 6 solenoids. That milestone has building a mount as a prerequisite so it doesn’t make sense for that to be first. In short, we ended up changing a lot of dates to be more sane. And finally some of our milestones simply ended up being absorbed by others. So, without further ado here’s our current milestones:
<!--more-->
**Completed (Pictures/Video follows each set of milestones)**

Open/close solenoid (Completed! – April 11th)

Connect solenoid to bottle (Expected – April 19) (Completed! – April 20th)

Consistently dispense one ounce (Expected – April 20) (Completed! – April 20th)
<div class='embed-container'>
<iframe src="//www.youtube.com/embed/liqCEJRP9Pk" frameborder="0" allowfullscreen></iframe>
</div>

Run peristaltic pump with just one mixer (Expected – May 1) (Completed! – May 3)

*This picture actually has two*
<img src="/images/old_mount_2_cup_pump.jpg" style="width: 100%" />

Set up the BeagleBone (Completed! – May 3)

Use Johnny-five to control the solenoids/pump from the BeagleBone (Completed! – May 3)

Create a settings page for OTTO (Completed! – April 23)
<img src="/images/settings.png" style="width: 100%" />
Create a menu page for OTTO (Completed! – April 27)
<img src="/images/menu.png" style="width: 100%" />
Create an “Add a Recipe” page for OTTO (Completed! – May 12)
<img src="/images/recipes.png" style="width: 100%" />

**Almost Complete (with commentary)**

Rig up all 6 liquor solenoids (Expected – May 21)

*We’ve made good progress on assembling the caps and just need to add a bit of glue to make them permanent. Then, we’ll just need to cut some wire and hook it all up to the power supply.*
<img src="/images/cap.jpg" style="width: 100%" />

Extend pump with 6 mixers and solenoids (Expected – May 31)

*We’ve hooked up 4 of the mixer solenoids to the pump and the power supply. The only thing left is to repeat what we’ve done for the remaining 2.*
<img src="/images/solenoids_in_fridge.jpg" style="width: 100%" />

Mount everything (Expected – May 21)

*We’ve devised a mount that works although it does look a bit ugly. We’re working on developing something nicer. If we have to we’ll use the less visually appealing bottle mount.*
<img src="/images/old_mount_final.jpg" style="width: 100%" />
<div class='embed-container'>
<iframe src="//www.youtube.com/embed/Z0_legeFDXw" frameborder="0" allowfullscreen></iframe>
</div>
<img src="/images/new_mount.jpg" style="width: 100%" />
<img src="/images/wood_enclosure.jpg" style="width: 100%" />
Solder everything (Expected – May 24)

*We’ve started running all the wires, but we’ve just tied them in. Once we decide exactly what we want we’ll solder and use heat shrink wrap to make it all permanent.*
<img src="/images/solenoid_circuit.jpg" style="width: 100%" />

**No Work Done**

Implement a queue for OTTO (Expected – June 1)

Add a weight sensor to detect a glass (Expected – Whenever (if) we have time)

Even though we’re still on track to finish, it looks like we won’t have time to implement some of our stretch goals. We have been spending a lot of time just running around San Diego trying to get together all the parts we need. We almost had a major setback on Saturday when we were working with the mini-fridge. We kind of broke the freon line so all the gas escaped and the fridge is basically broken. We managed to find someone on Craigslist that very same day that was selling a bigger, better fridge. It was a detour of several hours that could have easily morphed into a serious setback. That aside, we've been doing really well making steady progress everyday.

**Sprint**
<!-- I know this is disgusting. mama please forgive me. -->
Team<br />
&nbsp;&nbsp;Week 8<br />
&nbsp;&nbsp;&nbsp;&nbsp;Decide on and finalize enclosure<br />
&nbsp;&nbsp;Week 9<br />
&nbsp;&nbsp;&nbsp;&nbsp;Solder everything<br />
&nbsp;&nbsp;&nbsp;&nbsp;Mount everything within our determined enclosure<br />
&nbsp;&nbsp;Week 10<br />
&nbsp;&nbsp;&nbsp;&nbsp;Testing<br />
&nbsp;&nbsp;&nbsp;&nbsp;Testing<br />
&nbsp;&nbsp;&nbsp;&nbsp;Testing<br />

Chris<br />
&nbsp;&nbsp;Week 8<br />
&nbsp;&nbsp;&nbsp;&nbsp;Compile Redis on BeagleBone Black<br />
&nbsp;&nbsp;&nbsp;&nbsp;Configure to run when web instance is deployed<br />
&nbsp;&nbsp;Week 9<br />
&nbsp;&nbsp;&nbsp;&nbsp;Implement Kue for drinks queue<br />
&nbsp;&nbsp;&nbsp;&nbsp;Mount everything within our determined enclosure<br />
&nbsp;&nbsp;Week 10<br />
&nbsp;&nbsp;&nbsp;&nbsp;Test stability with concurrent MongoDB/Redis Cache<br />
&nbsp;&nbsp;&nbsp;&nbsp;Investigate speeding up website with web caching<br />

Rustin<br />
&nbsp;&nbsp;Week 8<br />
&nbsp;&nbsp;&nbsp;&nbsp;Responsive layout fixes<br />
&nbsp;&nbsp;&nbsp;&nbsp;Add additional unit options (e.g. ml, dashses)<br />
&nbsp;&nbsp;Week 9<br />
&nbsp;&nbsp;&nbsp;&nbsp;Theming<br />
&nbsp;&nbsp;&nbsp;&nbsp;Testing and bugfixes<br />
&nbsp;&nbsp;Week 10<br />
&nbsp;&nbsp;&nbsp;&nbsp;Testing and bugfixes<br />

Ryne<br />
&nbsp;&nbsp;Week 8<br />
&nbsp;&nbsp;&nbsp;&nbsp;Spearhead effort on newer, better enclosure<br />
&nbsp;&nbsp;Week 9<br />
&nbsp;&nbsp;&nbsp;&nbsp;Implement live menu filtration based on installed drinks<br />
&nbsp;&nbsp;&nbsp;&nbsp;Determine optimal drinks for pre-installation and demo<br />
&nbsp;&nbsp;Week 10<br />
&nbsp;&nbsp;&nbsp;&nbsp;Populate database with valuable recipes based on demo drinks<br />
