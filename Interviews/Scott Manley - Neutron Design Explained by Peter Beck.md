---
insider: "[[Peter Beck]]"
source: Scott Manley
link: https://www.youtube.com/watch?v=bVjYHLQtJUE
date: 2021-12-21
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Interviews]] <span style="color: LightSlateGray">></span> December 21 2021

**Insider**: [[Peter Beck]]
**Source**: [Scott Manley](https://www.youtube.com/watch?v=bVjYHLQtJUE)
**Date**: December 21 2021

![](https://www.youtube.com/watch?v=bVjYHLQtJUE)

🔗 Backup Link: https://www.youtube.com/watch?v=bVjYHLQtJUE

## 🎙️ Transcript

>[!hint] Transcript may contain errors or inaccuracies.

**Scott Manley:** Hello, Scott Manley here, and I'm with Peter Beck of Rocket Lab and we're here to talk about Neutron and everything else Rocket Lab is up to. Right, how are you Peter?

**Peter Beck:** Oh very well, thanks Scott. It's great to check in.

**Scott Manley:** So glad to have you here. So yeah, earlier in the year, uh, you ate a hat. How did it taste?

**Peter Beck:** Yep, it was absolutely terrible. When you put a hat in the blender, like all of the volatiles and the process of making the hat are released. So when you pull the top off the blender, you just get this waft of chemical concoction. I don't recommend it.

**Scott Manley:** I'll try not to do it, but I mean there must have been some thought that there was a great experience at the end of it, because you got to start building another rocket.

**Peter Beck:** Yeah, well look, I mean at Rocket Lab we, you know, everybody in this company is measured on "do what you say you were going to do." So there was really only one option when I had such a change of heart - you have to own it for sure.

**Scott Manley:** So the whole team's on board with this thing?

**Peter Beck:** Oh yeah, I mean who doesn't want to build a new rocket? I mean this is a dream. Generally in your career if you get to build one rocket, you count yourself lucky, but to get to do it twice, that's very rare.

### Neutron Design Evolution

**Scott Manley:** So I kind of want to talk about how it's changed from earlier in the year, because it was first revealed as this very simple rocket - eight tons to orbit, it had kerosene, it had a different profile. And then you came back earlier this month and there were a lot of radical changes to it. So I'm actually kind of interested how the process worked. Did you start with the business requirements and come up with this basic design, and then you sent it to the engineers? Did they come back or did you contribute? I'm really curious how this got that way.

**Peter Beck:** Yeah, look, the first rendition of Neutron was almost the roots. We knew there was going to be nothing like that, but we weren't far enough down the design process to be able to put out what we really felt was going to be the finished article. And also we knew it was going to be quite radical. So we thought, well, we'll put out what everybody would expect and then we'll finish our work and then release into much greater detail.

But really how it all started, as you point out, is it starts at the customer. One of the advantages of flying Electron a bunch and building all those relationships with the customers is you get to know them super well and you get to know the things that matter.

I think as people look at a rocket, the often mistake is thinking that the most expensive thing on the rocket is actually the rocket itself. And that is not the most expensive thing when you go to orbit. The rocket generally represents like one-third of the cost. When you go to orbit, it's actually all the overhead, all the infrastructure that surrounds a rocket that represents more of the value of it.

So if you look at what we've done there, you see almost no infrastructure. You see no barge, no strong back, no breakover - all of these things actually add tremendous amount of cost.

You know, I'm super fortunate to be the chief engineer on this project, so we can really... this is probably the last rocket I'll ever design, who knows, but it's been super liberating and fun process.

We all sat around a whiteboard and there's a couple of fundamentals that I laid down. Probably the thing that drove the design the most was this rocket has to be turned around in 24 hours - not because we actually want to turn the rocket around in 24 hours and fly it, but that constraint drove a whole lot of decisions that ultimately resulted in the lowest possible cost to get to orbit.

So that was the key fundamental. The diameter and the shape are a consequence of re-entry. It all kind of started trying to do the mechanisms for the landing legs, and I think we were scratching around trying to solve that problem because mechanisms suck, and if you can avoid them then that's always good.

So Neutron in its current form was really designed in like one hour on a whiteboard fundamentally, because we all stood around the whiteboard and said "landing legs suck, so how can we avoid them?" Well, let's just make the base wide enough so that we don't have to have them. And what we actually ended up with was like a DCX - it was a traffic cone.

### Design Philosophy & Approach

**Scott Manley:** Yeah, DCX. I remember that.

**Peter Beck:** And it's not surprisingly that DCX ended up like it was because that was the most efficient design for a single stage to orbit. But for us we had different requirements. One was no landing legs, so you end up with this really wide base. And then of course your upper stage doesn't need to be the diameter of your base, you end up with this taper.

And then as we started evolving that design, the re-entry of that first stage drove more of the requirements than the ascent. And if you think about re-entry, the 24-hour turnaround drove the ability to not launch on a barge. It drove the return to launch site concept of operations because marine assets are horrifically expensive to operate.

It costs us way more to put one tiny little ship popping out of the ocean for Electron than it does for us to fly out there in a helicopter, do a whole lot of operations, and come back even to pick up a stage. So marine operations should be avoided at all cost. And that drove a lot of that fundamental design.

Then the upper stage is the highest performing stage that you need to produce, so putting that inside stage one and putting it all in tension makes it super super light. And so you end up with this kind of traffic cone design.

**Scott Manley:** So you said in the Neutron presentation that the upper stage on Neutron is the lightest upper stage ever. Does that mean it's lighter than the second stage of Electron?

**Peter Beck:** Well, for its size...

**Scott Manley:** I was wondering if you meant that. I mean, I certainly understand that it's very light structure. Its dry mass will be very very good.

**Peter Beck:** Well, I think for the upper stage, think of Centaur because the Centaur is another tension balloon tank hung stage, except it's made of stainless steel. This is made of carbon, which is a quarter of the weight. And the great thing about that is it's so light there's no material in it, it doesn't cost much. So all of these things kind of come together to make a lot of goodness.

### Re-entry Approach

**Scott Manley:** So actually the design of the rocket is to support re-entry, and you mentioned on Twitter this doesn't have a need for an entry burn to reduce the force of the atmosphere compared to, say, the Falcon 9. And you believe that it can get away without an entry burn?

**Peter Beck:** Yeah, so the thing that unlocked return to launch site was really this, because you chew just a tremendous amount of propellant. There's two burns - there's one which is the RTLS burn which basically is a flip around to set us back on the trajectory, and then there's a landing burn.

You might go, "Well, how are we getting away with that?" And the thing is that re-entering Electron has taught us so much. It's taught us firstly in how to control a stage during re-entry just with cold gas RCS and some tricks to basically control that stage during re-entry. And it's taught us that if you can control that well enough through that corridor, then you can really define and constrain your heating to where you know where you can particularly run a small amount of the launch vehicle.

Now with Neutron, if you look at it, it's got a very high ballistic coefficient, very big base, and it weighs nothing. So if you're going to go and jump off the roof, it's kind of like jumping off the roof with an umbrella. Because it's so light, and it's so wide in diameter, just like Electron, we let the atmosphere do a tremendous amount of the work. We don't have to basically cook it because the deceleration profile is so light, it works to our advantage.

**Scott Manley:** And there's aerodynamic features on this for your steering, I presume. Right? You've got the fins at the front, or canards depending...

**Peter Beck:** That's right. That's exactly right.

**Scott Manley:** But, and then you've also got the legs - two of them extend upwards as straight along the side. And are those designed to provide lift?

**Peter Beck:** Right, yeah. So that's a kind of our downrange targeting, lifting body if you will. They also serve as very useful raceways.

**Scott Manley:** I was going to ask about that.

**Peter Beck:** Yeah, so the upper stage, because there is no strong back, that means there is no umbilical tower. So everything's umbilical in from the base, which means that the upper stage fill and drain lines run up those raceways to interface with the upper stage.

**Scott Manley:** Will the umbilicals be in the side of the base because that's your heat shield on the bottom? It would seem the best place.

**Peter Beck:** Yes.

**Scott Manley:** And so the legs come down. I presume they can't be carbon fiber because they'll be getting a lot of heat from both entry and the rocket exhaust. You're going to have some metal components there?

**Peter Beck:** Yeah, but I mean the majority of the structure is still carbon. It's just we run a hot skin on the carbon.

**Scott Manley:** And the fins, will those have to be metal?

**Peter Beck:** No, no.

**Scott Manley:** Okay. So the legs, they must have some sort of shock absorbers in them, right?

**Peter Beck:** Correct, yeah. There's basically a small section of the legs, about 500 millimeters, that is for shock attenuation for the landing base.

### Archimedes Engine Development

**Scott Manley:** So let's talk about the engine because obviously Archimedes engine, it's Rocket Lab's first like actual turbo pump-based engine. Are you excited to work on this?

**Peter Beck:** Yeah, I mean, I know everybody gets excited about engines, but I'm trying to build the boringest engine there's ever been. From a standpoint, the engine on Neutron is not exciting, and it's meant to be not exciting.

If you look at the propellant combination and the cycle, this is all about margin. It's all about margin. And designing a rocket is a giant engineering compromise, and you have to decide where the pain is going to be. If you have heavy structures, then the pain is in the engines and you end up with engines that are really really pushed. If the pain is in the structures, then you can kind of simplify.

Now for us, we've only ever built carbon structures, so for us the pain is not in the structures.

**Scott Manley:** I say that because it struck me that while the Rutherford engine did a lot of radical and new things, it felt to me like an engineer, actually an easier problem to solve than designing like a turbo pump.

**Peter Beck:** Oh man, no. The Rutherford is a springer. The combustion efficiency of that engine... it's really hard to build a really high-efficient small engine. Also, when you push the efficiency up, the thermal constraints become higher and higher. And Rutherford, the smaller the area, the higher heat flux per millimeter square you actually have to deal with. Whereas a larger engine, you have much much more margin on cooling.

So Rutherford is actually a really tricky engine, and because it's an all-anneal engine, it doesn't have a copper liner. And it's so high performance, that engine is actually really tough little engine to perfect.

Now, we've done enough engines to know that there's always a demon no matter where you go. But a gas generator cycle LOX/methane, 1,500 psi chamber pressure - it's all just keeping margin in everywhere. And ultimately if you're trying to build a reusable launch vehicle, you don't want to be running up near the yields of shafts and turbo pumps and running throats wide-heart-of-all. You just don't want to be there. So that was the reason for that choice.

**Scott Manley:** So you're going to have seven engines in the first stage, 100 tons of thrust per engine, and I presume you're going to have to be able to throttle that down a fair amount and control it quickly for landing.

**Peter Beck:** Yeah, that's actually the trickiest part of the whole propulsion program - that throttling range. For the upper stage, we have to throttle all the way back because we'll exceed our g limits. And it's quite nice that the upper stage engine throttling requirements match pretty much exactly with the landing burn engine requirements from a throttle perspective. So we only need to get that right once.

**Scott Manley:** The second stage, I was going to get some more... that's an Archimedes engine, it's also going to have the same basically pretty similar power head I would imagine, definitely.

**Peter Beck:** Yeah.

**Scott Manley:** Any changes to the throat diameter and nozzle?

**Peter Beck:** No, not at the moment. I mean, generally, even though the Rutherford is essentially the same engine, there is a small difference in the throat diameter in Rutherford's upper stage. So there'll probably be some small changes there, but largely it will be the same. I mean, ideally, you'll be building more of those because you'll be throwing them away.

**Scott Manley:** Yeah.

**Peter Beck:** Yeah, and that's also a good reason to follow a gas generator cycle - it's a very inexpensive engine.

**Scott Manley:** So for the upper stage, I'm presuming you're gonna have it able to re-light once it's in orbit. So how are you gonna perform restart and ignition?

**Peter Beck:** I mean, it's no different to what we do with an Electron upper stage. You have a start basket to contain propellants and a spin start on the gas generators. So nothing tricky.

**Scott Manley:** So you're going to electrically start the gas generator?

**Peter Beck:** Or pyro, we're in trade.

**Scott Manley:** Okay, that's what I figured. And so the upper stage has to throttle down as well because if you've got the lightest upper stage and a light payload, 100 tons would be a lot of thrust.

**Peter Beck:** This is one of the hardest problems to solve, actually.

**Scott Manley:** I thought it was kind of oversized to be honest. I thought it might be a different engine.

**Peter Beck:** It actually is oversized, but the thing is that, like I said before, it's always a giant engineering compromise. It's awesome for gravity losses, just after staging because you can sink all of that thrust in there. The upper stage is just super efficient.

If you look at the size of the upper stage compared to the first stage, it's really quite tiny. And that's because it's just so grunty and small. So you went on negating the gravity losses at the start of the second stage burn, but you lose when you have to throttle it back so you don't put the satellite solar panels through its battery pack at the end.

**Scott Manley:** You're looking at this project going ahead. What's your biggest concern about switching over to methane as a propellant?

**Peter Beck:** Just really the ground handling of it. Look, I know I've never subscribed to the fact that "wow, if you've got one cryogenic propellant you may as well have two." I mean, that's just terrible. Like you've got to deal with one cryogenic. Why on earth would you want to deal with two? It doesn't get easier at all.

I mean, there's still a delta in temperature between the two propellants anyway that's not useful. So you still have to deal with all the same things you have to deal with at room temperature. But really what drove methane was reusability once again.

If you look at the timelines and if you look at from a LOX/kerosene perspective, one of the things that take a lot of time to be able to turn a vehicle in 24 hours - well, I mean you have to descoot and clean out all of the soot of a gas generator cycle, or even in the main TCA on a LOX/kerosene engine. That takes a huge amount of time, whereas if you run LOX/methane, basically you can eat your lunch off of the TCA and the gas generator exhaust.

So it all came down to turning this vehicle in 24 hours. LOX/kerosene would be a fine choice, but it wouldn't meet that requirement. The servicing between flights of the engines just drives that away.

### Tank Pressurization & Carbon Fiber Technology

**Scott Manley:** Cool. So how are you going to pressurize the tanks?

**Peter Beck:** Autogenous.

**Scott Manley:** And you're not worried about like hot gases going in through your composite tanks?

**Peter Beck:** I define hot gases - I mean like room temperature, no, not worried about that at all. If I was putting like 150 degrees Celsius gaseous oxygen in there, I'd think differently. But room temperature, warm, cold, however you want to define it, not an issue at all.

**Scott Manley:** So Rocket Lab has worked a lot with carbon fiber over the years, and I'm just curious how has your work, how has this evolved since the Electron? I presume you've had changes to your process during the Electron program and going forwards. I'm just curious if you get anything, you know, are there new techniques, formulations are going to be needed for Neutron?

**Peter Beck:** Yeah, I mean, look, we've learned a lot. We've learned a lot in so many areas - firstly like laminate formulation, resin systems. You know, it was always a really big challenge to think, could we have a composite system that would be happy at cryogenic temperatures and then happy at elevated temperatures when we re-enter? And we've already solved that problem with Electron.

Cryogenics and composites is a whole problem to solve with micro cracking and interlaminar shears and bits and pieces. And then it's a completely different problem when you go and elevate temperatures. So all that is solved.

And composites get a really hard rap of being super expensive and slow and all the rest of it. And that's true if you're like one dude in a clean room laying it out and laying it down by hand. But when you're doing things like automatic tape laying, if you've got machines like Rosie, man, it's fast. To lay down an upper stage with an automatic fiber placement machine, you're talking like a day. You're measuring the build time in meters a minute. Like it's super super fast and incredibly reliable and accurate.

So things have moved a long way in the composites industry from guys in a clean room hand laying down bits and pieces. It's super super fast and really really cost effective.

**Scott Manley:** And so how does that leave you if you do need to make changes to the design? Like how quickly can you turn around?

**Peter Beck:** This is the engineering compromise, right? If you wanted to iterate a design over and over and over and over again, composites would be the worst decision you could make because the real cost in composites is the tool. It's very very difficult to build a tool and then completely scrap your design and change and iterate and iterate.

But we tend to iterate at the component and sub-assembly level. By the time we're building structures, we expect that to be right. And if you look at our development approach, it's not unique, but I kind of liken our development approach somewhere in between the traditional ULAs and whatnot, and kind of SpaceX. It's kind of in the middle.

We have a fail-fast philosophy, super hardware-rich, we build lots of hardware. But by the time we get to assembly level, we don't expect stuff to fail. By the time we're building tanks and rockets and bits and pieces, we don't expect it to fail. And if you look at an Electron, the very first Electron that we flew looks identical to number 23. There's no fundamental design changes that were made. We failed fast early, but once we arrived at the design, then it's locked in.

**Scott Manley:** There is a bit of a tank stretch in the latest, isn't there? Or is that a fairing?

**Peter Beck:** We put about 500 millimeters in the upper stage. And that's just, you know, as Rutherford engines are getting higher and higher performance, actually the majority of that was given from batteries. Battery technology, as we predicted, was improving. So we did a new battery program, and it just gave us a little bit more performance, which we're able to eat some of the mass that we added for recovery and kind of put us at a net neutral place.

**Scott Manley:** I mean, I would imagine that given you've got a tapered design on Neutron, you couldn't simply stretch the tanks without getting a whole bunch of new tooling.

**Peter Beck:** Most of the taper is actually in the interstage section because it's such a wide vehicle. The tanks at the bottom for stage one are not far off spherical - these two big blobs of spheres down there. So if we needed to extend and increase tank, it wouldn't be that big a deal because it's in basically a parallel section.

But a little bit of tank stretch here and there is no big deal. But if you're fundamentally changing the design, then this is the trade that you make when you work with composites.

**Scott Manley:** And actually the Neutron design, does it use a common bulkhead or is it two separate tanks?

**Peter Beck:** Separate tanks.

**Scott Manley:** And those tanks go right out to the structural wall?

**Peter Beck:** Yeah.

**Scott Manley:** Just but the majority of it is actually interstage versus tanks, because it's such a fat diameter at the bottom that the tanks are pretty stumpy.

**Scott Manley:** I imagine there's a fair amount of room in that interstage for the supporting hardware. I mean, you're going to have the fins that back on to that right?

**Peter Beck:** Yeah.

**Scott Manley:** And those will have electrical actuators?

**Peter Beck:** Yeah, I mean, that's still in trade actually - electro-hydraulic or just straight electrical is in trade. Because there's actually quite a lot of systems like that around the vehicle. The upper stage is kind of hung off the payload plate and the way that we hope to integrate that. And of course, you've got the hungry hippo fairing.

So the trade right now is - do we just do an electro-hydraulic system for all of those, or do we put discrete electrical actuators on each one of them?

### Fairing Design & Future Capabilities

**Scott Manley:** And speaking of that fairing, obviously a lot of comments were made about certain links to James Bond. And you know, you are in New Zealand, which I'm gonna point out I believe has a lot of volcanoes. Great places for a rocket base, right? Do you have a white cat?

**Peter Beck:** I do not have a white cat. I'm sure somebody at Rocket Lab does.

**Scott Manley:** But it shows a four-part fairing, and that obviously is an early design. And I'm wondering what the trades are for a four-part versus a three-part versus a two-part.

**Peter Beck:** Yep, and I would say that is a hot topic and discussion at the moment - whether it's four-part or a two-part. Basically what it comes down to is exit cone clearance. As the second stage is exiting out of the interstage and clearing past those fairings, the four-part gives you the most amount of clearance cone.

But there are some nice little tricks with some over-centering mechanisms that we're looking at that would enable us to deal with two. It's just that once again it's the trade - the simplicity of only having two moving parts versus the complexity of a mechanism, or the simplicity of a mechanism but four moving parts.

**Scott Manley:** Geometrically the two-part has to go further out, correct? But so why not three then? Because three gets you the same motion but...

**Peter Beck:** I like even numbers.

**Scott Manley:** Totally valid reason.

**Peter Beck:** You know, you could... I imagine there's like a bilateral symmetry in the rocket, so a four-way sort of fits probably with everything else.

**Peter Beck:** The four pedals is actually a hangover from an earlier iteration where we were going to use those pedals as aerobraking. And actually the original concept that I really pushed hard to see if we could close was to use them as control surfaces so we didn't have to have any forward canards or any actuated fin surfaces.

But the shape of them is just super ugly, and they're not good aero surfaces, and getting any kind of tolerance out of them was just a GNC nightmare. So sometimes it's easier to solve... to make control much simpler. Given that control is actually one of the really hard things here, giving the GNC team a break with some fins that they know what they're going to do when they actuate them is a nice place to be.

**Scott Manley:** I would just imagine the amount of force you had to put through those to keep them still and stop them flapping.

**Peter Beck:** It was huge.

**Scott Manley:** It's funny because somebody asked me about that, and I rejected the idea out of hand. So I'm happy that somebody, you thought about it.

**Peter Beck:** Yeah.

**Scott Manley:** And that also, I would imagine that if they have problems where they can't close, will you have a way to eject those so that you can land a vehicle?

**Peter Beck:** No, I mean, that's a whole level of complexity we don't really want to have. I mean, at the end of the day, it's a simple pivot and a hydraulic ram. Everything can fail, but it's a pretty low-risk system, especially given that the load on them is almost zero when they're being actuated from the nearest aerodynamic and heating. Once they're locked in place, I imagine there's latches between the segments and stuff because you're gonna handle the ascent.

**Scott Manley:** And actually I believe during the first Neutron presentation, you actually talked about possibly making this a human-rated vehicle?

**Peter Beck:** Correct.

**Scott Manley:** And presumably in that case, it wouldn't have the fairing, it would have an integrated vehicle on top?

**Peter Beck:** Yeah, exactly right. And it would... you could still use the existing second stage, but it would just be radically different.

**Scott Manley:** Then would you be using that given the mass of human-rated vehicles? Would that be an expandable launch, or...?

**Peter Beck:** I mean, you can get some big people on orbit with eight tons. I mean, you look at Soyuz for example. So you can do some meaningful things with that. I mean, if you need more performance, there's options to trade. You can go expendable, or if you really had to, you could actually land on a barge or something downrange. That would increase your performance a bit. But we think eight tons is plenty to get three people on orbit.

**Scott Manley:** It's not a lot of leg room in the Soyuz, I'm told. But you said 15 tons if it was expandable, right? And while you say no barges, there's presumably some value in between 8 and 15 that you could get from a barge landing?

**Peter Beck:** Yeah, yeah. We'll just have to look at the... at the moment we're really honing in on that eight-ton class. We think that's where we're seeing the majority of interest from our customer base. So we think that's the right place to be.

And if we found that we were wrong, we'd probably stretch tanks before we would introduce downrange assets. But it's always an option. I mean, I guess it's an option, and you wouldn't need a radical vehicle redesign to accommodate it. So if the business case worked out, you could start renting barges or whatever.

**Peter Beck:** I don't own a ship. I just do not. But anybody who owns a boat already knows what owning a boat means. Like ownership is just terrible.

**Scott Manley:** I live in the Bay Area. There's a lot of that.

### Photon & Lunar Missions

**Scott Manley:** So what we've talked a lot about Neutron, that's... it's really cool. Do you mind - I'm really curious if you want to talk about Photon, because we're getting ready for CAPSTONE next year, right?

**Peter Beck:** Yeah, yeah. Sure.

**Scott Manley:** Okay. Well, what is the current status like of Photon and Hyper Curie?

**Peter Beck:** Yeah, so it's getting really close. I'm not sure... I think we've released some images of the flight vehicle.

**Scott Manley:** You released a really good looking vehicle. It looks grainy.

**Peter Beck:** Now it's beautiful. I like to build beautiful things. So it was going through the sine-vibe test, actually right now. Yesterday it went up on the vibe table, so it's just going through its final TVac and vibes and whatnot, getting ready for the flight early next year.

Man, that's been a big program. It has absorbed way more resources and time than we thought it was going to. Going to the moon is no joke, as it turns out. It's proper hard.

**Scott Manley:** Yeah, there's nothing like Photon out there with its interesting engine, I guess.

**Peter Beck:** Yeah, I mean, the Hyper Curie engine is once again just super high performance for a tiny little engine. 320 seconds of ISP for this tiny tiny little engine is right up there. If you look at all of the hypergolics and storables, kissing up in that 320 second range is rare.

**Scott Manley:** And your Hyper Curie has pumps in it, right? Electrical pumps?

**Peter Beck:** Yeah.

**Scott Manley:** And so that's partly why you can get that performance, because you can get the higher chamber pressures?

**Peter Beck:** Exactly. And like, this is the perfect application of electric pumps because we have eight burns to do. And in between burns, we just let the sun recharge all the batteries. It's just the perfect symbiosis here because you're just harvesting that energy from the sun. You're not carrying it in a pressure tank or anything like that. It's just makes things so light and efficient.

**Scott Manley:** I mean, imagine it's an extra complication for the navigators to try to figure out long enough between each burn to make sure you can recharge for the burn length.

**Peter Beck:** I mean, we've kind of sized all of the panels to give us plenty of margin in that respect. The hardest thing with this mission actually... Well, the hardest thing - everything is hard. But each one of those eight burns... the reason why there's eight burns is because we do the burn and then we use the IMPAIR light radio and do the Doppler ranging from it to figure out where it is in the universe.

And then in 24 hours, the GNC team has to completely recompute everything again, and then we do another burn. And then the idea is just to keep refining that margin right down and then increasing that accuracy right down until the final kind of TLI burn, which is "hold onto your seat" for that one. It's going to be just right.

But there's going to be no sleep for the GNC team for like eight days as we do each one of these burns and recalculate its position. And it's quite a unique way to get to where we want to go here, in utilizing as much of the Earth and the Moon's gravitational field to get us in the right place. Direct inject is super energy intensive, but much much simpler.

**Scott Manley:** Well, and you're also going to NRHO, and that is one of these chaotic orbits. You're not like Apollo where you're just rushing across this hump in the middle. You're easing your way through this like hole in space in the geometry.

**Peter Beck:** Yep.

**Scott Manley:** And so the plan is, the plan with the... you're going to deposit CAPSTONE satellite and then you're going to go your own way, correct? And I haven't heard, are there instruments you're bringing, or is it just...?

**Peter Beck:** Well, I mean, we have camera.

**Scott Manley:** Really? That's an engineering camera?

**Peter Beck:** Yeah, and but we also have star trackers. So there's another couple of cameras there, but they're sort of five-megapixel black and white cameras. But we have a Rocket Lab payload, if you will, which is a camera.

But there's a lot of other like... even just the ranging radio, it's a tremendous amount of learning we can do with that. And this all sets us up for the Venus mission in 2023, because basically the trajectory is going to a different place, but we're using exactly the same process to get there.

**Scott Manley:** And I mean, presumably you'll have to work on the thermals of Photon before then for a Venus trip?

**Peter Beck:** Well, actually the re-entry probe that we're depositing in Venus is really the only thing that looks different. Instead of being a CAPSTONE spacecraft on the top, there's a re-entry probe.

### Conclusion

**Scott Manley:** Well, that's gonna be great. I'm really looking forward to seeing this thing fly and, you know, what both missions send us back. Peter, this has absolutely been great to talk to you about all this stuff, and I no doubt have like a million other questions afterwards, but it's always a pleasure.

**Peter Beck:** Likewise, always fun.

*[End of interview]*