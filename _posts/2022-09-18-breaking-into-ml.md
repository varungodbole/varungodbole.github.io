---
title: "How do you break into a career in machine learning?"
date: 2022-09-18
---

I often get this question, so I thought I’d write a blog post about it. As a disclaimer, my own journey was fairly idiosyncratic. It’s unclear how easy it’d be for another person to precisely emulate it. I got lucky with being in the right place at the right time around 2015 when deep learning was taking off. Otherwise, I’m not sure that I’d have a nature paper, nor would I be on this current team. Having said that, there are lessons I’ve learned that I think would be very helpful for you. I’ve also paid close attention to the overall recruitment dynamics due to all the mentoring I’ve done in the past 5 years. This post explores some of these ideas.

## 1. There are many different types of machine learning roles.

There isn’t really one single role/archetype that captures the work done in machine learning. There’s a spectrum spanning from “pure” to “applied” roles. Teams like Google Brain are at the extreme end of the “pure” side. Teams like the Google Docs “next document” recommendation system are at the extreme end of the “applied” side. There’s also a spectrum between teams that train models and teams that build ML infrastructure (e.g. JAX, TensorFlow, etc.).

Initially, most people often ask for advice on breaking into a “pure” ML role. However, it’s often because they’re simply unaware of the opportunities available on the applied side. Assuming that the mentee in question is a general software engineer with no PhD or research experience, it’s a lot easier to break into applied teams first. These teams often place a higher premium on experienced engineers possessing a general array of skills. I’ve seen many managers of “pure” teams that often just want a research scientist with a specific mathematical background to help them develop theory.

Your best bet is to find a team on that “pure”/“applied” spectrum that will value you the most. And then build expertise and credibility that you can leverage to incrementally move to different parts of the spectrum.

## 2. Deeply understand how your work does/doesn’t create business value
All healthy organisations irrespective of whether they’re in industry or academia, offer their members an incentive gradient specifying which behaviours lead to reward. Knowing how to form hypotheses and having an appreciation for problem formulation is an essential skill. Thai is independent of whether you’re on a pure or applied team. Doing a PhD seems to be a predictable pathway for learning these skills. But it’s not the only way. It’s possible to cultivate these skills even if you don’t have a PhD, and if you find yourself on an applied team.

If you’re on an applied team, take the time to understand how your ML actually creates business value. Build empathy for your org’s leadership, and the outcomes they’re trying to create. Craft the minimal set of ML work necessary to achieve those outcomes. Done effectively, this can provide the skills necessary in problem/hypothesis formulation. Cultivate a deep understanding for how marginal improvements to the model’s performance on your validation set generates business value.

For example, if you’re on a scrappy growth team, it might not make sense to train very large models and do expensive hyperparameter sweeps, if you’ve reached a regime of diminishing returns. Perhaps the team would appreciate a simple random forest that’s “good enough”.
Adopting this mindset is also helpful for learning the “human” or “organizational” dynamics involved in solving problems in industry. These problems are often also present in pure ML teams.

## 3. Help other people achieve something in the same vein as what you’re trying to achieve for yourself.
This is an important hack for “manufacturing” your own luck. It’s certainly been very helpful for me. Suppose you want to get better at tuning models. It might be that there are other teams/engineers in your company/org that know less about tuning than you. Go help them with tuning. Or perhaps help to unblock them from model development. Even if you don’t know “anything”, there’s probably something valuable you can share. There are no two teams that are exactly the same. You’ll probably learn something new as you attempt this, which can be integrated into your toolbox for the future.

It’s extremely difficult to measure the short-term benefit of expanding your knowledge in this way. You shouldn’t disregard your primary responsibilities when you do this. But longer term, this inherent pro-social behaviour creates a profound upward spiral.

## 4. Stay focused in developing “expertise”.
There's so many exciting things happening in ML right now. It's easy to get pulled in a million different directions. A side-effect of this cambrian explosion is that it's relatively easy to become an "expert" in a given sub-domain in the space of a year, either in your org, company or the industry. For example, I don't really consider myself an "expert" at tuning models, or applied model development. There are people at Google that I consider the true “experts”. 

However, over the years I’ve used the strategy described above to proactively help lots of people in solving specific classes of problems. This afforded me a level of “deal flow” of information, which helped me identify more opportunities for getting involved. Eventually, people across our org started automatically deferring to me for those focused sets of problems, and sometimes even adjacent issues. It’s not clear what the natural limit to this philosophy is.

Eventually, I’d cultivated enough “credibility” that could be leveraged to do other things, or compounded to generate new areas of expertise. For example, I once cashed in on this reputational capital to convince a bunch of teams to engage in a tricky migration. I had absolutely no formal authority over any of these teams. There was a lot of grumbling, but by this point they all trusted me. The migration ended up being a huge success, and it only increased my reputational capital. Even if it hadn’t worked out, I’d generated enough goodwill that everything would have probably been fine.

Don’t underestimate the combination of focus, compounding and pro-social behaviour. You can use this to manufacture your own luck, and break into new opportunities.
