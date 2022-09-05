# Novak template rebuild

## BLUF

Rebuild the Novak template in both vanilla js and nextJS using only documentations.

## Overview

In order to test my knowledge and potential shortcomings, I am building the landing page from story site named Novak (https://www.storysite.co/storybrand-website-templates/p/novak-template). I chose this landing page for 3 reasons.

1. I love the consept of story brands and even employ it religiously in my own detailing business.

2. I wanted a quality wireframe to work with. although I dont have the Figma files, I  think its pretty good quality for me to work with (live demo will help)

3. coffee is life ☕️

this will probably read like a journal, so apologies in advance

## Objectives & deadline

Despite the face that im still a new developer, I want, to treat this as if its a real client and project with deadline. As such, I will set a **deadline of 1 October**, which gives me a month to complete the site.

I will also take notes on progress, lessons learned, and so forth in this readme. This is to facilitate in highlighting shortcomings as well as hold me accountable to my progress.
#
## Notes

### **31 Aug**

#
first day of the project! Im still organizing and planning it all today. I know I wount get much done over the long weekend, so the plan for the day is to organize file structure, plan download assets, and build the navigation bar. I am bouncing between doing mobile-first design or not. Ideally I would, but I dont want to distract too much from the main objective-- rebuild the site. Chances are, I'll do mobile first-design, but I'm not commiting to that idea yet.

#### **post-coding**


Imported all of the assets to site. worked on navbar and realized I dont quite understand position as intimately as I should. Had navbar looking decent, but then broke something when I made position fixed. ended up cannibalizing work trying different CSS snippets just to see how they would react. I already want to use NextJS just for the ease of it, but that would defeat the purpose of this. The plan tomorrow is to study **more** navbar design and then come back at night and try to implement what I learn. Ideally, I want the bar to be uptop and transparent, but gain a white bakcground on scroll and follow the user down the page. I have the JS drafted out and could probably use the navbar I coded ofr the Movement Clinic, but I should be able to do it again off the cuff.

#
### **1 Sept**
#
Today is the day where I either complete the navbar or I wont have it done until next week. Girlfriend and I are taking a vacation, so probably wont get much work done.
#### **post-coding/notes**
Finally worked out basic nav bar. I dont like my CSS display declarations. Ill work on cleaning it up later. THe scaling, text, and such isnt perfect, but as long as I can give the bar a slightly thinner profile, Ill be happy. Might work on it more tonight, but i'm probably going to fiddle with a youtube code along or watch netflix and clean. (this was a lie, I spent most of the night trying to work out what i did wrong. ended up creating an agnostic navbar file and trying to find my issue while watching Bobs burger)
#
### **2 Sep**
#
Woke up this morning and got straight to work! Amazing how sleeping on a problem can just fix your issue. Decided to throw everything in a Nav wrapper and set my properties from there. Fixed some issues, so from there I wiped out my SCSS file and restructured it, testing different position settings until it all snapped into place! 2 hours of work and I got the navbar **mostly** completed and the background image positioned.

Its time to start my vacation, so a ton wont be completed this weekend. I do still intend to maintain #NoZeroDay so I will work on stuff here and there, but it'll probably be more conceptual stuff than this website.

Notes for future me: Background is set as background of content div. I dont think I like this too much. may be better if it is put into its own background div and then set. Ill think on this while i drive.
#
### **2-5 Sept**
#
Got some work done on my vacation! Really spent the time refactoring the navbar more. I also decided that while while mobile first is ideal, I should keep the project in scope and Just copy the page as is and add mobile if I have time.
