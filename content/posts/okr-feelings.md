---
title: "On OKR"
date: 2022-02-27T20:46:21+08:00
description: "" 
---

Recently, my company introduced the idea of OKR as a method of reviewing. Our chief officers came together with some objectives and some projected key results. You know, the Os and the KRs. They're all high level stuff, there were no individual objectives defined.

I read them shortly after the announcement. My firsts thoughts are that I like them, I want them to work. I'm willing to work towards them. These are great objectives and if we do hit them we'll be due a very big payday. But my previous experience with OKR kind of blocks me from going down that train of thoughts.

My previous encounter with OKR was during my last employment. It didn't turn out to be great or yield positive results for anyone around me. It got so bad that in the end we went back to our old 1-to-1 style reviews with a much shorter time frame, since the original time frame was wasted on doing the OKR. We essentially tried to do it but bailed out at the last second.

Looking back, I do have some thoughts on how certain aspects become problems that I think contributed to why it didn't work the last time. I'll describe each problem and propose a solution to it, if I can think of one. I do hope one day I get to validate if these solutions are actually working solutions. 

### Problem 1 - Conflicting objectives across teams.

This happened when the devops team had a objective to lower the total downtime caused by deploy incidents in the given year. But the product team had an objective to introduce more features than the last year. The apparent conflict here is that, assuming it's the same people developing the features the same way, if the product team wants to deliver more stuff more often, the projected amount of incidents increases proportionally with the new feature delivery rate. So, if both teams are trying to accomplish their objectives, they're working against each other. One side wants more changes, the other wants as little change as possible.

I think the ideal solution here is to give more planning time for the teams, and discuss it on a team level before setting the OKRs, so that the objectives are working together, or at the very least along side of each other. Whether this is possible at all depends on each team's attitude towards the company. If the teams don't share the same desire towards the company's success, then there's no incentive for teams to work together, after all, under this system, their compensation should be more directly linked to the key results fulfillment instead of company success. To be honest, that's what I thought was happening back then. Some teams just would rather have team/individual success rather than company success. If it's like that then it's unavoidable for situations like this to happen, but that's out of the scope of OKR and the solution to this problem is just try to plan it better beforehand.

### Problem 2 - Inconsistent high level objectives.

This one might not be a direct problem with the OKR, but more likely a managerial problem in the company during that time. I remember we had a first level objective that was to expand our services to different regions in China. After 1 or 2 quarters, that objective was dropped and replaced by another objective that was to increase average customer spend. I'm by all means no expert on OKR but I don't think you're supposed to change objectives after everyone has started working on it. Even if we do allow that, is it tolerable to change the objectives to another objective that's on a very different spectrum ? In this case it is very apparent that the replacement is on a different dimension than the original. By replacing the old one, it directly decimates any work that's done towards the previous objective and I do think it's a problem. Which lead to the OKR not working for us.

I honestly don't know if there's a perfect solution to this problem. Since some circumstances do change over the course of a year and these changes can sometimes be really wild and out of control, it is really hard for everyone to suck up and keep marching towards objectives that don't fit the circumstances. 

One possible solution to accommodate circumstantial changes might be to always add new objectives instead of replacing them. While on the surface it does seem like this is adding new stuff for the employees to do, but at the very least it won't devalue what's been done. Also, it'll remind everyone during the final review that "Hey, an objective switch happened at X and that's why I only achieved Y% of corresponding key results.". Still, this only accommodates the changes, the real problem is with the change and the objectives planning itself. Life is complex, so is running a company and I don't have all the answers.

### Problem 3 - Inconsistent audit of key results.
    
Different teams will have different key results. It's by definition that it is that way. But I think it is very feasible to have the same standard on auditing key results before it's officially decided for one member.  The problem I see was one guy who had one of his key results as "Reduce severe customer complaints", the problem I have with that was, 1) It's more of an objective rather than a key result. 2) The 'severe' part wasn't objectively defined. I don't think it was a good KR, but it wasn't my place to say. That KR went through all the way, I asked his manager afterwards about the definition of 'severe' custom complaints, the guy doesn't have an objective answer for me, all I got was a very vague response, iirc was "If I think it's causing too much problem then it's severe.". Maybe he did have a concrete definition that he didn't want to share with an outsider like me. Maybe he doesn't have such thing. By not giving me an objective answer, I could only assume.

You might think, why does it matter to me ? What purpose does this doubting sequence of challenging another team lead serve me ? Well, I think it serves me a fair review at the end of the year. If the KRs by different teams are being audited at a different standard, how can we justify that we're using the this system to give out the same promotions proportionally to the KR achievements ? How can I get a fair evaluation when other people can have vague KRs while I setup mine so that they're objective enough to review easily ? Isn't that the way its supposed to be ? These are how ideal key results should look like for me:
- "Analyze and optimize response time of 20 endpoints currently above 500ms to less than 250ms. Time should be measure at 50th percentile."
- "Introduce connection pool layer in front of the DB so that there's no more connection spikes."

I can give you more examples, but this should be sufficient enough to tell you how I think KRs should be defined. It is very apparent that the KRs should be defined objectively well since it'll make the reviewing process easier for all parties involved. It's kind of absurd to think that manager of that other team just approved KRs like that, while me, without a manager{{< link-note 1 >}}, enforced myself that I should write the KRs this way so that my review isn't screwed up.

The solution to this is fairly straightforward, just do some training beforehand and people will be better off than just randomly googling how-tos on OKR and defining without a principle. Just need to make sure that at the very least the KRs are on the same standard.

### Problem 4 - Missing clear rewards/penalties.
   
At the very beginning of OKR adoption for us, we were only told that this will contribute to your yearly review. Rewards/penalties weren't made clear to us and nobody asked. I guess people were just googling what is OKR first and didn't thought that much, myself included. There was zero incentive for achieving your KRs on time or to define them well. I think in order to make people realize how OKR can really help their work get seen is to ensure proper incentives when an individual is doing it right. But I guess that was hard at the moment since nobody tried OKR before and therefore wouldn't know how to properly incentivize the thing.

One potential solution for that was to go baby steps first. Instead of trying to run the whole thing yearly at the first try, do it by weeks or months or quarters. And after people seemed matured enough to define the Os and the KRs well, and the whole system seems to work, then move on to longer objectives such as 6 months or 1 year. Of course, figuring out the right amount of incentives during the trial runs is something that you must do as well.

## Conclusion

I don't think OKRs are hard to work with, it does give you an objective look at things, which I think is very crucial to any business. But it did have problems that prevented it from being useful the last time I tried it. I hope these problem won't get in the way this time if we decided to do OKRs for everyone inside the company.

---

1. {{< note 1 >}}Due to how my company was structured, my reviews were conducted by the CEO directly. It wasn't too bad for me since the guy used to work as a frontend engineering lead. Couldn't say the same about other teams tho.{{< link-note-ref 1 >}}
