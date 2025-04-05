---
insider: "[[Peter Beck]]"
source: NASASpaceflight
link: https://www.youtube.com/watch?v=C3l87aPWUCk
date: 2023-11-12
---

**Insider**: [[Peter Beck]]
**Source**: [NASASpaceflight](https://www.youtube.com/watch?v=C3l87aPWUCk)
**Date**: November 12 2023

<div class="responsive-video">
<iframe src="https://www.youtube.com/embed/C3l87aPWUCk" title="Electrons Return to Flight, Neutron, and more - With Peter Beck - NSF Live" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

## 🎙️ Transcript

>[!hint] Transcript may contain errors or inaccuracies.

**Jack Beyer (NSF):** Welcome to another NASA Space Flight live. This is a special edition because we have a special guest. I'm Jack Beyer for NSF, and we are joined today by CEO of Rocket Lab, Mr. Peter Beck. Peter, thank you so much for joining us for a very special episode of NSF live.

**Peter Beck:** My pleasure, great to be on the show, Jack.

**Jack:** Excellent, and of course we also have another NSFer on the stream, Sawyer. Thank you for joining us for what will prove to be, I'm sure, a really fun interview.

**Sawyer:** Thanks Jack, I'm really excited, and Peter, again, thank you so much for joining us. We got a lot of fun stuff to talk about.

### Electron Anomaly Investigation

**Jack:** Let's jump right into it and let's talk about Electron. Peter, you guys recently had an anomaly on an Electron flight, and you've recently closed out that anomaly investigation. Let's just hear a little bit more about what happened and how you were able to determine what the issue was, maybe mitigations, that sort of thing.

**Peter Beck:** Yeah, well, I mean, we could use the whole time just talking about that because Electron has got such a long flight heritage now that any anomaly wasn't going to be like super simple where somebody just forgot to screw something on. It was going to be really convoluted and difficult, which is exactly what it turned out to be.

So perhaps I should kind of start with how we got to the root cause. Obviously, we had a successful first stage separation, and we got the start of an ignition transient of the second stage. But during that ignition transient, there's a whole bunch of stuff that obviously happens.

If you want to boil it down to its most elementary form possible, there was essentially an electrical arc that occurred, which pulled down the whole voltage. We have a high voltage system and a low voltage system on Electron, and there was a high voltage arc that pulled down obviously the high voltage rail, but also it was an arc to chassis, so it pulled down the low voltage rail as well. That's the easiest way to describe it.

Now, Electron's a little bit unique in the fact that we have electric turbo pumps or electric pumps that pump the propellant into the Rutherford engine. So we have that 500 volt rail there, sitting at that potential.

When the arc occurred, if you go back to the live stream, you can actually visually see a big greeny glow for a small amount of time. The whole event was about 1.6 seconds or so, so it's a very short transient to try and capture, but the team did an awesome job.

Obviously, in a failure investigation, you create a tree, and the object of the exercise is to lop as many branches of the tree off as you can. There were hundreds of sub-investigations occurring all concurrently, but we were able to actually pinpoint the location of the arc through some pretty devious methods.

We've got some folks on staff who do quite a bit with movies and things like that, and they were able to recreate all of the lighting conditions. There are some unique kinds of shadows that are on the nozzle, and if you blow a certain light in a certain place, it'll cast a certain shadow. We were able to determine the exact location of the failure point using these methods, and also there are a few sparks, and if you trace the trajectory of those sparks and then match it up with the light – this is all evidence piling on top of each other to pinpoint a location.

But very quickly, we knew exactly where the general region had occurred, and as the fidelity of that optical modeling got better and better, it actually pointed exactly to the place that we were concerned about, and it was being corroborated with other information.

Once we determined where it was, which was on the fixed pack, fixed high voltage battery pack, we were able to really focus our efforts there and continue to dig deeper and deeper.

### Paschen's Law and the Root Cause

This is where it gets a little bit more tricky. At the end of this conversation, everybody will be Paschen's Law and Paschen's Curve experts, but without having a whole bunch of Paschen's curves to draw on a whiteboard and explain it, there's a sequence of events that all had to be true for this to occur.

If you wrote them all down on a piece of paper – and we've summarized them at the highest level possible for the most amount of general consumption by the average person possible, but there's a lot of depth behind them – even if you wrote them all down, you'd say, "Well, that's highly improbable." If you had a risk register, you would go through all these things and probably still think that this is improbable.

But to make a long story short, the Paschen's Law is a unique phenomena with respect to high voltages in space or in partial vacuums. The Paschen's Curve is a conjunction of a number of things – you've got voltages, distances, pressures, and gases, and in a mix of certain conditions, arcs can behave very differently.

I think the best way I could describe it is: if you take a battery at 500 volts down here on Earth and you put the two terminals of those batteries – positive, negative terminals – 30 microns apart from each other (one-third of the thickness of a human hair), they still won't arc to each other on Earth. For all intents and purposes, you've got to touch them on Earth to get an arc.

Now, in space, that same 500-volt battery, the same positive-negative terminal can jump an arc nearly a meter under the right environments in a partial vacuum with the right gases.

**Jack:** Wow, a whole meter?

**Peter Beck:** Yeah, it's a crazy phenomenon. You can go to Wikipedia and look at Paschen's Curve, and you can see a real simplified Paschen's Curve. The reality is they look nothing like that when you actually start to overlay a bunch of stuff on them, but you get the general gist of it.

At a very partial vacuum, in certain gases especially, it's aggravated. You can form these big arcs. With Electron, of course, at stage separation, the rocket gods wouldn't be so kind to us – they've put us in the worst part of the Paschen's Curve possible at that very point in time, where the battery voltage is at its highest, of course, because the batteries are full.

So what that leads to is basically all the high voltage looms in Electron have to be hermetically sealed. You can imagine that one pinhole in any of those high voltage connections can jump an arc to nearly a meter. So if you've got a pinhole in one of those things and anything around it is a meter away, then you can, in theory at least, jump an arc.

We go through extreme levels of testing here. In fact, we take the whole second stage, stick it in a vacuum chamber, pull it down to these partial vacuums, inject it with argon to try to aggravate it. But it's just a really hard thing to try and simulate because the various gases have quite a big effect.

In that particular flight, we had trace amounts of helium, which is normal, and we obviously had nitrogen because we purged the interstage with nitrogen. So we had a helium-nitrogen kind of mix, so there's some aggravating gases there. And then we have the high voltage batteries.

On top of that, because they're a DC brushless motor sort of a synchronous motor, we get an AC ripple on top of the DC line. So although it's 500 volts DC, we get an AC ripple on top of that 500-volt line, which is also an aggravating factor for a Paschen's Curve. If you have 500 volts DC, it might jump a meter; if you have 500 volts AC, then that distance increases once again. And you've got to dig real deep to find this kind of literature; it's not readily available, and a lot of it we kind of derived experimentally.

So you've got trace gases, and then you have an AC ripple over the top. Clearly, there's the tiniest imperceptible fault in the insulation, and then where that fault in the insulation is, depending on where it is, can also have a big effect on the probability of an arc being able to form and go to ground or go to chassis.

Ultimately, all those things lined up in a very transient moment because the moment we ignite the second stage, the battery voltage drops and gets us into a better part of the Paschen's Curve. And of course, as we climb, we quickly climb into a much harder vacuum, so we don't have so much partial pressure, so we actually climb ourselves out of the Paschen's Curve.

So in a very specific set of conditions, in a very specific point in time, we were able to have all of those things align, and ultimately, the end result was an arc which pulled the bus voltages down, and then there's no coming back from that.

### Finding the Exact Location

**Jack:** That is absolutely fascinating, and I made a mental note in my head to ask about the gases, and you took us through the gases. I didn't even have to ask. So that level of detail is super appreciated, and it's absolutely fascinating.

As someone who devours industrial accident media or just strives to learn how these things happen, it sounds like a classic sort of Swiss Cheese model situation where all of these disparate things had to line up to make this happen, and it could only happen at that exact point in time at that exact pressure. That's wild.

And just props to you guys and the team there for using lighting and the trajectory of sparks to figure out where on the vehicle. I mean, that's just... I'm geeking out hard over here. That is absolutely fascinating stuff.

**Peter Beck:** It was super cool because the guy who did all the lighting work, we kept him segregated from the investigation team, so he had no idea where the area that we were looking was. It was a completely independent and isolated project. It was about a week or so in, and we'd already identified this area as the most probable. When he came in and presented his results, it was bang, right exactly where we were looking. It was super cool to see that corroborated.

**Jack:** It's obviously unfortunate to have an anomaly, but it's amazing to see what a bunch of smart people in a room or two separate rooms can derive. That's absolutely fascinating.

So the anomaly investigation is wrapped up, you have a cause. What are some of your mitigations for this anomaly?

### Mitigations for the Anomaly

**Peter Beck:** The first thing to do is increase the testing even further. Now we have some new instrumentation in the vacuum chamber, and we're able to measure electrical potential fields down to the picoamp now, which is crazy accurate. Basically, if there's any breakdown in any insulation anywhere, we start to see partial fields occurring in the chamber.

The team's come up with some pretty clever ways to triangulate that to find where it might be. Obviously, you've got a big high voltage system. It's a good go/no-go, but it's also good to be able to pinpoint it.

That was kind of one thing, but I really wasn't happy with that as the end result. Sometimes the best way to solve a problem is to delete the problem entirely. It was a rather extreme solution, but essentially what we did is: the upper stage is in a battery frame around the upper stage engine, and we filled in all of the panels around the battery frame and put a flexible boot up to the nozzle. We now just are going to pressurize that whole area.

By pressurizing that area – it only needs to be like to half a PSI – basically, it's like being back down on Earth. So there's no way you can jump an arc 900 mm or a meter. You basically remove any of that Paschen's Law out of the equation anymore. It's literally as it would be down on Earth.

**Jack:** So I mean, this is sort of what happens when you're on the bleeding edge – you get these crazy edge cases. And you guys at Rocket Lab, you have the carbon fiber rocket, you have electric-powered turbo pumps, you're doing things that nobody else is doing. 

It's unfortunate to have the anomaly, but I'm super glad you guys were able to pinpoint the cause, do these mitigations, and you're going to be flying again soon here, I believe by the end of the month with IXPE?

**Peter Beck:** The window opens at the end of November, and provided the customer's ready and we're happy, then we'll roll it out and fly again.

The team's done an amazing job. Nobody's slept for weeks and weeks, and just plowed on through it. It's one thing to get to the causes; it's another thing to implement pretty drastic corrective measures. It's non-trivial to build a press system and monitor that pressure in there and create that whole solution in this time frame, and then go through all the qual testing and acceptance testing. It's a lot of people really busting hard to get all this done.

### 2024 Launch Schedule

**Jack:** Good on everybody that has been absolutely working their tails off to get this done. So we have the return to flight coming up. We said the window opens end of November, but let's talk for a second about 2024. You guys have a lot of launches planned for next year, do you not?

**Peter Beck:** We do. It's a busy year for sure. We're very happy with that manifest, and that's a great place to be for the product.

**Jack:** It's like something like 22, I think that's what I remember reading – 22 Electron launches, including the HASTE launches as well?

**Peter Beck:** That's correct, and you know, Electron really cemented itself as a great product and really reliable, a great way to get to the particular orbits that ride-share just can't get you to. So it's really found its groove.

I know there's a lot of commentary about "Is small launch even a market?" and all of that, but you can clearly see there that it is a market. It's a nice little market, and the product is well-placed to do well in that.

**Jack:** What do you have to do to enable 22 launches? Scaling up to 22 launches, what sort of limits you guys? Is it pad turnaround? Is it stage production? Is it some hard-to-get or long lead time item, or like a piece of metal like niobium or something? What have you been doing to enable that increase in cadence?

**Peter Beck:** I mean, we should start off with the premise that rocket production sucks. It is just really, really difficult, even at the best of times.

But we have all the pads – there's two piers at LC-1, there are three clean rooms down there, there's a pier at LC-2 and two clean rooms there. So all that kind of base infrastructure is there. The factory has been scaling, the production team have been doing a great job incrementally pulling down the build rate.

The product is super mature, the manufacturing process is super mature, and we've kind of transiently hit the rate that we need to hit for next year. Next year is really just holding that rate all the way through the year.

This year, the team hit 1-in-15 rate, so that's one rocket every 15 days, and sort of hovers around that 1-in-17. So it's not like unnatural things need to occur for us to be able to achieve that rate.

### Electric-Powered Pumps

**Sawyer:** You were talking about, in terms of the anomaly with the batteries, it's something that's relatively new, and that means unfortunately you're the guinea pigs to find the things that are wrong with it. But Terraspace is asking here: why is Electron's second stage powered by battery packs rather than other methods of power? What's the benefit of using the batteries?

**Peter Beck:** This is a design decision that we made at the very beginning of Electron to have it electrically pumped, and it's probably not as obvious as everybody might think.

In a small launch vehicle, propellant residuals determine the success or the failure of a small launch vehicle. Propellant residuals on a big rocket are super important, don't get me wrong, but on a small rocket, if you leave 30 liters or 30 kgs of fuel or oxidizer behind, that represents a large portion of your payload mass. So residuals mean absolutely everything on a small launch vehicle.

Electron is quite unique in the fact that we have a closed-loop system. We have level sensors in both stage one and stage two. In fact, in stage one, we suck that tank 100% completely dry. We know where the propellant is in the tunnel as we're gurgling down the last few liters of it.

Of course, being electric motors, they're able to load sense. So we use them both as motors but also as instruments. As the head pressure comes off those pumps, the load profile changes, and you can actually detect the onset of cavitation. So we sucked that first stage 100% completely dry.

Now, if you're doing that with a turbo pump and you deplete one propellant more than the other, then that ends up in a bad day with the engine. But also, if you get cavitation, you can explode the turbo pump, and it ends up in a bad day.

So with the electric pump, we're constantly modifying the oxygen-fuel ratio as we're depleting the propellant to make sure both propellants deplete exactly perfectly on time. Then we also load sense in them to make sure that we suck every last little bit out.

That's on the first stage, and on the second stage, we do the same thing. We have a closed-loop level sensor, and we're modifying the oxygen-fuel ratio exactly to make sure those propellants... we don't deplete on one propellant versus the other.

It's super easy to have 100 kgs of propellant left over, and it's like, "Well, there's your payload." So you get nothing to orbit.

If you look at Electron as a size of vehicle for the amount of payload it lifts, it's actually a really, really tiny vehicle for the amount of payload that it lifts. Propellant utilization is the key for a small launch vehicle, and we can just control that all in software, rather than through mechanical means or having to do it with gas generators and ride the knife edge. It is the thing that makes that vehicle so good – that electric pump.

**Jack:** It's really unbelievable that you're able to get every last drop out of that to get that extra oomph for the payload.

Along those lines, Safir was asking: with the changes that you've had to make after this anomaly, is that going to have any impact on either payload mass or the margins that you have in terms of fuel, electrical with the vehicle?

**Peter Beck:** This is the challenge. I can say this now because I'm building a big launch vehicle and a little launch vehicle, and a little launch vehicle is so much harder to build than a big launch vehicle.

The question hit exactly on the point – every gram that you add is meaningful to the payload. So to implement this solution, not only did we have to implement it, we had to implement it in a "no mass" way. The team's done some pretty tricky things to make sure that it really is a minimal mass.

There'll be a couple of kgs hit to the performance of the vehicle, but certainly nothing that would cause us to have any concern or inability to fly payloads. It's marginal impact. But that is the challenge.

We have debates about, "Can we afford the mass of another pressure transducer?" And then with Neutron, it's like, "Ah hell, just throw another 10 on it," and it represents like 0.0000001% of the mass, whereas on Electron, 200 grams is a meaningful amount of mass.

### Wallops Facility and Launch Cadence

**Jack:** Are there more scaling up plans for Wallops? What do you see in the future for launches from that place specifically?

**Peter Beck:** The Wallops pad was always intended to be a government pad where we do a lot of the work for government customers who don't necessarily want to get on a plane down to New Zealand and require some of the facilities that are at Wallops.

Wallops is never intended to be the super high cadence pad. That's why we have the two pads down in New Zealand, where we have complete control over that launch range and that launch range schedule. When you have to go and play with other people, you lose some of that flexibility.

Wallops is obviously where we're setting up Neutron, so the team is flat out there building pads and starting to build infrastructure out there for Neutron. It's a key site for us, but for Electron, it really is focused around launching some of those government missions. The HASTE missions generally will always go out of there, and that's really what that pad was designed to do.

### Automated Flight Safety System

**Jack:** What is the status of your automated flight safety system certification? Is there any updates there?

**Peter Beck:** Certified. Whenever we fly out of Wallops, we're flying on that AFTS system. That one is behind us. That was a marathon.

**Jack:** A lot of red tape?

**Peter Beck:** A lot of red tape. But I think on that particular project, it wasn't just about us. What we were trying to do with that is make sure that there was a system available for everybody in the future.

FTS or flight termination is just such a massive thing. It consumes a huge amount of resources and takes a huge amount of time and is a huge barrier. The AFTS that we fly on Electron is certified for Electron right now, but the idea with that is it's a commercially available AFTS system for everybody to use. NASA hold all the software. The pain that we went through and others have gone through with flight termination is hopefully reduced here going forward.

**Jack:** I love that. And the red tape, I got to say, the red tape though – it's different from the red that's painted on the Electrons that are reusable, right?

**Peter Beck:** Reusable red, yep.

### Rapid Response Missions

**Jack:** We've seen a lot of talk about rapid response missions in the smallsat sector lately. What is your opinion of that as a market or usefulness or not usefulness? How do you feel about the whole rapid response segment of the market?

**Peter Beck:** It's kind of difficult for us because that's just kind of every day for us. I mean, it's not unusual to integrate a customer the night before and go, "Okay, the weather's good," and roll a vehicle out in the morning and fly in the afternoon.

So we look at the rapid response, and it's just like, this is basically what we do normally. I think it's a good capability to have, and I think it's a good capability to demonstrate. But for us, it's just how we roll. It's not new or different; it's just, "Yep, we're launching Electron, let's roll it out."

### Additional Launch Sites

**Jack:** So you have Wallops, and you have Mahia. Do you ever have any plans to perhaps have another launch site, maybe – I'm a West Coast guy, I have to ask – maybe like Vandenberg?

**Peter Beck:** Launch sites – I mean, it sounds like an awesome thing to own, but they're just literally money holes. It costs a tremendous... they're always by the sea, so everything's melting all the time, and they just cost a tremendous amount of money to keep up-ticked and ready to go.

So the least number of launch sites, the better, in my books. Look, we'll build a launch site wherever there is a market opportunity for us. If it proves that we need a US-based West Coast launch, then the market will drive us there, and we'll go and build one.

Building a launch site for us is just no big deal, but to have one, they cost a lot of money to maintain and operate. So you're going to put that on the balance sheet, you better make sure there's a business case for it.

### Electron Recovery Efforts

**Jack:** How is ocean recovery of Electron coming? Do you have any plans, or are you at the point where you're ready to refly a recovered Electron yet? Are you still sort of gathering there?

**Peter Beck:** Surprisingly good. The base assumption that we had was that if a rocket touches the water, it's toast. That's a pretty logical and reasonable base assumption to start with. Hence the reason why we thought, "Well, let's not let it touch the water, and let's grab it with the helicopter."

Of course, we ultimately splashed a whole bunch down. As we splash them down and recover them and started bringing them back and pulling them apart, we realized, "Actually, there's not that much we need to do here to make this waterproof and marinized."

It kind of got to the point where, as much as I'm an avid helicopter pilot and I love my helicopters, it became pretty obvious that with a small number of modifications, we can fish them out of the water. And it just makes the operation so much more simple to start with.

The cost in the refurb, you trade it against the cost of the helicopter, and it's pretty well neutral. So the economics stacked up. We may as well just make it a little bit easier for ourselves.

But really, our focus has been on getting them back, getting through the wall, getting the trajectories right. The team are able to – the last one came down within 400 meters of its predicted location. So for a passively guided launch vehicle, that's pretty bloody good.

We've got that down and just passively bringing it through and re-entering it was really the hardest thing to do. Because, as you know, Falcon does a braking burn; we don't do a braking burn. So keeping that stage together and in good condition is really the tricky bit.

Once we get it splashed down in the ocean, everybody sort of just wipes their brow and goes, "Phew, that's the hard bit done." So now we're really focusing on how do we get it out of the ocean in various weather conditions without damaging the vehicle.

The team's been spending a fair bit of time on ingenious methods to ensure that we don't ironically damage the stage getting it out of the water, even though it's survived through all this heinous reentry and shoot deploys and whatnot.

I would say that a big point was being able to refly that Rutherford engine earlier this year. That was a big deal because that kind of was the last piece – can we really do this? And not only just do it, because you can do anything, can we do it economically?

So for the reusability program, the next big demonstration will be a whole set of engines, a whole first stage power pack set of engines, and then a refly of the whole vehicle. But we're plowing forward with production rate and those kinds of things. It's a nice-to-have, not a must-have for us to either reach rate but also reach the point in our economic model that we need to be at.

**Jack:** So I have to ask, when Electron splashes down in the ocean, does it then become a marine asset? Because you have famously said marine assets suck. Do they suck less now?

**Peter Beck:** They do. The most amazing thing is: one of the early ones that we splashed down, it was in the water for probably call it an hour (generally we get it out pretty quick). It was in the water for an hour, and there were freaking barnacles on the engine – little marine things attaching themselves to the engine in that amount of time.

It's like you gift it to the sea, and it automatically starts consuming it, just instantly. And that's why I hate marine assets, because you put a ship in the water, and it's just dissolving in front of your eyes. It's just literally being consumed by everything around you. It's incredible.

**Jack:** So on record, marine assets still suck?

**Peter Beck:** Suck. They're a necessary evil, I admit they're a necessary evil, but I much prefer things in the sky than things in the water.

### Reusability Plans for 2024

**Sawyer:** For the manifest for next year – first off, 22 missions, crazy. Second, there was a mix kind of there of some that were denoted as recoverable and some that weren't. Is there a reason they're not all planning on being recoverable yet?

**Peter Beck:** Totally. The vehicle is always performance-maximized one way or the other, whether it's a single payload and we've added more payloads to maximize the amount we're lifting, or the trajectories. We always consume the vast majority of the vehicle's performance. Also, some trajectories consume a lot of performance as well.

Some of it is just based on what we're able to do with the vehicle, and then also prioritizing the rate necessarily over reusability. Next year is important for us.

That manifest is as it stands probably last week, and the manifest changes all the time. It's literally like a giant game of whack-a-mole as customers... because we provide a dedicated service, we fly when the customer's ready. So if the customer's not ready, then we don't fly. We're always moving missions in and around and changing.

The manifest is a very dynamic thing, so some reusable vehicles will move forward or back and come in and out, and HASTE will go all around. But we keep a pretty dynamic game with that manifest. So don't be surprised if there are other reusable vehicles that pop up or there's other stuff that pops up as we go through the year.

**Sawyer:** What's next in terms of the steps to refly an entire booster? And Massimo wants to know: when is the potential first reflight of a recovered Electron booster?

**Peter Beck:** The next major step is a full set of engines on the first stage, making sure that we get that milestone ticked off. And then the next milestone after that is a completely reflown booster.

The actual tanks are a relatively low-risk, low kind of uncertainty for us. The things that are high uncertainty, of course, are things like engines and avionics and those kinds of things.

Obviously, it looks like a complete rocket when you've got the tubes there, but the tubes, by mass and complexity, represent a relatively small portion of it. We've been reflying equipment on a number of vehicles, whether it be press systems or vent relief systems. There've been a number of vehicles gone up with reflown components on it as we go through that inspect, refurbish, and reintroduce into production.

**Sawyer:** Maybe sooner than later?

**Peter Beck:** It's hard to say. It depends on a number of things because those reusable vehicles – the number one priority is getting customers to orbit on time when they want, and that drives everything.

When we've got reusable missions and we can do them, we do them. But if a customer has a particular requirement to be on orbit at a particular time and it's not a reusable vehicle, we're not going to push that customer away. That's really the priority for us.

### Venus Mission

**Jack:** One of the things I lament very frequently on our streams is the shortness of human lifespan, and bear with me, I'm going somewhere with this. That is because I want personally to gather as much knowledge about this universe that we live in as possible, in the solar system that we live in. I wish we could send very well-appointed probes to every planetary body and then some, and therefore learn more about our place in this amazing universe.

Rocket Lab, and I think you in particular, have an affinity for Venus, and Rocket Lab has a mission on the books to send a probe to Venus. Do we have any sort of updates with how that development is going? I know it's kind of like a side thing, but I would love to hear more about what's going on with your Venus mission, and maybe any difficulties you've encountered, and how that's all going.

**Peter Beck:** The Venus mission is most definitely a nights-and-weekends project. It's a Rocket Lab project, but also we have a number of team members on board as well, and it's nights and weekends for them as well.

We have NASA providing the heat shield for the reentry probe. We have Sara Seager and her team on the science team. We have another group that have designed and built the instrument, which is an autofluorometer.

It's a nights-and-weekends project for everybody. As a result, if I was retired, then I would just make that my job, but we've got actual customers to fly and actual spacecraft to build. Nevertheless, the project's still going well. It's based off the CAPSTONE Photon deep space spacecraft, and then there's a unique probe that's on the top.

To your point, if you look at everything else around you, it has lifespans that measure thousands of years to millions of years. I think it's a cruel thing that a human is... really, a useful human is probably what, 60 years? You're useful maybe? That's a bit unfair. But you look at everything else around you, even just like a piece of wood, and it goes longer. So it's a ridiculously short amount of time frame to get anything done.

For me, probably the biggest question I have is: are we the only life in the universe? And that stems back from the youngest memory I have or space memory I have as a child, standing outside, looking at the night sky with my father, and him pointing out that those were all stars in the sky, and those stars could have planets around them, and on those planets could be somebody looking back at you.

For a four-year-old kid, that was like, "Wow, now I know what I'm doing with the rest of my life." That was sorted. But I think it's a really important question to answer, either way, because if we want to take a pure scientific method, in the absence of any evidence, for all intents and purposes at this point, we are the only life in the universe.

Now, I don't particularly believe that to be true, but with the lack of any evidence, that's the only logical assumption you can draw. So if you could go somewhere and prove that there was actual life, then I think that changes your view on the universe pretty substantially.

Venus has this really interesting place – about 50 km altitude in the clouds – where the environment is kind of not bad enough where you could have potential for life. And of course, Sara Seager and her team's work, finding some trace amounts of phosphine, really supercharges that theory.

The whole point of this probe is to enter the atmosphere of Venus. We get about 120 seconds, and the instrument team have come up with an instrument that is basically a go/no-go gauge for life. If it's there, it will be digital – if it's there, it's yes; if it's not, it's no.

So we're not necessarily going there to make hugely in-depth scientific measurements and feed a lot of data back. There'll be a lot of data that comes back, but primarily it's optimized for really looking for phosphine and detections of life.

We get about 120 seconds before the probe's crushed and melted, and it'll be a red light or a green light at the other end. Either way, if it's a green light, obviously we need to go back again and prove it some more, but if we take it as a green light, then if life has been able to survive and thrive in that environment, chances are actually life is prolific throughout the universe.

And if it's a red light, then we best stop fighting with each other for a little bit longer because life's a little bit more precious than we thought. So either way, I think it's a super important and exciting thing to do.

We've kind of reached the point with both Electron and Photon that we can do this for a tiny amount of money. If we can do more of these kinds of missions to your point, I think everybody is much better for it.

**Jack:** Absolutely. I mean, I always say "more data, more better; more science, more better." It's become a sort of a joking phrase at this point, but I really mean it, because the more we can learn about our place in this amazing universe, the better off I think we all are.

You were just saying you have some ideas for future things you can do, and obviously the Venus mission is a weekends and side project kind of thing; it's not your priority in that realm at this time. But when you guys are hanging out around the water cooler or in the break room or having a beer at the bar or whatever, do you ever chitchat, like, "Man, but after Venus, we should do this"? Do you have any things you've thrown at the board?

**Peter Beck:** That's called entrepreneurial drift. You've got to be careful with that – scope creep.

No, Venus is a big enough thing to really focus on. But look, the cool thing is that with the Photon, that deep space Photon spacecraft, we can go anywhere that's in that near-Earth regime, whether it be a comet or an asteroid or Mars or Venus. We can sort of stooze around our solar system, which is a super cool capability.

We have the ESCAPADE missions that we're building for NASA at the moment. Those are two missions that are going to orbit Mars next year. So we love building those interplanetary spacecraft and doing that work. I think the whole team has a real deep passion for exploring our solar system and our universe.

I would love to go deeper as well. I think the Voyager probes are super cool, but let's get some stuff way out there. There's a lot to learn for sure.

### Small Launch Vehicle Challenges

**Jack:** Rocket Lab has the best and most impressive cadence of all smallsat launchers. I think that's a slam dunk; that's super fair to say, and it just shows in what you all have been able to do. Other smallsat companies and other vehicles have significantly worse track records – some have gone out of business, some are struggling.

Do you think there's something inherent to launching small satellites and having such tight mass margins that makes Electron's current reliability record sort of the maximum achievable? Do you think you guys can do better? How do you see that?

**Peter Beck:** We can always do better. Reliability is number one, so you can always do better.

There is kind of a paradox with the small launch vehicle in the fact that you have a $7.5 million sticker price, and you have to amortize all of the people and all of the processes over a $7.5 million sticker price. If you've got a $60 million sticker price, then you've got a much bigger team to amortize.

Just pick on one team like the flight safety team, for example. We can't afford to have 30 people running all the trajectories and building all the flight safety products and submitting all those to FAA. We just can't afford 30 people to do that; we need like three people to do that.

So what that drives you to is just incredible efficiency, automation, and just being really, really smart. In that simple way, it's so much harder to build a small launch vehicle as a business than it is a large launch vehicle, for sure.

Then there's the physics of it where not everything scales. We talk about a pressure transducer – that's a real thing. A pressure transducer only goes so small, and so at some point, everything only goes so small. Those things start to attribute meaningfully to the mass of the vehicle. So from an engineering perspective, it's much more difficult.

So really, if you can pull off a small launch vehicle with a high cadence and high reliability, a large launch vehicle is a piece of cake. I made the comment before: it's so much easier to build a big rocket than a little rocket. That is a truism, both for the actual vehicle itself from the engineering through to the operational and the business model. It's just way, way easier to do.

But the thing is that small dedicated launchers are absolutely required, and it's a really important market niche. The other thing I think is true is that the thing that makes a big launch vehicle difficult is not so much engineering; it's capital.

For a small launch vehicle, you can build a launch site, and it doesn't cost you that much because there's not much concrete in the ground and not much steel in the ground. With Neutron, the real challenge is not necessarily the engineering; it's just the quantum of capital and the quantum of infrastructure you have to build to make that successful.

That's why all rocket companies, probably bar none, start off by building a little launch vehicle first, and then they move to a big launch vehicle. Because to just go straight to building a big launch vehicle, you don't have the credibility to raise the level of capital that is required to actually go out and just straight-out build a big rocket because it's enormous.

The hard bit about a big rocket is the capital, not necessarily the engineering. Certainly, the business model is far easier to close than a small rocket.

### Neutron Development Status

**Jack:** It's common to build a smaller vehicle first and then go on to a larger vehicle, and lo and behold, Rocket Lab is doing the same with Neutron. It's currently in development, and in October, you guys posted the footage of the structural testing of the second stage tank, which pushed to the maximum operating pressure in that test. Where is the current status of Neutron's development, and how do you see all that going?

**Peter Beck:** Let's talk about that tank test to begin with because I think that's a way bigger milestone than people probably realize. The second stage is the most difficult stage to build for Neutron because it's literally like a paradox. It has to be the lightest, highest-performing structural vessel and also needs to cost the least because that's the only part of the vehicle that is disposable.

So you end up with the most challenging economic and engineering problems. If you can successfully build that second stage tank – you look at the first stage tank, and it's got heaps more margin and it's way gruntier and all the rest of it – it's okay.

That's the reason why we really focused on the second stage first – because you do the hardest thing first. To get to the point of getting a frosty tank and then MEOP (Maximum Expected Operating Pressure) and then actually to failure is a huge milestone. What that essentially means is that we met those test objectives, all the material science and all the material work has been done, all the manufacturing of the tank.

It sort of doesn't show it in the images, but that thing's freaking big – it's 5 meters in diameter; it's really big. It's a large composite structure that's really hard.

The way that the Neutron is architected is it's kind of a hung tank. There's no structural load path through the tank; it's kind of hung inside the first stage. Most people don't believe me when I say that tank weighs the same amount as a Harley-Davidson – it's 300-something kgs. It's nuts; it's so incredibly light.

The Centaur is an amazing upper stage, but carbon fiber is one-quarter of the density of stainless steel, so you get a sense of how incredibly light that tank is. That's what gives us the low cost, because there's almost no material in it, and it gives us the incredible performance of the upper stage of the vehicle. So that tank is really something else; it's a really big milestone to hit.

Now we look at the first stage tank, and like I say, it's much thicker walls and real grunty because it's got to go over and over again, and it's like, "Oh, yep, this isn't so hard now."

So that was a big milestone for the team. More generally, it's a rocket program, and I would say we're in the honeymoon period where hardware is coming together, and we're getting right down and dirty into the big testing.

It's always cool to have hardware turn up, and of course, you look at it and you go, "It's going to be amazing; it's going to work perfectly." And then you go out to test, and it's like, "Actually, no, that didn't work perfectly, so we need to go back and fix that."

I call this to the whole team the honeymoon period. We've got lots of hardware, and now we're breaking it all, and we're truly learning what we got right and what we got wrong, what has enough margin, what doesn't have enough margin, and then when you combine certain systems together, what works and all the interactions of those systems.

So this year's gone really well. I'm really proud of the team and how much we've chugged through, but next year is a big year for sure. Make no mistake.

**Jack:** I'm still trying to process the weight of the tank being so light. I mean, I know it's carbon composite, but that's utterly wild.

I have a personal question just because I'm maybe dumb, but the tank is hung inside the vehicle – how does the load path for the payload work? Does the payload go to a structural point on the vehicle itself, and thus the tank doesn't have to bear that load during liftoff and launch? How does that work?

**Peter Beck:** There's a payload cone, not too similar to a normal launch vehicle, and that payload cone comes quite far out to the top of the tank dome and wall. So yes, the actual payload goes down and couples in the very top of the tank down to the ring main, if you will, around the top of that stage.

But the load path is super, super clean. It's the most beautiful load path. It's kind of like you stand in front of a whiteboard and then draw the ultimate load path, and then that was the basis for starting the design of the vehicle.

In order to make the vehicle as reusable as possible, as I think everybody knows, we hold the fairings on the first stage and bring those fairings back down on the first stage. That is a really parasitic performance thing to do, so you have to find other ways to make it up to make the rocket equation close.

Because you come up with all these great ideas to make reusable launch vehicles, and they sound all cool, and then you do the math, and it's like you get 100 kgs to orbit. So it's all a giant trade-off.

If you look at our first stage compared to our second stage, the first stage looks giant, oversized to the second stage. That's because we're bringing a lot home on the first stage, and we're making sure that first stage is good to go on again and again with a minimum amount of refurb. It's just all a big engineering compromise about where you put the margins and where you put the performance.

**Jack:** I am glad that all I have to do is operate cameras and talk to people because the amount of trades you have to deal with in rocket development – it's just like the most insidious puzzle I could possibly think of.

**Peter Beck:** We call it the spiral of doom because basically, you'll be a little bit underperforming because of some structural mass, some inert mass, some parasitic mass. So you need to add a little bit more propellant to end out that mass. And then you add a little bit more propellant, you have to add a little bit more tank. And you've added a little bit more tank, so you have to add a little bit more propellant.

You very quickly can run off into areas where it just doesn't close – you get nothing to orbit or negative payload margin. It's just one giant engineering compromise. You've done your job right when every engineer is unhappy, because if somebody's happy, then they got too much.

**Jack:** I love it. I mean, there's a reason they call it rocket science, right?

You said next year is a big year for Neutron. So what are your next stages of development? You've tested the second stage tank. What's coming up next for Neutron?

**Peter Beck:** There are more tanks in development – more upper stage tanks to roll through the qual programs, first stage tanks as well to roll through the qual programs. Probably the longest pole in the tent is propulsion; it's always propulsion.

I would have said that probably the upper stage tank was one of the highest risks, largest amounts of development, hence the reason why you've seen that been prioritized. That's a good monkey to have off our back.

But look, Archimedes as an engine is going super well, and the whole point with Archimedes is to get it to such a benign operating point that you really don't have to think too hard about flying it again and again and again.

I liken it to: if you're sitting in an aircraft and you're looking out at the gas turbines on the wing, you don't expect them to be running at the point where you're not quite sure if it's going to do the next flight. We picked operating points and cycles to really maximize the kind of performance we needed but ended up in really benign operating points.

We went to a closed combustion cycle, generally associated with super high-performance engines with crazy high combustion chamber pressures, where you're trying to squeak every last little bit of performance out of the engine. We went to that cycle not for that reason at all. We went to that cycle really because if we just dial that back a bit, then you end up in a pretty benign – actually, you end up in a really benign operating point at the same kind of level of performance as, say, a GG (gas generator) cycle.

So you take an ox-rich closed cycle and operate it at GG pressures and GG performances, and you end up with this thing that's really bulletproof. That's been kind of funny because as we've been doing pre-burner tests, obviously we're flying all the oxygen through the combustion device, and generally, you're doing that at wickedly high pressures. We're like, "Nah, this is backed way off."

You end up with new problems, like extinguishing the flame because its operating point is just too benign, and having to solve those problems there. But that still remains the long pole in the tent, and the team's crashing through it. But I think we're trying to build the most boring rocket engine.

### Neutron Launch Cadence and Landing

**Sawyer:** How many launches per year are you hoping to get with Neutron? Obviously, I'm guessing that's going to be scaled up, so what's the hope in terms of how many launches per year, and when you get to that full cadence?

**Peter Beck:** I'd be hesitant to put a number on that because every time you do, it just turns out to be wrong. What I will say is that the initial cadence is following the same model that we did with Electron, and I think that everybody else has with a new launch vehicle – one and then three and then five, and kind of slowly building into the cadence.

It should be capable of reflying many, many times. The kind of customers that we're talking to for the vehicle aren't looking to buy ones and twosies; it's designed to be a mega-constellation deployer really. It's designed for quite high rates.

We're the conservative guys, and I think it would be ridiculous if I came out to you and said, "Well, in year one, we're going to fly once, and then in year two, we're going to fly 20 times." That's just not reasonable. So we'll step into our cadence and take the learnings as we go through.

But this is kind of second time around. With Electron, we had to build all of the factory production, the ERP systems, and all the boring stuff at the same time. There's so much that just directly flows straight across to Neutron; we don't have to invent a new ERP system or a new work construction system and a new production system. It's already there.

So we're already way, way, way further ahead. I'd hope we'd do a better job, but at the end of the day, it is still a new launch vehicle, and there will be improvements and teething problems along the way. That's just the reality of it all.

**Sawyer:** Is Neutron's plan only to land back on land, or would there be potential for a drone ship for a more intensive launch or for higher launch cadence? Also, what is the progress on getting that first stage to that landable point?

**Peter Beck:** In the original architecture – and this is where your engineering trades just come in – Return to Launch Site was like, "Well, let's just return them all to launch site." But actually, you chew a tremendous amount of performance to do that.

A Neutron RTLS (Return to Launch Site) is like 8-ton payload; a downrange drone ship landing is 13 tons payload plus. There'll be certain missions where return to launch site makes sense, but from an economic model, the baseline is to return back to a drone ship.

So yes, we will have more marine assets, which I've resigned to the fact of one way or the other. It's just the most efficient way of doing it. You just trade out too much payload to do RTLS.

**Jack:** Are there any plans for hop tests with Neutron, or is your first launch with Neutron just going to be an all-up, "We're sending it"?

**Peter Beck:** We'll just try to bring it home. If we hadn't had the experience with Electron, then you'd go, "Yeah, there's a lot we need to learn there." But this is kind of – I think I've said it before – if we hadn't gone through the process of trying to reuse Electron, trying to make a reusable launch vehicle with Neutron would just be an incredibly daunting task. You'd have so many unknowns, known unknowns, and unknown knowns. It would be really difficult, and you'd have to chunk the problem up and start breaking it off into various different things.

It's not the first time we've ridden the wave back through the Earth's atmosphere. The learnings – if nothing other than those learnings comes from Electron's reusable program, it will be 1,000% totally worth it – from materials, control algorithms, to understanding how vehicles actually interact with the atmosphere, to thermal protection systems. We've learned it all. I'm sure there's more to learn, but we've learned enough that we'll just have a crack at bringing it straight in.

### Neutron Fairing Configuration

**Jack:** Has there been a final decision on how many halves or quarters the fairing on Neutron will have? I think we've seen the four-petal and then we sort of saw the Hippo Chomper. Any more thoughts on the fairing configuration there?

**Peter Beck:** It's a Hungry Hippo, 100%. It's two halves. We originally started off with the flower, the four, but we changed pretty quickly as we got into the detailed engineering design into the Hungry Hippo.

One thing we did learn earlier this year: we made a whole bunch of progress on the vehicle over the last year and a half, and we didn't put out any renders because we were just busy building a rocket. It wasn't until we actually put out a render and incorporated a whole bunch of the new stuff, I think all the forums and everybody kind of lit up with, "Oh, Neutron's gone through all these changes!" But actually, no, we just haven't done a render. So we learned that lesson; we'll try and keep the renders a little bit more current. But a lot of the stuff that was new for a lot of people – we're like, "No, that was like a year old."

**Jack:** I mean, I guess it's kind of more of a nauseous hippo because if it was a Hungry Hippo, it would be eating the payload.

**Peter Beck:** Burping hippo.

### Reusable Second Stage

**Jack:** Are there any plans for a reusable second stage for either Neutron or Electron? That's like one of the most devilish problems, I suppose.

**Peter Beck:** It's just not that conducive; the rocket equation just doesn't, it's not that conducive to it. We trade so much to keep the fairing on the first stage. Putting the fairing on, keeping the fairing on the second stage – you just end up much, much larger, and your payload just suffers so horrendously.

And then you have heat tiling and reentries and all those kinds of things. Then you're in orbit now, so you actually have to time your orbital reentry point so that you land it back where you care. It's no point just landing it back in an African desert somewhere; you've actually got to land it back where you care. So you've got a whole reentry bit to deal with from an orbital targeting standpoint, which is all doable, don't get me wrong.

Never say never because I've learned my lesson, but at this point, we're just focused on making a really efficient, really high performance, and really low-cost upper stage. The reality is that 70% of the cost of the vehicle is in the first stage, and that's true with Electron and Neutron. The vast majority of the cost is in the first stage, so that's the obvious thing that it makes the most amount of sense to try and reuse.

If you can focus on the second stage and make it as affordable as possible, then actually the economics start to get pretty fuzzy at that point. That's one of the reasons why the second stage is hung inside the first stage because, as I said before, it doesn't have to carry the structural through-load of the vehicle. There's no material in it as a result, and if there's no material in it, there's no cost in it.

### Neutron Launch Pads

**Sawyer:** What's the plan in terms of the launch pads for Neutron? Are there plans to modify Pads A and B, or is there a plan for maybe building a Pad C?

**Peter Beck:** Big is the short answer to that. If you look at some recent images of the amount of land we've cleared at Wallops Island to start building LC-3, it's a big, big pad. So we start launching it out of Wallops.

At this point, there are no plans to launch it out of New Zealand. The reality is that if we take all of the liquid oxygen produced in New Zealand, we half-fill a Neutron tank once. There's just not the industrial base to support that level of project. Hence the reasons why it's launched out of the States, where we can just have a whole line of tankers turn up, and away we go.

Infrastructure has been starting to be put in the ground at Wallops, and we really love the Wallops site. It's nice and quiet, and we don't have to work around too many other folks, and we get nice trajectories there. It's actually a really, really sweet sun-synchronous dog-leg corridor, way, way better than the Cape. The Cape's sun-synchronous dog-leg is pretty energy intensive; Wallops is a little bit better. So that's good for us. We really love that site, and that's where we're focusing Neutron on at the moment.

**Sawyer:** How has it been working with them over at the Mid-Atlantic Regional Spaceport in that whole area in terms of planning for the RTLS side in addition to the launch side?

**Peter Beck:** The state has been super supportive; the state's been great. Obviously, Antares is winding up, so the state was super keen, and we built those relationships with Electron. We already have a team out there and facilities out there, so it's been super good.

### Human Rating Neutron

**Sawyer:** Are there ever any plans to human-rate Neutron?

**Peter Beck:** Absolutely. We're designing it to be human-ratable, not human-rated out of the gate. If you've got a vehicle with that amount of performance, it's silly not to account for the one-day ability to put a capsule on the top.

As we're going through the design decisions and safety factor margining of things like tanks and whatnot, that's totally on the top of our minds. Now, as to when we would do that – at the moment, there is really no market for human spaceflight. There's one customer, and that customer is well-served.

Until there are multiple customers and a real business case, as cool as it sounds to run off and build capsules, the reality is there needs to be either more space stations or more orbital destinations before you jump in and make an investment to that kind of scale. But we certainly haven't ruled it out, and we're making sure that if the opportunity arises, we're well-positioned to jump on it.

### Memorable Launches

**Jack:** We're transitioning out of Neutron a little bit here, just some more general questions. Do you have a favorite launch that you've seen in person? Any launch, any rocket? Was there a standout moment for you? What was the first launch that you've seen?

**Peter Beck:** The first launch that I ever saw was the last Shuttle night launch. That was actually the first launch I ever saw. And then my favorite launch is every successful one. Probably one of the most memorable launches for me personally was the NASA launch that we did, the VCLS launch, very early start of the company.

For a number of reasons – I think the launch was called "This One's for Pickering," named after William Pickering, who was a New Zealander who helped start JPL. It was just super cool because we had the Pickering family in mission control. As a kid growing up, to watch NASA TV – for the longest time, my whole focus and being in life was to go and work for NASA. So to actually fly one of their payloads, have a big meatball on the side of the rocket, was one of those pretty cool moments where – I didn't quite get to work for NASA, but in a different way, I still got to live the dream.

**Jack:** That's really special. And thank you for mentioning Shuttle so that we can check that off the NASA Space Flight checklist here. We have to mention Shuttle; otherwise, Crispy will get mad, and rightfully so. What an amazing vehicle.

You said you had a meatball on the side, so I have to ask this: are you a meatball or a worm person, or do you not really care?

**Peter Beck:** I'm probably a bit of both. I wouldn't swear allegiance to either one; happy either way. On the VCLS mission, we had the meatball on the side; on the CAPSTONE mission to the Moon, we had the worm. So we're ambidextrous on the logos, that's for sure.

Part of the reason why we had the worm, though, is we had no performance left in the vehicle. That CAPSTONE mission to the Moon was the craziest flight ever, and there was like a three-hour debate whether or not we could afford the mass of the sticker on the side of the vehicle or not. In the end, probably the worm was slightly lighter; that's probably how it got on there.

### Photon and Constellation Capabilities

**Sawyer:** You mentioned earlier the whole idea of being designed to build constellations, to help with the launch of satellite constellations. Is there any role for Photon in that, do you think?

**Peter Beck:** We've talked a lot about rockets today, but two-thirds of our business is actually Space Systems and building spacecraft. We have the ESCAPADE mission we talked about, where we're going to Mars. We have the Varda missions; one of them's on orbit right now, soon to be deorbited.

Then we have the MDA GlobalStar constellation, so we're actually building constellation-class spacecraft. These aren't little ones; the solar wings are 10 meters in length, and the actual core of the bus is about the size of a Mini. These are pretty significant spacecraft.

The whole goal of Rocket Lab is to be an end-to-end space company. Launch is super important; it gets all of the headlines and all the fun, and it's super hard to do, and it's super rare, which makes it super valuable, which is great. If you don't have launch, then you don't have the keys to space, and having the keys to space is super important.

But our view is that launch is just one element of an end-to-end space company. Having launch is good, being able to build any spacecraft that you want to build is good, but really, the big prize is putting infrastructure in orbit.

I think that's become very obvious for everybody – that if you can build whatever satellite you want to build, and you can launch it using your own rocket, it's incredibly hard to compete with or beat that as a business model. We're kind of gently and methodically stepping our way through to that ultimate end point.

### Future of Rocket Lab

**Jack:** The road to Neutron is ahead of you, and you're returning to flight with Electron. How do you see the next two years going, and how do you ensure Rocket Lab is able to continue and make it through the next two or three years? We were talking about earlier how we've seen other smallsat companies struggling. Space launches is not easy. How does Rocket Lab survive the next two years?

**Peter Beck:** That's a much better question. You're exactly right – this is hard, this is super hard, and launches are really hard. I would say that the industry has suffered from a lot of aspiration and not a lot of execution. What we're witnessing right now is the weeding out of the aspiration versus the execution.

Rocket Lab is not immune to that; we have to execute as well. But I think the one thing that we're really rigid on, both culturally and just in our DNA, is like everybody at this company gets measured: did you do what you said you were going to do? And I expect everybody to measure us: did you do what you said you were going to do? That's kind of the core of the company, really the culture of the company.

We're probably not the best marketing people – though we have great marketing people, Morgan and team do a fantastic job. But we're probably not the best at pumping everything up. We just sort of quietly go about executing stuff.

As a public company, we have to be a little bit more public about the things we do, but I'm sure that you can remember a number of times in our history where we've just done something and then we talk about it. Like, "Surprise, we just put a satellite on orbit in a school Photon." There's a bunch of stuff throughout the company's history where we just sort of quietly go about and execute, and I think that's super important for us.

The next couple of years are important years, but fundamentally, one of the reasons I took Rocket Lab public was: ultimately, I'm trying to build a multigenerational, enduring space company. This company can't be the Peter Beck show because, to a discussion before, everybody has an "end-by" date, either forced or unforced.

When they put me in the ground, the definition of success will be a thriving and successful Rocket Lab continuing on. By going public, you force that to happen because you have to be profitable. If you want a company to live on in prosperity and in the future, you have to build something that's actually profitable, and you have to deliver the things that you said you need to deliver and things that you aspire to achieve.

Going public for us is like the forcing function – one of the reasons and one of the forcing functions to build an enduring company. Neutron investment aside, if you take that out, Rocket Lab is actually a nice little profitable company; it's really good.

But we're making those investments into Neutron right now because we think ultimately that's going to set us up for being a much larger company in the future. I look at it in two ways: half of me is kind of happy that we're starting to actually weed out the aspirational from the executors. And of course, the downside is some people are losing a bunch of money, and there have been some just amazing engineering feats created and achieved, and teams built, amazing people have done amazing things. But at the end of the day, it's all for naught if you can't be profitable and sustainable at the end.

Capital has been flowing into the space industry, which is wonderful, but it has to flow in a way that delivers returns ultimately for everybody.