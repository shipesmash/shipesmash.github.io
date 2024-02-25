Steve Klabnik posted a [great overview of how BlueSky and the Authenticated Transfer Protocol (atproto) works](https://steveklabnik.com/writing/how-does-bluesky-work) yesterday. I’m enjoying BlueSky so far and now I have a better understanding of how the protocol backing it works and the potential the technology has for creating new social experiences online. If you’re not familiar with atproto yet, read Steve’s post first.

I’m not smart enough to have a lot of thoughts on the tech-side of atproto or how BlueSky is using it today but the post did make me think about how all this can improve on some challenges current social media services have.
# Current Incentives for Moderation

Facebook, twitter, instagram are all “free” today. You pay these services with your attention by letting them show you ads, promoted posts. They also control the order you see those things in and how often you see them. This is certainly *a way* to make money but it comes at the cost of the end user’s safety and mental well-being. Further, these services are motivated to moderate content just enough so that the companies paying them for ads and promoted posts are not seeing their ads show up to objectionable content. Nestle doesn’t want to see their ad next to Nazi propaganda but they don’t care if 10 people sent you death threats yesterday.

There are some tools available today for individuals to have more control over what they see on a social network but they often have to rely on hacks or access to a service’s API. As we’ve seen with Twitter, API access can go away in an instant. The interesting part of atproto is that the same tools are available to an organization running a network or an end user consuming content on that network. Feeds and labelers on atproto can combine to filter things any way you want. Are these things easy for the average person to configure? No (not yet at least) but that’s where things get interesting.

# Productization of Moderation
On an atproto-based network, if you are suddenly the internet’s main character, you can quickly switch to a new feed that only shows you replies from, for example, people who have been following you for more than a week. Bam, you’ve cut down the garbage flowing into your life in just a few minutes. 

How did you find that customized feed? Was it something provided by the service you’re using or built by a third-party? Atproto is exciting because it allows the people who want moderation to implement exactly what they want. I can use a feed built by a friend or pay someone else to build or run a labeler. Moving moderation control directly to the people who want it will improve both the availability and quality. I’m not stuck seeing whatever Facebook’s high court of moderation has decided is appropriate because I have the same access and information to curate exactly what I want to see or not see.

There are many questions to answer and I think this is the source of some of the hand-wringing around “BlueSky’s moderation is no moderation” or “BlueSky’s moderation policy is to make you figure it out yourself”. For atproto, I think a service should be transparent about the content it does and doesn’t allow and then provide basic moderation tools to end users to further refine their feeds. For now we’ve only seen BlueSky start to tackle these things and there are many more questions to answer still:

- How do you make it easy for users to find filtering and labeling services?
- How can filtering and labeling services be packaged to meet certain moderation goals?
- How can users fine-tune moderation services they’re using to get exactly what they want?
- How can you make moderation portable between different atproto-based services?

# Wrapping Up
Atproto is a brand new concept for moderating content in social settings. Its flexibility allows each user to fine tune the experience they have both in a single service and across multiple services in a way that hasn’t been possible before. 

The first social services using this protocol have a greater than normal responsibility to make sure these tools are available for their users and work as expected. While atproto has a ton of potential, if the first services using it are perceived unmoderated wastelands or too much work to use without being a software developer then this technology and all its potential may never expand beyond BlueSky.
