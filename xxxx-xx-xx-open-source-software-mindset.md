# Open Source Software mindset

A while back, in a company far far away, more accurately Oslo, Norway, a development team made the decision to try developing applications with an Open Source mindset. This company was called Hyper.

## transparency vs translucency

When we say Open Source mindset, we don't mean Open Source by default in the way that Artsy has gone. One part of their mission was to achieve transparency, where as we strive for translucency. The main difference, in my opinion, is that our customer base is different then theirs, not to say that transparency is not the end goal for us but we had to start somewhere and it felt like a good middle ground. We as a company have great admiration for everything that Artsy have done and continues to do for the community, they are pioneers within their field and we couldn't find a better place for inspiration.

We wanted to include people in the same way as Artsy but instead of inviting people to develop applications, we went for the obvious, to develop component. One core fundamental difference that we wanted to make, was to give the component a stage to shine. Developing on our components should feel as important as developing an actual application. We spend a long time with branding, such as, finding an appropriate name, the same process that goes into building an application. We strive to have good well-written README's that are both fun and informative. We create artwork for our components to make them shine even more and last but not least, we give them an icon to make them feel at home with the rest of the family. All these steps might seem like a lot of work with very little gain, if so, then I'd have to disagree with you. You wouldn't cut any corners when building an application would you? So why shouldn't a component get the same treatment. One could even argue that components are even more important that applications as the lifespan is far greater.

## The first step

Going Open Source wasn't a hard decision to make, nor was it hard to actually start doing. It felt like the next logical step for us. Sure, there were some bumps in the road but that is common when changing and/or improving an existing workflow.

Of course modularity can be achieved without Open Source, but we wanted all the gains involved. There is certainly an increase in difficulty when building components that should have a wider use-case than our own, but we, as in Hyper, are not known for backing down from a challenge. Go big or go home came to mind, but being translucent with code can be daunting, I'm not gonna lie to you, we were terrified at first, having doubts and started second guessing ourselves.

What if people didn't like the things we created, what if no one uses the things that we made, what if people found bugs, what if people blamed us for it, and worst of all, what if people ended up hating us. The list of `what if`'s just kept on growing.

You have probably had this feeling at least once, it is perfectly normal. We found comfort by thinking that surely, not all citizens of the Internet are born with a grudge towards their fellow man. So by making this U-turn with our way of thinking, we started day-dreaming about all the incredible things that could happen when you invite the entire world to be your co-workers. All of the sudden, the possibilities felt endless.
We also found solace in that we weren’t the first ones to do this.

The first modification that we had to apply to our existing workflow was to speed up the process of creating a new component. The logical first step of improving it was to start linearly by making a convention that all components should conform to, a well structured project template with some fairy & Ruby magic sprinkled on it. That turned out to be just the thing to solve this problem. To add a bit of customization, the script asks for a few parameters before applying its magic.
The mundane first step was now a thing of the past.

## Think different

The biggest impact it had on our existing workflow was that we no longer worked in a self contained project. There were a lot of jumping back and forward at first. We improved this by adding example projects to the component repository to reduce the jumping. We didn’t know it at the time but there were more benefits to be had with that change.
Some of our projects are large, as in, 5-6 minutes Swift compile-time large. So by moving the main development into the component and example projects, we could get the job done faster. This also ensured that the component could work on its own outside of our project, by freeing us from our own bounds we started thinking in different ways. The best way of describing it would be the to compare it to something relatable to everyone.

Think of it like a newly purchased box of LEGO's, instead of just building the illustration on the box, we could start tinkering and modifying the individual pieces, shaping them into a polymorphic entity which made them fit into combinations that seemed impossible before. Like turning an airplane into a space craft, the sky was no longer the limit.

The next thing that we had to improve upon was our way of thinking.
We had to improve the way we of build new features, deciding very early on if it is something that has reusable traits. Going back on such a decision at a later stage can be easy or difficult depending on if you stick with the reusable open source mindset all the way through.

So when is 1.0.0 ready? That is something that only you can decide. Have clear goals in the beginning on what you want to achieve is always a good thing. You need a set of core requirements so when the time comes, you know where to draw the line. But do plan ahead, make milestones, this gives people a nice indicator of what the future has installed.

Now that the first initial release is out the door and you see that people start using your component, the hard part is over right?
