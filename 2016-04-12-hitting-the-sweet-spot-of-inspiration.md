# Hitting the sweet spot of inspiration

Before I tell my story, I want to use a sentence to introduce myself, as this is my first Medium post. My name is Christoffer Winterkvist, I work as an iOS Developer together with a team of super talented individuals at Hyper, located in the heart of Oslo. Enough about me, lets get this show on the road.

In the beginning of October of 2015, our mobile development team went on a small trip to Krakow to attend that years MobiConf. We chose MobiConf because it covered both our platforms, iOS and Android. It was also a brilliant opportunity to get to know each other better across teams, and that turned out to be one of the greatest things about the entire trip. High profile people in the industry was in the lineup of speakers, people like John Sundell, Ash Furrow and Marin Todorov. This helped to reassure us that we wouldn’t go home empty handed. Kevin Goldsmith started off by talking about his time at Microsoft, Adobe and how Spotify was a breath of fresh air. He later talked about how Spotify organized themselves to achieve an autonomous relationship across teams, how they fuel innovation and gain velocity. This was all really interesting, so interesting that I couldn’t help myself to ask questions after the talk was over. However, it wasn’t inspiring, not in the way that I wanted anyway.

![MobiConf 2015](https://raw.githubusercontent.com/zenangst/articles/master/images/2016-04-12-hitting-the-sweet-spot-of-inspiration-1.jpeg)

When we walked home from the conference the first day, I couldn’t but help to feel a bit “cheated”, for the lack of a better word. Not to say that there weren’t good speakers or interesting topics. Don’t get me wrong, I’m not throwing faeces at neither MobiConf or the speakers that year, I’m sure that people learned a whole lot from many of the talks but this was not what I had hoped for, I was hoping to be inspired.

> inspire |ɪnˈspʌɪə| verb [ with obj. ] 1 fill (someone) with the urge or ability to do or feel something, especially to do something creative.

Day two arrived, I told myself that this was going to be the day, it included all the people that I referred to as high profile earlier, so it had too. And sure enough, Ash Furrow held a great talk about the evolution of asynchronous programming in iOS. The greatest thing about that talk wasn’t the topic, but a small tidbit that Ash dropped in. He mentioned that when you are working on a piece of software, or anything really, you are in a context, a mind-set if you will. This context is a fragile thing that can easily be lost along the way, something that made sense at the time might not make sense the next morning. It is important to not look down on choices that were made in past contexts, at the time those decisions made sense. This might seem elementary, mainly because it is, but it is important to be reminded about these things on a regular occasion. Take time and reflect. This inspired me to not judge things right off the bat and to be more understanding about the past.

I went to lunch feeling a lot more content with agenda than yesterday and was still feeling hopeful for what was to come. I was conflicted about which talk to go to next, it was either Power up your animations or Platformizing UI code — the Spotify feature system & view frameworks. I ended up going to Power up your animations, but I left very early when I realized I had already seen the talk just a few weeks before at realm.io, and I’m glad I didn’t stick around. When I walked in, the talk had just gotten started but John had already captured the crowd with his super positive approach yet laid-back way of describing the topic. John promised that he would give us, the audience, five valuable tips on how to improve our implementations, and boy did he deliver on that promise.

If you haven’t seen the talk, head over to MobiConf’s YouTube channel and watch it, for there will be spoilers beyond this point, you have been warned.

The first tip that really intrigued me was view models, this is not something new nor is it revolutionary, it has been around for years. I’ve read about the benefits multiple times, but the context has never been correct for me. I only saw the theoretical gains, this was the thing that I needed to have an eureka moment. The second tip that really resonated was to have a centralized navigation system. John only showed small hints of code in his presentation, but that was more to underline and to avoid any confusion surrounding the things he was referencing. Majority of the questions during the QA was about the central navigation system and people wanted more. They wanted implementation details and/or concrete code examples, I did not. I liked that he left it open to interpretation. If he were to show too much, you would end up copying that as a foundation and never test the limits, you’d box your thinking.

Again, couldn’t help myself from asking a few questions afterwards. I walked away feeling empowered and hungry for more, doubts about the agenda didn’t exist anymore, the next meal would have to be Components & View Models in the Cloud — how Spotify builds native, dynamic UIs, the rest didn’t matter anymore.

This was an extension of the first talk and focused on the subtopics that I found most intriguing, it was tailored to my curiosity. When MobiConf was over, I couldn’t stop talking about it and all the possibilities! It sparked a creative flare in my developer soul. We went out to grab a last supper before heading home to Viking-land the next morning. Talks continued but soon shifted over into more social small talk, the context had shifted.

![Strolling in Krakow](https://raw.githubusercontent.com/zenangst/articles/master/images/2016-04-12-hitting-the-sweet-spot-of-inspiration-2.jpeg)

The next morning my mind and body went into semi-auto pilot like they usual do when you’re heading home from abroad. It all went smooth until I sat down in the airplane seat, where I usually just chill until I eventually fall asleep (yeah I’m one of those a-holes who can sleep on airplanes) But I didn’t this time. Something was different. I started thinking about yesterday’s creative flare, the spark of inspiration and about past contexts. I reiterated over everything that I had seen and learned, everything still made sense as the context was still intact. This is how I knew that something was in the making.

As soon as we had reached the right altitude and the seatbelt sign was turned off, the laptop came on. Never in the history of an eager nerd had a computer booted that slow. When the login screen finally appeared, me and a fellow co-worker started ironing out the details and began typing the first lines of code in a fresh Xcode project. There is nothing quite like it.

This was the birth of Components.

When a mumbling voice appeared over the speakers I didn’t pay much attention to it. However soon there after the seatbelt light turned on. I realized that the mumbling voice had been the captain, informing us that we were approaching our destination. I might just be the only person in history of aviation to go, “no, not yet, I’m not ready to land”. This was an odd feeling, I mainly didn’t want this because we were in the middle of something that felt important, it had a purpose and the world deserved Components. I was terrified that the context would go away. Luckily, we didn’t have any luggage so going from the terminal to public transportation when really smooth. When we sat down on the Airport Express train, we continued on. By the time we reached downtown Oslo, the first working prototype was done. It didn’t do much but it worked, it felt like victory.

A renaming took place when we decided to give credit to the people who inspired us to build it in the first place. The most fitting name that we could come up with was Spots. As you might already have figured out, this is an homage but it also works semantically. A spot can have many variations, they come in all kinds of sizes, they can be stacked, lined up or come in a form of a grid. We tried it out for a while and the name just stuck.

![Spots by @hyperoslo](https://raw.githubusercontent.com/zenangst/articles/master/images/2016-04-12-hitting-the-sweet-spot-of-inspiration-3.png)

Without going into too much technical detail, Spots is a subclass of UIViewController. What makes Spots great is that it infers a reusable and generic pattern when building applications. You don’t need to build data sources for looking up which cells should map what data. The generic view model that comes bundled with Spots can be used for anything that conforms to a specific protocol. This opens up for all kinds of possibilities, like refactoring a view to be a grid instead of a list, with minimal amount of effort. Or having different layout depending on what kind is specified on the model. It also supports preprocessing of view heights and height caching for increased performance. This comes in handy when building views with dynamic heights, like a chat or a feed. Last but not least, because of its internal architecture, it can parse JSON into native UI. This makes Spots incredibly flexible and the possibilities seem endless, you can move view models into the cloud, speed up development by working in a playground while you creating your views, or for mocking UI tests.

We wanted to build something that would give you more time to focus on what is really important, and fun, building the views. We listened to John’s words of wisdom and stuck to them. One important goal was the decoupling views and models. We aimed to get rid of manual data source handling, and if you really need to modify the data, it should be as easy as inserting something into an array, passing updates to the corresponding UI element should just be handled by the system and the view should redraw the necessary parts that went into the mutation.

But for Spots to be successful one key feature was still missing. We needed a centralized navigation system. And again, we went back to the Platformizing UI code talk and took further inspiration. We ended up creating a new library we called Compass: A URN based navigation system, with a registration mechanism that is inspired by Ruby on Rails. This was intended to be a supplementary tool to help Spots control the application but it ended up being so much more. With this library, we could achieve deep-linking by decoupling controllers. What this means is that you could potentially open any view from anywhere. Handling loud push notifications with corresponding actions has never been this easy.

So, if you got this far in the story, I’d like to leave you with a “one more thing”. The components that were mentioned are available today. Both are open source and are available on GitHub.

Now that I’ve shared my story, shamelessly promoted our work, I’d like to give some words of wisdom. Contexts are fragile and complex things, if a context feels good, make sure to enjoy it. Be kind to people that includes you. If you find inspiration run with it. The only one stopping you is you. Eat your vegetables.

Thank you for reading.

You can find me on Twitter @zenangst and on GitHub

**References**

- [Spots by @hyperoslo](https://github.com/hyperoslo/Spots)
- [Compass by @hyperoslo](https://github.com/hyperoslo/Compass)
- [Brick by @hyperoslo](https://github.com/hyperoslo/Brick)

**Fun facts**
- 90% of this article was written on a bus and/or subway, on my way to or from work, using Notes on iOS.
- Spots was written in the clouds.
