---
title: "PM Types"
date: 2021-10-22T21:41:01+08:00
description: ''
---

My programming career has reached its 4th year in length (At time of writing). Within these years I have come across numerous PMs (Project/Product). Recently, my company has had its fair share of PM rotations. To be more specific, 2 left, 1 came and left, 1 came back to fill the void for a month and 2 came. When I discussed this uncertainty of PMs with my supervisor, he did mention something close to this:
- "Good PMs are hard to come across, even more harder to judge during recruitment. We judge them to the best of our perceptions, try working with them for few weeks and see if stuff pans out alright."

After a while I randomly thought, this whole process is very expensive. An average hiring process in most companies I've worked with is roughly 3 months (between resume received to actually getting onboard). For each candidate we also need to spend at least 10 man-hours judging them in various forms (looking at their resume/interviewing the candidate/group discussions). After all that, my experienced colleagues who has 2x my work experience still have next to no idea about whether the candidate will work with us.

With that being said, maybe a recollection of my past PMs would come in handy for us fellow programmers. If we were to hire one or judge one.

Before we start, there are some points that I would like to make clear to the readers.
  1. The difference of project managers and product managers would not be addressed in this post. Since I've never been in an environment where this concept is applied, (i.e have both positions at the same time and operating supportively both ways.) my understanding of this differentiation would be inaccurate and therefore misleading. The "PMs" I've come across all works on the same stuff and there's no separation despite different namings.
  2. The types are ranked by head counts. The more common the type is, the higher it will be.
  3. The types are named by initial letter of the first person that I've thought of in that corresponding type.


## Type P - Mailing it in proxies

These PMs just mails it in everyday, pretty much just proxies everything they heard, unprocessed, to the corresponding recipient. 

When I'm forced to work with PMs in this category, I often find myself waiting for some confirmation on details of varying sizes, such as how would spec.X work together with spec.Y when they seem to clash functionality-wise just by looking at the requirements, or how should button.X behave when the user clicks it. 

Since these PMs don't try to understand the feature themselves (they're mailing it in, right ?), the programmer who has to implement this cannot get a direct answer from the PM, they have to proxy the question forward and then proxy the answer back. I feel it's catastrophic and kills any possible development momentum a developer might have.

My best shot at facing these PMs and getting stuff done on schedule is to go above these PMs, essentially skipping the proxy. In a stiff organization this might not work due to responsibility concerns, but if I'm in pursuit of getting something done for whatever worthy reasons, I'm gonna go out and grab it. (Since I evaluated that it's worthy)

Another way to deal with these PMs is just letting them know that they absolutely have to think about the problem themselves and provide answers within a reasonable time, if they have their stuff together then this should be doable in most cases. However, this method will need extra time to be effective, since you're asking someone to do more. So far, I have only come across 1 PM that's effected this way and is on her way to solve difficult problems.

## Type C - Chill about everything, sometimes unrealistic

PMs in this group are some of the nicest individuals I've ever met, but to be honest, based on my observations, I'm not sure if being nice to everyone is a good way to get things done in a software company.

They're sometimes torn in between the feature requesting party and the corresponding implementing/engineering party. As they're very nice people, I do feel bad for them sometimes, but it is their job to resolve differences between the two parties in order to get things going. But only so much can be resolved by one person, and more often than not, the resolving direction is very political and cannot be coordinated by one PM.

One perk of these PMs are, since they don't beat around the bush and is solving problems or figuring out ways for people. Most of the times, if you just tell them your actual difficulty/problem/blockers, they'll understand and try their best to work around or with it. On one circumstance, I even told one PM that his boss (my boss) is paying me too little for me to sacrifice my holiday time for xxx and it is very okay to resolve xxx on the next working day since we're not losing money. He took it in and he convince the requesting party, a truly win-win solution for both me and him. (No overtime for me, no extra work to check my work for him.)

From observations, I think they're somewhat tolled/stressed out during their careers. Some coinciding facts are:
- They take much longer smoking breaks during work than average, either in quantity or in length.
- They come to work late, and leaves even later than what they're accounted for. (ex: Come to work at 11am instead of regular 10am, leaves at 9pm instead of regular 7pm, or a shifted 8pm for late arrival.)
- They have taken a step away from everything after they resigned from their positions. They either stopped working as PM for a while or just have themselves a nice long break that can be as long as 6 months.

The above symptoms applies to 2/3 of this group, I think that's a fair representation. I personally have had little to no problems working with these PMs, but I'm a little concerned about their mental health.


## Type M - Hysterical, lacks basic field knowledge

The two points in the title are very independent on their own, but as a result I find them tied together in the PM circle. The hysterical ones and the ones that lacks very basic field knowledge are, from observation, the same ones.

When working with these PMs, I find it very hard to think things through due to their hysterical behavior. They just won't stop inquires for their requests. Such as a "How is that API of yours coming up ? Is it close to ready ?" every 10 minutes or another "I see you editing on the document, how far is it from done ?" every 10 minutes. I might've exaggerated a bit but this illustrates the picture well. Even when you give them a exact time for progress, they still comes at you with some supposedly light-hearted checkups, something like "Whassup, letting you know that you said you're gonna deliver X at HH:MM" or "Can I have a preview of X ?". This is extremely interruptive for some reasons
- I usually have a list of things to do, your stuff is on that well-kept list, if it's more important than something else then it should've been already scheduled accordingly. Inquiring for anything most likely stops that list from moving and therefore keeps your thing from being processed. Which is going against your target as a PM.
- If I have questions working on your stuff, I'll just fire away since that's usually the fastest way I can get through and deliver. Regular checkups is grossly inefficient. Plus, the real problem here is most likely the planning didn't go well enough so I have questions for you.
- When I gave a time to someone, its a commitment that I put on myself for them. Constantly reminding me for these commitments does more harm than good due to breaking up whatever flow I have at that exact moment. I'll let you know if it's done or I need more time.

But I guess another angle of this is that when your thing requires some effort from another team, their progress is usually relayed pretty quickly across teams. While it's very challenging, I guess if these PMs can strike a balance then it could be beneficial for all parties involved.

Another aspect of this type of PMs are their lack of basic field knowledge. This essentially leads them to become a proxy just like type C. Which I'm not a fan of and I don't think that's a right path for PMs. 

One absurd case for not having the basic field knowledge that I can think of is when I was working on a commission distribution system. After a month on that, I had the system test against the distribution formula that was given to me. The distributed commissions didn't make sense (tldr: the commission would eat up **all** the profit) under certain conditions, I asked the PM to double check the numbers with problematic examples and it got to the point where we had to go to our boss and have him show us the actual commission calculations. Had the PM got any basic field knowledge of how the industry works, this problem wouldn't get out of hand like that.

Another case was that one PM had one feature developed completely just to revert it. Apparently "it did not meet the requirements" (Said by our boss, minutes after deployment), even tho everyone developed to the spec. The PM asked to revert, and the way that she asked for it sounded like it should be as easy as flipping a book. 
> "Hey <DEVELOPER_NAME>, just revert it for now first." - The PM

That implied that the PM not only did the feature wrong, but also doesn't know how reverting can come in very difference magnitudes. Luckily, this one was only a code change and no data migration was involved.

As a programmer, if there's only a handful of these PMs working like this in your working environment, then one can try converting then to do better just by telling them the concerning points like how I listed above. Any sensible person should be trying to improve, some just need pin point directions. However, if your working environment is consisted of PMs that work like this with little to no role models, my suggestion is to look for another job if situations permits, since there's only so much one programmer can do.

## Type S - Stupid and naive
The language is a bit strong on this one but I'm thinking that we've all been there at some point of our careers. There's always this one PM that has no clue what all parties want out of a certain feature/request. With or without some very naive thought processes.

The most recent one I have in mind was a supposedly experienced PM who had worked for 5 years. I recall during one feature discussion we had, at one point we brought up more than 5 options to supposedly do what the requesting party needs, and the requesting party have no opinion on which way to proceed and the meeting is just stuck with everyone staring into the celling. I can't stand it so I asked PM to make the call here, since someone's gotta make the decision. The PM thought about it for like 30 seconds and just went with option 1 which is a little more work for me, so I asked for the PM's reasoning behind this. The reply I got was "I thought everyone's okay with everything ?".

Yes everyone was okay with everything, but how do you even convince yourself that you made a good decision for the company or for anyone ? The lack of opinion and the void thought process is the concern here. When you gotta make decisions you have to make them and take responsibility since that is your job.

Thankfully, the PM I described got fired not too long after<sup>1</sup>, and I do not get this type of PMs very often. But when I do, they're out of my sight fairly quickly. I can't be sure how I'll be when I'm forced to work with one for a long long time. Maybe I'll just try to avoid them as much as possible.

## Type K - Micromanaging 
This is also a once-in-a-while type for me. I've only encounter one PM that I could fit into this category. The symptoms are very obvious and I knew that I'm being micromanaged from the very first implementation that I'm trying to deliver.

There's just so much confirmations that the PM is trying do. The time I use, the implementation of certain parts in my code, even down to the level of "I need to see your if-else conditions for this action". I felt ridiculed. If this detail mattered so much, the PM should just have it extremely well defined and have the QA or I test for it. Micromanaging how I do things is not the right way. I could write a spaghetti block and as long as that works to the spec, there is no problem on the PM's side of things. The spaghetti is my problem as a programmer. Not something for the PM to micromanage on or even worry about. I'm getting disturbed for no reason and at this point it does more harm than good.

The good news is, eventually the PM got off this habit. I didn't even talk to the PM about it, I only briefly mentioned it to my mentor. So it's either my mentor asked the PM to lay off or the PM somehow got wiser. If it's the former then I thank him for that, since it's technically my responsibility to work and bring problems afloat.

Now I look back to those times and I think there's some easy fixes to it. For one you can just assure the micromanager that you're going to deliver what should be delivered, and after once or twice it should become obvious that there's no need for micromanaging.

Another way is maybe to just endure it and let it rip for a while, and some uncaught mistakes will surely happen, and when that happens it should be very clear that the responsibilities and works should be separated for a fair blame game. The PM should then recognize that micromanaging serves no purpose other than for them to take extra engineering responsibility and should probably stop doing it. Do note that this probably doesn't work in a [blameless environment](https://codeascraft.com/2012/05/22/blameless-postmortems/). Since it should only work when there's some type of blame or equivalent pressure.


## Conclusion

Each individual is different, PMs are people too, it's impossible to just group all of them into merely 5 groups. I only grouped them based on my perceptions of some key points that I think are most common and are interesting to me. If I were to have accurate groups in this article, each of them would have 1 group.

I think the key takeaway for all these PMs is the ability to have objective communications, as a programmer I need to feel at ease when I'm trying to communicate with one, and when I try to stay objective about stuff, the conversation should feel pretty swift and both parties can strike a reasonable balance according to the objectives. I feel like if any PM can do that, they're in a good spot already and they should only need some other minor pieces to work efficiently in any given environment.

---
1. It's actually outrageous how he got fired. From my understanding of the matter, during a discussion with one of the team leads, he directly used the team lead's computer and replied to a Slack thread using the team lead's account. Yes, in the most blatant way, 2 guys having a conversation and one just peeked at another one's computer and just started typing with the owner witnessing the entire sequence. I'm just gonna leave it here and let you think about the outrageousness level for this matter.