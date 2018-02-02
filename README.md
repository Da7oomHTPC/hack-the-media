# Hacking Engineers and Engineering Media
### Background
There are many ways to “hack” software engineers by influencing media sources and fellow community members.

This document collects examples of intentional and unintentional hacks of software engineering information sources like Hacker News, Reddit, and tech blogs. The hope is to unbias these sources and provide antibodies to engineers so that they can make better personal and team decisions. (For more background, see this introductory essay - COMING SOON)

Contributions are welcome (see our [guidelines](contributing.md)).

### General Notes
- Key questions to ask with any media
  - Why are they writing about this topic and how do they and/or their sources personally benefit? Always need to understand the personal motivation of writer and their sources
  - What is the technical background of the writer? A surprising number of people with little subject matter expertise have strong opinions on highly technical topics
- **Reader Interest is King**: When something is heavily covered, it is often due to large reader interest — not due to the importance of the event for you
	- Editors and especially social media algorithms focus on engagement as it maximizes interest and revenue; also, a key reason for confirmation bias, filter bubbles, and technical hype
	- Rather than thinking of news as mirror of what’s going on in the world, think of it as mirror of what people (or on FB/Twitter, you alone) want to read/hear
	- This is a key reason for so much content about hyped topics like blockchains, AI, or the latest frontend framework
- **Issues with Online Democracy**: Social networks algorithms and voting mechanisms generally treat each of us equally, which diminishes how much voice is given to experts; often an issue on deeply technical topics
- **Empathy Gap**: Media and social media forums often have little empathy for the “other” side, as a given audience prefers to see themselves in the best light — and it is more engaging to see opposite side in worst light (see many cryptocurrency communities); algorithms and even editors cater to this. Leads you to a deeply flawed view of other side, which you need to consciously correct for by favoring moderate voices on the "other" side
- **Fact Distortion Field**: Motivated parties often create a "fact distortion field" in media that justifies their parochial views; they do this by encouraging content that supports their views and paying scientists/engineers to support these views
- **Building antibodies**: Scientists and engineers deeply benefit from getting things “right” in their job; to do the best job, critical for us to identify ways our data sources are influenced — and how to partially unbias them

### Sources and Hacks
## Social Media
#### *Reddit and Hacker News*

**How it works**

- Anyone can join and vote in community, with everyone’s vote counted equally
- For new posts, the number of upvotes soon after posting determine placement in the front page ranking
- Comments are similarly upvoted, with early comments generally advantaged over later comments
- Goal is to favor content that is likely to be heavily upvoted *for the community of upvoters*
- (Popular input source in startup communities and for junior engineers)

**Example hacks**

- **Upvoting Ring**: Asking your friends and supporters to upvote (common in dev tool companies, training programs, incubators); this can work despite countermeasures that social networks undertake
- **Confirmatory Content**: Creating content that justifies pre-existing views or financial incentives of subreddit holders; see what popular views are before, and ape them (example: [cryptocurrency subreddits](https://twitter.com/fehrsam/status/892429946550837248) that promote their own currency, and discredit competing currencies)

**Other issues**

- **No more experts**: No distinction for experts versus others; one layman has the same voting power as the world’s most thoughtful expert (Example: a non-engineer vs. the world’s most thoughtful database expert on MongoDB posts); readers may also not take the time to understand background/expertise of writer
- **Militant Minority**: Upvoting and posting community is likely small compared to readers, providing lots of power to a small group of motivated users; motivated users are often people who personally benefit from post
- **Different Needs**: Ideal tools for one group/use case don’t map to another group/use case, even though both share the same social network (Example: frontend engineer’s database preferences for a hackathon vs. backend engineer’s database preferences for production, [TDD and the needs of consultants](https://news.ycombinator.com/item?id=14664311))
- **Tribalism**: Tribal behavior by key influencers can determine how certain topics are received (example: Though HN was quite negative to MongoDB, what would the reaction been if MongoDB was a Y Combinator company?, [How does one cryptocurrency subreddit approach another](https://twitter.com/FEhrsam/status/892430348285427713)?)
- **Clickbait**: Decision of clickworthiness made on title alone, leading to incentives for clickworthy titles and easily explained content
- **Extreme “other”**: Lack of empathy for other side, as more relevant to see the most extreme actions of the other side and ignore the poor actions of the most extreme people on your side (example: [CIA deaths versus limited coverage in US of CIA actions elsewhere](https://www.nytimes.com/2017/05/20/world/asia/china-cia-spies-espionage.html), [one cryptocurrency subreddit’s view on another](https://twitter.com/FEhrsam/status/892429946550837248))

#### *Facebook and Twitter Feeds*

**How it works**

- Algorithms take newly posted content from often likeminded friends/followers and decide what to feature so that user engagement is maximized (click, like, share/retweet)
- Unlike Reddit model, algorithm is focused on maximizing engagement for each individual user, not for a broader, more diverse community

**Example hacks**

- **Fake News**: False content that comport to reader’s views (example: fake news)
- **Selective facts**: Partial facts (factual coverage that only shows part of the picture); key issue with relying on likeminded friends to dictate content

**Other issues**

- Extreme degree of confirmation bias
	- we click on content that justifies our individual views without interacting with the full body of research on a topic
	- Gives us an irrational confidence that we know what is “reality”, because all evidence we see justifies a certain view
	- May easily dismiss valid opposing viewpoints

**Potential Antibodies**

- Realize huge degree of confirmation bias on Twitter/Facebook — and echo chambers in every social network; social media gives readers what they want, not what they need
	- Ari Paul, CIO Blocktower, on social media around cryptocurrency:

> “Easiest way to be popular is to tell people what they want to hear.  Easiest way to get rich is to tell rich people lies that they want to hear.” ([link](https://twitter.com/aridavidpaul/status/938154852567396352))

- Ari Paul, CIO Blocktower:

> “When I tweet anything positive about cryptocurrency it gets 10x the likes/shares as anything negative…” ([link](https://twitter.com/aridavidpaul/status/938153893636247552))

This example shares a lot of similarities with [publication bias](https://en.wikipedia.org/wiki/Publication_bias) in the sciences. Reader interest influences what content is produced ("the invisible hand of the reader").

- Realize it is newsworthy/relevant to see the excesses of the opposite side, but not very newsworthy/relevant to see excesses of your side (leads to empathy gap)
	- Noah Smith: “There are always a handful of people out there doing any stupid, crazy, or annoying thing you can imagine. And the media has an incentive to find those people and shove their excesses in your face.” ([link](https://twitter.com/noahpinion/status/934837949404811264))

	- My research on Islamic terrorism coverage in the NY Times vs non-Islamic terrorism and homicides ([link](https://www.nemil.com/s/part2-terrorism.html))

## Conferences and Meetups
**How it works**

- Conferences make money primarily through ticket sales, sponsorships, and booths; they aim to fill the conference seats
- Companies and media organizations organize groups of speakers and market the conference
- Sponsors and corporate organizers want to show their technology in the best light
- Motivations to speak at a conference ([according to MongoDB’s marketing team](http://web.archive.org/web/20120724115659/http://meghangill.com/2012/06/25/how-to-run-a-tech-conference-part-4-finding-speakers/))
	- increasing the speaker’s network
	- raising the speaker’s profile (personal branding)
	- recruiting for the speaker’s company
	- marketing for the speaker’s company (and for conference sponsors)

**Example hacks**

- **Sponsor speaker**: For companies, support a speaker unaffiliated with your company who you think will be likely to represent your view
- **Organize your own conference**: Run your own conference to ensure your own viewpoint is widely shared — and then shared widely online afterward by participants (Example: [MongoDB funding for conferences and user groups](https://www.nemil.com/mongo/3.html))

**Other issues**

- **Invisible hand of the sponsor/organizer**: Hard to speak badly about any sponsor, as it may impact if you’ll get free follow-up marketing or a future speaker invitation (Example: [Server Density highlights marketing benefit from speaking at MongoDB conference](https://blog.serverdensity.com/does-everyone-hate-mongodb/))
- **Surfing on hype**: Conferences need to fill seats, and so often feature ideas that will encourage this

**Potential Antibodies**

- Conferences should be just one additional data point that augment learnings from being around talented engineers — and shouldn’t be used as a primary view of what’s going on
- Weigh the background and personal motivations of every speaker
- Weigh the motivations and editorial power of who’s running conference

## Content Marketing
**How it works**

- Create “valuable” content that doesn’t look like an ad; is apt to get engagement and influence engineer behavior (examples: uptake a dev tool platform, enroll in a training program, join a company, use an open source package)
- Popular reasons for content marketing: increase domain SEO (example: [Yummly](http://firstround.com/review/the-seo-tips-that-helped-tally-20-million-visits-a-month/), [Nerdwallet](https://outrunseo.com/how-nerdwallet-built-a-520-million-company-using-a-content-based-seo-strategy/)), collect sales leads, sell product/service, recruit engineers, improve brand
- Content can be created in house, or relatively small amounts of funding can encourage others to create the content needed (example: [Pusher’s technical tutorial solicitation](https://pusher.com/guest-writer-program))

**Example Hacks**

- Create content that encourages audience to mistakenly believe that your product should be bought (Example: [REST is dead piece in Free Code Camp written by author trying to sell PluralSight GraphQL course](https://news.ycombinator.com/item?id=14839576); post was submitted by owner of Free Code Camp who was looking to get distribution; see [my response](https://news.ycombinator.com/item?id=14840321))

**Other Issues**

- Need to write content on widely read topics to maximize readership; leads to an echo chamber of hype around new technologies since these have been validated to be of interest

**Potential Antibodies**

- Have to be able to identify when something is content marketing
- Ask what is motivation of writer and how this influences their view; also need to understand their technical background
- Use content marketing to learn, but use it with proper skepticism
	- Fred Wilson, Partner Union Square Ventures:

> “So how should entrepreneurs use this knowledge that is being imparted by VCs …? Well first and foremost, you should see it as content marketing… That doesn’t mean it isn’t useful or insightful. It may well be. But you should understand the business model supporting all of this free content. *It is being generated to get you to come visit that VC and offer them to participate in your Seed or Series A round.* That blog post that Joe claimed is not scripture in his tweet is actually an _advertisement_. Kind of the opposite of scripture, right?” ([link](http://avc.com/2016/08/understanding-vcs/))

## Tech blogs and top media publications
**How it works**

- Trained (and untrained) journalists research various topics and work with editors to publish on blogs and print news
- Media organizations most often make money from ads; in some cases, they make money from subscription fees
- At it’s best, [goal of journalism](https://www.reuters.com/article/rpb-adlertrump-idUSKBN15F276) is to give the “facts [we] need to make good decisions
	- Baser goal is to optimize eyeballs and number of paying subscribers by providing content that audiences want to read
	- Similarities to a convenience store that determines product placement based on maximizing sales

**Example Hacks**

- Leak something to a journalist that reflects unfavorably on your competitor, allowing it to receive more credibility than if sourced back to your company (example: [Speculation of New England Patriots leak](https://www.nytimes.com/2018/01/14/sports/football/patriots-tom-brady-belichick.html), politics on any given day)
- Pay for PR firm to place (example: [Syria’s Asma al-Assad’s team pays $5k for help getting a favorable Vogue article](https://www.theatlantic.com/international/archive/2012/01/the-only-remaining-online-copy-of-vogues-asma-al-assad-profile/250753/))
- Pay journalist/writer directly to place a piece (example: [HuffPo/Forbes/etc](https://news.ycombinator.com/item?id=16182576))

**Other Issues**

- **Engagement is king**: Reader interest and social media algorithms prize engaging content, rather than information that leads to good engineering decisions (example: [Cecil the Lion](https://www.nytimes.com/2015/08/17/business/where-clicks-reign-audience-is-king.html))
	- Coverage is a function of reader interest; fundamental problem with using media to make decisions
		- What’s covered is not the same as what’s important for the decisions we make each day
		- Focus on newsworthiness and relevance leads to substantial “sampling bias”
	- Opportunity to create fake content that meets reader interest (example: [Jim Cramer talking about how easy it is to create fake news that Apple’s original iPhone isn’t selling well](http://www.cc.com/video-clips/rfag2r/the-daily-show-with-jon-stewart-exclusive---jim-cramer-extended-interview-pt--2), allowing him to profit off a fall in the stock price, 2016 US Election)
- **Technical Competence**: Many journalists don’t have a technical or business background, but write on these topics authoritatively
- **Talent**: Salary in journalism is a fraction of tech industry, meaning that many experienced, smart journalists increasingly leave or work in house
- **Access**: Companies/investors can control access to their companies, dictating the rules that journalists must follow to get exclusives and scoops; can cut off access to influence future coverage (example: [Coverage of the British Monarchy](https://www.nytimes.com/2018/01/14/arts/television/queen-coronation-bbc-smithsonian.html), [Disney and the LA Times](https://boingboing.net/2017/11/05/bob-iger-vs-the-press.html), [Liz Smith and Celebrity journalism](https://mobile.nytimes.com/2017/07/28/nyregion/liz-smith-lions-of-new-york.html))
- Journalists try to:
	- maintain good source relationships (e.g., investors) and access for future information
	- manage substantial story deadlines with limited time (example: [Paul Graham’s post on maximizing PR and importance of making stories easy for journalists](http://www.paulgraham.com/submarine.html))
	- show strong engagement metrics to ensure job security (Example: [Greta Van Susteren at MSNBC](https://www.nytimes.com/2017/06/29/business/media/greta-van-susteren-leaving-msnbc-after-only-six-months.html))
	- use “three’s a trend” as common heuristic, despite the fact that this would be laughable to most statisticians (example: [Great Clown Scare of 2016](https://www.nytimes.com/2016/09/13/insider/on-the-creepy-clown-beat-you-really-cant-make-this-stuff-up.html))
	- (sometimes) keep a future career path open to the technology sector
- Media organizations/journalists can try to reward supporters (Example: [speculation about National Enquirer and Donald Trump](https://www.newyorker.com/magazine/2017/07/03/the-national-enquirers-fervor-for-trump), [Donna Brazile and Hilary Clinton](https://www.snopes.com/donna-brazile-leaves-cnn/), debates about the relationship between media barons and politicians around the world)

**Potential antibodies**

- When something is heavily covered, it is substantially due to large reader interest — not due to the importance of the event for you; risk of confirmation bias and sampling bias if you don’t adjust signal
	- Paul Graham: “The number of news stories about a problem is not a sign of how serious it is, but of how much demand there is for stories claiming so” ([link](https://twitter.com/paulg/status/888496117159276545))
	- My research on death coverage in the NY Times and risk assessment ([link](https://www.nemil.com/s/part3-horror-films.html))
- Realize vivid stories are powerful for user engagement, while lots of drier data and stories that inform good decisions are less monetizable (example: [Shooting of Australian in US - and needs/pre-existing beliefs of Australian readers](https://www.nytimes.com/2017/07/22/us/minneapolis-police-shooting.html))
- Dig into technical background of writer
- When you see something covered, ask yourself who is motivated to have it covered this way
	- Especially valuable in laudatory personal profiles
	- In leaks, who could have leaked it and what was their motive? What important information might be unleaked?
- When a PR-like piece is shared ([A24 in GQ](https://www.gq.com/story/a24-studio-oral-history), IBM Watson, a laudatory profile) , ask what the covered party’s motivation is to get the word out now (recruiting, sales, corporate branding)
- Read *[All the News That’s Fit to Sell](https://www.amazon.com/All-News-Thats-Fit-Sell/dp/0691123675/ref=sr_1_1)* (Stanford Professor James Hamilton) and *[Public Opinion](https://en.wikipedia.org/wiki/Public_Opinion_(book))* (Walter Lippmann) for more on how events are turned into news

## Fellow engineers

**How it works**

- Fellow engineers may be vocal in social media, conferences, and on mailing lists


**Example Hacks**

- Give them a monetizable business model, so that they’ll represent your views (example: [MongoDB consultants who then speak favorably about MongoDB](http://web.archive.org/web/20120724115659/http://meghangill.com/2012/06/25/how-to-run-a-tech-conference-part-4-finding-speakers/))
- Give them equity in the success of your business — increasing the likelihood they’ll speak positively of you and, at minimum, reducing the likelihood they can publicly say negative things about you (example: [cryptocurrency ownership](https://twitter.com/fehrsam/status/892429946550837248), open source developer equity grant)

**Other Issues**

- Fund researchers who pursue avenues that will be potentially accretive to your interests; not explicit bias, but means that opposite hypothesis may be weakly pursued

**Potential antibodies**

- Question funding and incentives of anyone speaking favorably about a chosen technology
- Just because someone has a well regarded reputation (e.g., through open source contributions, through previous well regarded projects) doesn’t mean they can’t be representing parochial incentives that are at odds with what is right for you