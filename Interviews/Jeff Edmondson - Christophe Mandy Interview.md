---
insider: "[[Cristophe Mandy]]"
source: Jeff Edmondson Beyond the Forecast
link: https://www.youtube.com/watch?v=OCOnk3T1mIo
date: 2025-12-25
---
🏠 > [[Interviews]] > December 25 2025

**Insider**: [[Cristophe Mandy]]
**Source**: [Jeff Edmondson Beyond the Forecast](https://www.youtube.com/watch?v=OCOnk3T1mIo)
**Date**: December 25 2025

![](https://www.youtube.com/watch?v=OCOnk3T1mIo)

🔗 Backup Link: https://www.youtube.com/watch?v=OCOnk3T1mIo

## Transcript

### Introduction: ESCAPADE and Mars Magnetosphere Science (0:19)

**Host:** Welcome to Beyond the Forecast. This is a special edition episode as we're talking about how to build a spacecraft that's going to go to Mars. This is really cool. Mars is going to get two new visitors, two orbiting spacecraft that's going to study the magnetosphere.

So the magnetosphere on Earth is where we see how Earth's magnetic sphere, how that layer protects us on Earth and how the charged particles from the sun interact with that can create the aurora and things like that. But we got to learn that for other planets, too. And that's what we're going to learn on Mars. At least I'm not going to learn. That's what the scientists are going to learn.

We're going to talk with the systems engineer from Rocket Lab about the ESCAPADE spacecraft on this episode. It'll be really fun. So, without further ado, let's get in.

Joining me now, we have a very special guest from Rocket Lab here, Kristoff Mandy, the systems engineer with Rocket Lab is joining me right now. We're going to talk about the ESCAPADE spacecraft that's on its way to Mars. Welcome to Beyond the Forecast.

**Kristoff Mandy (Rocket Lab) (1:20):** Thank you. It's nice to meet you.

**Host (1:21):** Yes, thank you. And just before we get into engineering this spacecraft, a spacecraft that's going to Mars, tell me a little bit about history about yourself. Is this your first time ever building a spacecraft?

**Kristoff Mandy (Rocket Lab) (1:32):** Uh, not exactly. So, my name is Kristoff Mandy. I'm the chief engineer for the uh ESCAPADE program at Rocket Lab. And um so I it was my first real mission coming into Rocket Lab. I supported another couple of missions we've done in the past including CAPSTONE which is uh a beautiful spacecraft we sent to the moon and but prior to that I was actually working in manufacturing. I came to the US to work in aerospace but it took a little bit before I could get into the industry.


### Kristoff’s Role: Systems Engineering and Trade Decisions (2:01)

**Host:** Okay, that's fascinating. So tell me about the ESCAPADE spacecraft. What was your role with designing constructing this? Because this has been going on for a couple years now.

**Kristoff Mandy (Rocket Lab) (2:11):** That's right. So uh we started working on ESCAPADE in 2021 at Rocket Lab in January. Um and my job was to be the lead system engineer.

So uh I am responsible for all of the technical decisions on the program itself. Uh the way we think about it is that uh on the one hand a system engineer is responsible for requirements and interface documents and um documentation in general and on the other hand uh we're also the node of communication for uh interdisciplinary issues.

So, if say the thermal team uh decides that they need heaters to work for a couple more watts, then um then there's three options. Either we go back to the propulsion, sorry, the the power team and we tell them to figure out a way to get two extra watts in there, or we go back to the thermal team and tell them that they just have to eat it and find a way to not need two extra watts. Or we do some kind of compromise in the concept of operations and the the people responsible for that decision-making are the system engineers.


### Two Spacecraft, SIMPLEx Cost Cap, and Compressed Timeline (3:14)

**Host:** Gotcha. So this is this mission is not just one spacecraft that's going to Mars. It's multiple. So we have two going to Mars. How many were built in total?

**Kristoff Mandy (Rocket Lab) (3:25):** We did just build two. Okay. Uh which is already big enough. We also had some test artifacts but yeah it is two spacecraft going to Mars. Uh two two beautiful spacecrafts which is already hard enough on the team.

**Host (3:36):** I I don't even know how you to because you have to be precise on both.

**Kristoff Mandy (Rocket Lab) (3:41):** Yeah. I mean so what is really unique from the Rocket Lab perspective is that um so these are two spacecraft going to Mars but they're on a very tight budget and schedule.

Whereas a typical Mars mission would be a billion dollars or more these days. Um we were part of a SIMPLEx program for which there is a cost cap and that cost cap is at $55 million uh for the entire program. So that's not what comes to Rocket Lab but that's what goes to uh the the um the entity that is actually organizing the mission and that's Berkeley.

And so we are a supplier to Berkeley. We made their satellite and uh and we had to do this on a very tight budget and on a very short timeline in three and a half years instead of the usual 10 years and so so that really is the driver of all of the work we were doing.


### Test Articles, Qualification, and “Five Spacecraft Worth of Components” (4:28)

**Host:** And uh so two identical spacecraft but also you had some for testing. So how does that kind of work out? It's not a whole another spacecraft but you take parts to do some stress testing on that. Is that how it works?

**Kristoff Mandy (Rocket Lab) (4:39):** Yeah. So um so there's two ways to think about this.

So on the one hand um you know we uh when you build a satellite it goes through a range of tests. Classically once the satellite is assembled you take it through what is known as environment testing and that's where we test the radio emissions at the limit just to see if there's any issues there and then we vibe it. So that's uh get you know vibrating it on a table to shake it um to simulate the launch loads.

And then we do what is known as a TVAC campaign which is a thermal vacuum chamber campaign where we put it in a vacuum chamber. We take it to the highest and lowest temperature as it's going to see and cycle it a few times.

**Host (5:20):** I see.

**Kristoff Mandy (Rocket Lab) (5:20):** Um and and so we do that with the actual satellite but before we do that with the satellite very often you'll create uh what is known as a test article which will run through the same campaign um but usually a little bit stronger. So we'll have higher vibration loads. We'll go to higher and lower temperatures um to ensure that the design itself is going to work and that is known as a qualification article.

And so we'll make a qualification article which is as close as possible to the actual spacecraft two of the same spacecraft. And then um even at the subsystem level we might do this.

So we'll usually build for example on this satellite there are two radios on each satellite. So that means we did four radios to fly with and then we had spares and qualification articles even at the radio level where we would test the radio to the different environments.

So there's there's you know there's in total um about five spacecraft worth of components that we end up buying for the two satellites that are flying. [unclear]


### Interplanetary Challenges: Hot Near Earth, Weak Links at Mars, Slow Response (6:18)

**Host:** Wow, that's incredible. And flying through space is not just flying in an orbit around the Earth. You're leaving Earth's orbit. You're leaving uh anything that you'd be doing with the moon of Earth, you're going all the way to Mars. So, that's a pretty hostile environment, especially when the sun is still getting past solar maximum. There's a lot of solar storms. So, there's a lot of things to consider when a spacecraft is sitting there all by itself on the way to Mars.

**Kristoff Mandy (Rocket Lab) (6:42):** That's right. Um it's so it's hard enough to make a satellite in general. Uh but interplanetaries are especially challenging because as you point out we start around Earth which means we have to survive the Earth environments which uh in the context of this mission are kind of hot like it's much hotter around Earth than it is at Mars.

And then we have to make our way all the way to Mars where uh you know our communication link is much weaker because it's so far, where the power is lower because the uh the density uh of light that you get from the sun is lower, and where it's much harder to um to react to any issues because of the travel time of light.

And so our our satellites have to be capable of not just surviving the usual Earth environments, but also the Martian environments and everything in between.


### Why Loiter at L2: Transfer Windows, Space Weather Science, and “Loiter Orbit” (7:26)

**Host:** Uh, one thing that's about this that's interesting to me with this whole mission is the flight path and how long it's taking. So it was launched back on November 13th. It's going to loiter at L2 near Earth basically for a year. So why is it going to stay near us for a year before it makes that push towards Mars?

**Kristoff Mandy (Rocket Lab) (7:44):** Yeah. So the um the optimal trajectory to Mars uh happens every 26 months when the the Earth and Mars uh orbits orbital planes kind of align and when you can do um you know either a [unclear] transfer or [unclear] maneuver to get from Earth to Mars.

And and that happened last uh September and the next one is in November next year. And so originally we were planning to launch last September but uh there were delays with the launch vehicle and uh ultimately uh we missed the launch window and so uh the you know the the  simplest solution is then to wait for the next launch window.

But NASA decided to launch us early and have us wait for that planetary alignment in space and use the time in space to already do some of the science.

The the satellites are intended to measure um primarily solar activity, but it's really space weather. So, it's the effects of the solar wind on the Martian atmosphere. But we can already look at the effects of the solar wind in the Earth environment and in particular in an area known as the magnetotail, which is a zone uh you know behind the Earth as it sweeps its way around the sun. That has interesting properties from a heliophysics perspective. [unclear]

**Host (8:59):** Yeah, I didn't think of that. That's interesting because I thought, okay, they're just going to sit there and have on standby. But you're actually doing some science while we're waiting to go to Mars.

**Kristoff Mandy (Rocket Lab) (9:08):** That's right. So, we're on an orbit that we term a loiter orbit. Uh it's kind of shaped like a kidney bean if you're looking at it in the right frame of reference.

And um it sort of rotates around one of the Lagrange points. Uh so the Earth-sun Lagrange Point 2, which is where James Webb is parked. So, we're sort of rotating around uh that point, coming back to Earth just as the orbits align, and then we'll be able to do our trans Mars injection maneuver, which is the the biggest maneuver we do on the satellites uh to get us on the way to Mars.

**Host (9:40):** And that'll be happening when roughly.

**Kristoff Mandy (Rocket Lab) (9:42):** Yeah, it's early November of 2026.


### “Ruthless” Build vs Buy: Lead Times, Margin Stack-Up, and Vertical Integration (9:51)

**Host:** Okay, that'll be exciting. We'll have to see how everything goes once we get to that point. One thing about the spacecraft um that you developed with Rocket Lab and at Rocket Lab and what I've seen when I was at your Auckland location last February is that a lot of the things that you do at Rocket Lab, this spacecraft or the Electron rocket or the Neutron rocket that's coming up is things are built in your buildings.

You guys kind of vertically integrate a lot of the things, not maybe everything or a lot of things, but a good chunk of this spacecraft like reaction wheels, propulsion tanks. So tell me kind of the anatomy of this these two satellites that are going to Mars. What did you guys develop and do at Rocket Lab?

**Kristoff Mandy (Rocket Lab) (10:28):** Yeah, so Rocket Lab has been really good. Um, I like to think that we're ruthless about build versus buy decisions. So if it makes sense to build it in house, we do so.

And the reason you want you want to do it in house kind of fall in three categories. So sometimes um it's just more economical to do so. That's that's rare. It does happen but you know if it costs money to a supplier to make then it's also going to cost us money to make. And if a supplier wants to make margin we'll also want to make margin. So that does happen but it's not that frequent.

Uh more often um when you build it in house you get to control the supply chain which helps with lead times and so we can make things faster.

And then the the other biggest advantage really is that um when you you know we we make radios or we make um reaction wheels as you point out and when you make those things and then sell them to a customer um you'll usually pad your performance to make sure that when the customer use it in their environment and whatever they want to do to it you can guarantee that performance.

So, if you say that your radio is going to have, I don't know, 30 dB of power, then um you know, you might actually test it to 35 dB to make sure that it can reach the 30 dB you're talking about. And and if you do this for all of the different components in the system, that margin stacks up.

And so if we're making it in house and we know where that margin is and we have the right specialists who know how to to handle it then um then you're not stacking margin on margin and you can make your system perform much better um which is another advantage of doing so.

So, as you point out, you know, we we build reaction wheels and star trackers, we build uh radios, but even um our team in New Zealand has a a tremendous strength in the composites and the way we build our composite decks and struts and other parts in the spacecraft um is also kind of unique and a specialty, as are propulsion.

Since we make uh rockets, we're we're pretty good at the propulsion side of things as well.

**Host (12:29):** So that probably really helps too because as you're building this thing and designing the spacecraft, you're thinking, "Oh, wait. This we got to make sure that this radio system works correctly or the star system works like this, but who who built it? Oh, wait. We know who built it. Let's just email them because they work down the street or they work on the other side of the Pacific." So that's probably very helpful in terms of collaboration and communication.

**Kristoff Mandy (Rocket Lab) (12:47):** That's exactly right. And so, you know, whenever we run tests and have an issue, uh, the person we need to ask a question to or, uh, you know, bring in to to help us fix it is right there somewhere.


### Mission Duration: Earth Loiter + Cruise + MOI + Conjunction + Science Phase (12:56)

**Host:** Yeah, that's very helpful. Uh, so another thing that I wanted to bring up is the once you get to um once you get to Mars or on that way to Mars, kind of what's the long-term goal there? How long is this mission going to be?

**Kristoff Mandy (Rocket Lab) (13:12):** Yeah. So, it'll take a while to get to Mars. So, we have one year in Earth orbit until we we do that uh TMI, which is the trans Mars injection. Then, it takes about 11 months to get to Mars.

Uh and then we get to Mars and do uh the second biggest burn which is called the Mars orbit insertion. And so at that point um so it's already been one year and 11 months and um we'll actually wait a little bit about 7 months because um the Mars is going to pass behind the sun and when that happens it's it's basically impossible to communicate with the satellites. So we're waiting for that to happen. It's a conjunction.

And then after the conjunction the primary mission will take place. And so there is a an 11-month science mission at Mars that starts after everything I just described. So it's after about 26 months.

Uh and then once the 11-month mission is over, um we've met the primary goals of the satellites. But our assumption is that if the satellites are still in working order that NASA will want to continue prolonging the mission and continue uh you know executing whatever science it can until we run out of uh consumables which would probably be running out of fuel.

So the the spacecraft you know if everything goes correctly and they last a little bit longer for a good example of the Mars rovers they lasted much longer than they were designed for. So you know we're hoping for another success story like that.

We could use the spacecraft not only to study about Mars magnetosphere and the solar wind interaction from the sun but maybe for future missions that could go to Mars too for simple communication or other um kind of crutches and aids to help with the science of those too.

**Kristoff Mandy (Rocket Lab) (14:47):** That's right. Um yeah absolutely. So they can be a communications relay if needed.

Uh and you know one of the so the one of the drivers of the science is is an assessment of the history of the Martian environment and weather and in particular um it there are signs of there having been water at the surface of Mars which is no longer the case.

And uh the the only way that would have happened is if the conditions uh you know the temperature and pressure at the surface of Mars which used to be high enough to support water uh have now gone down and the pressure and temperatures are are lower.

And for that to happen the atmosphere has to have vanished somehow and the mechanism by which the atmosphere of Mars gets stripped away is this interaction between the solar wind and the Martian atmosphere.

And so uh you know that this primary mission we have which lasts one year will effectively take um a a pretty thorough assessment of what that stripping process looks like but for a very specific period of the solar cycle.

The sun has this 11-year cycle uh during which it increases and decreases in activity. And so the longer that uh mission at Mars lasts, the more data points we have of how the stripping takes place over the course of the solar cycle, which will also help us really understand what the Martian environment is like.


### Big Engineering Challenge Example: Propellant Tanks, Late Integration, and Test Strategy (16:08)

**Host:** During your time uh engineering and building this spacecraft, were there any big challenges or things that your you and your team had to overcome? And how did you do that? Tell me about that.

**Kristoff Mandy (Rocket Lab) (16:16):** Yeah, I mean there were many and you know the the drivers of the challenges are what I mentioned up front which is the the lower cost and faster timeline.

Um and you know I think maybe one of the the best examples of uh the kind of challenges we faced in the way we address them is to bring up our tanks.

So uh you know if if you look at our spacecraft we were designed to be able to go from Earth's orbit to Mars whereas a typical mission to Mars uh is put on board a rocket and the rocket sends it to Mars directly. Um we did not have that benefit.

NASA uh you know in order to keep the costs down wanted us to ride share and uh when we were designing we didn't know what our ride share would look like.

So we had to be able to support a bunch of different missions which meant basically being able to go from um a Earth orbit such as a sun synchronous orbit all the way to Mars.

So given that constraint uh we had to design satellites where about 60% of the mass is fuel. So those satellites are about 500 kilos or or 1,200 lb and and 60% of that is fuel, which means that when you look at them, they're really big fuel tanks with uh instruments and computers kind of stuck all around them.

And uh the originally the vendor um for the fuel tanks was supposed to be able to deliver them in two years, but they ran into issues and uh you know two years is already a pretty long time on a three-year mission.

And so we were we were running out of time to get that resolved. And uh about eight months before we needed the tanks, we started making them ourselves.

And so ultimately the tanks that have flown are ones that we didn't buy from anyone but built in house, which goes back to what we talked about earlier where you know one of the benefits of building things in house is you control the supply chain and from there the the schedule.

Um but but it's not that simple. So uh you know we we had to figure out a way to integrate those tanks very late into the satellites and um and that's not an easy thing to do because once uh you build a satellite as I mentioned the next thing you typically do is vibrate them and then once you're done with that you uh put them through the thermal testing.

And so we came up with a method of testing the satellites with mass simulant tanks instead of the flight tanks and then with thermal tanks instead of the flight tanks so that we could plug in the tanks as late as possible um and and were able to close the schedule and and get on time to the launch site last uh last year.


### Dynamics and “Fundamental Mode”: Stiffness vs Fuel, and Designing for Re-Open/Re-Close (18:54)

**Host:** Wow, that's interesting. So, if you add a tank at towards late in the game after you've kind of designed everything else, is it also a factor of where that weight of fuel is going to sit with your are reaction wheels and everything that kind of controls the spacecraft? Is that an issue?

**Kristoff Mandy (Rocket Lab) (19:10):** Uh partly. So you know you you care about the center of mass and you care about the inerts which are is what you bring up.

Um but those are set basically once you know most of your satellite is fuel. There's not much you can do about where the center of mass is going to be. You can move your reaction wheels up and down. You can move your components here and there but the center of mass isn't going to move that much. It does to some extent but not that much.

Um the other quantity we care about a lot is what is known as the fundamental mode which is the the frequency at which uh the satellite will vibrate. So you know everything you make has a fundamental mode and uh you don't want that mode to be excited by the launch.

Um and so there is usually a minimum mode above which you need to be uh in order to be compatible with your launch vehicle. And uh and in order to meet that you'll have to stiffen your system.

And when a lot of your system is fuel, it's actually very hard to stiffen it because the fuel will do what it wants to do.

So, so you're right that uh there are some some technical considerations such as where the center of mass is or what the fundamental mode is.

Um but there's another side to this which is you know in order to open and close your satellite to replace the tanks you have to make it so that the interfaces to those tanks um can be tested very simply because you will basically have made your satellite and then vibrated it and if when you open the satellite to replace the tank you're taking everything apart then you've sort of invalidated that test.

And so um so to do that we did something that I think of as being pretty clever which is um you know when you when you build a satellite and you want it to be stiff, the classical image that people have of a satellite is a box with some solar panels sticking out of it and uh and if you start with that and then you try and make it lighter, you might start cutting holes in the box um you know to try and keep the general shape of it which is a very stiff shape but make it light.

And if you push that to the extreme you end up with the design we have which is you have kind of two decks. There's a bottom deck and a top deck that are connected by struts and that that sort of has the same uh stiffness property as a box would have but for much less mass.


### “Two Decks + Struts” as a Lever: Tank Access and Thermal Zoning (20:42)

**Kristoff Mandy (Rocket Lab):** And so so you know taking uh taking the design from the box type thing to the two decks with struts type thing is good engineering and it's something that Rocket Lab would do but I'm sure many other companies would do.

But one of our strengths is to see that design and harness it to do much more. So, one of the examples of that is what I described, which is we figure out a way to have that basic structure, the decks supported by struts and make it so that you could easily open and close the decks to replace the tanks.

But another example of how we use that cleverly is that um we made the thermal system a bit simpler.

So, you know, uh you have components on a satellite that have a tendency to get hot like batteries or amplifiers or flight computers. They they take electricity to run and then they get hotter. And you need over time to find a way to get rid of that waste heat.

And then you have components on a satellite that have a tendency to get very cold, regulators and propulsion lines. And that's because gases expand and contract. And as they do so, they get cold.

And so often uh your thermal system on board the satellite has to figure out a way to heat up this the things that are getting cold and to radiate away the heat from the airs that are getting hot.

And what we figured out is that if your system is designed with a top deck and a bottom deck, then you can make it so that all of your hot components are on one deck and all of your cold components are on the other deck so that they're not fighting each other thermally, which then simplifies the thermal system, makes it cheaper to make. It makes it easier uh to assemble as well.

And then um that entire system has a tendency to to degrade more gracefully when there are faults. So there's only benefits.

But we only got there by looking at our our satellite realizing that it was going to end up having the structure I described and then taking that structure and making it do something good for the thermal system just like we took that structure and made it do something good for the program schedule.


### Closing and Outro (23:19)

**Host:** You describe it make it so simple but it's a very complex thing I guess.

**Kristoff Mandy (Rocket Lab) (23:22):** So I I hope I was able to describe it simple.

**Host (23:26):** Thank you. So um we're going to be keep an eye on this mission as it's on its way to Mars. Not there. Not it's on its way yet but that's going to be happening here as we go into the next year. So exciting stuff.

We might have to check in with you and see how this mission is going as it goes on into the future.

**Kristoff Mandy (Rocket Lab) (23:41):** Yeah, I mean we're definitely very excited. It's been amazing to see the satellites operating in space. It's what we built them for. So, it's a huge reward to see them work and we're definitely looking forward to the trajectory to Mars.

**Host (23:51):** Well, thank you very much, Chris, for joining me here on Beyond the Forecast. And good luck to you guys at Rocket Lab for your future uh missions and spacecraft.

**Kristoff Mandy (Rocket Lab) (23:58):** Thank you very much. It was great meeting you.

**Host (23:59):** All right. Thank you. All right. We'll be back with more on Beyond the Forecast here in just a bit.

And once again, the ESCAPADE spacecraft is going to be on its way to Mars after it sits in that L2 Lagrange Point 2 position for the next couple of months. It should be on its way to Mars later next year. We'll keep you up to date on what happens with that with Rocket Lab and there's a lot of other things that are happening in our own backyard with [unclear]. So, we'll keep you up to date on all of that in the coming year.

Thanks for watching this episode of Beyond the Forecast and we'll see you next time.
