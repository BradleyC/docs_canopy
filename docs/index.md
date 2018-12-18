# Canopy
## authentic human community

### Canopy is an online community built to [foster authentic communication](culture.md). It's owned by its users, [users retain ownership of their content](ownership.md), and advanced techniques in voting and economics keep out spammers and propagandists. 

# What is a Canopy?
A Canopy is the upper layer of leaves in an area of forest, protecting the ecosystem that thrives beneath.

Our Canopy is a community bulletin board where members can share their thoughts, links, comments, photos, proposals, etc with complete confidence that they are in control of their content. There are many Canopies, each focused around a specific interest, organization, or geographic area. If desired, users can publish their content to one of our meta-canopies (need a better name) that is a board of the best content as created and curated by our members.

# Creation
Just as any interaction in the real world puts something at risk (ie reputation), Canopy requires its members to take a small risk when creating content.

When adding any content, a member must deposit a stake. They may choose any amount above a small minimum; the amount they stake determines the potential rewards they might get returned. Vitalik Buterin has called this technique of requiring up front risk in order to post content to the blockchain "Proof of Stake Hash Cache". But we just call it "Creation" ;)

Members own the content they post, and a variety of cryptographic techniques that Canopy uses helps to ensure that member privacy settings are always respected, and that creators receive payment when / if their content is licensed.

# Curation
Curation of content on the platform takes place through voting, beginning with boosting and burning.

Canopy uses Quadratic Voting (Recently popularized by Glen Weyl and Eric Posner) to rank votes. A member must pay for each vote, and a member may vote as many times as they wish. However, each additional vote costs more than the last, increasing exponentially.

```
cost = votes^2
1 vote = 1 token, 3 votes = 9 tokens, 5 votes = 25 tokens
```

This allows members who feel very passionately about a particular post to increase the volume of their voice, but keeps one or two wealthy members from hijacking the conversation.

Canopy uses quadratic voting to get sentiment as the ratio of positive to negative votes, and then factors in popularity, which measures unique votes over time.

In this way, the Canopy community creates a continuously changing score for each piece of content. Each Canopy's home view is made up of posts sorted in order of Curation Score.

# Rewards
We've discussed costs implemented in Canopy that represent risks taken in real world communities, but is there any way for that cost to return to Canopy members? I'm glad you asked.

There are three ways to receive tokens from the Canopy curation process itself:

1. Return of creation stake
2. Transfer through curation votes
3. Bonus payment 

**Return of creation stake**: when a member chooses to cash out their post (any point within 30 days of posting), they will receive a return of their initial stake based on their ratio of boosts to burns. 75% positive votes will return 75% of initial stake.

**Transfer through curation votes**: When another member pays to make a positive vote, that payment will be sent on to the post's creator.

**Bonus payment**: when a member's post reaches a Curation Score threshold, they will receive an additional payment based on their initial stake, up to doubling their initial stake.

But the biggest rewards are returned to the Canopy community. While individual members tend are rewarded for their positive results, any money spent / surrendered to burning goes into that Canopy's community pool. This funds the bonus pool for individual posts as well as the community windfall.

When the community pool reaches a certain threshold (could be account balance or could be voted by Canopy community), 70% of the money in the pool is distributed to all members who were active participants since the last bonus payout. 

A windfall payout also pays 10% of the community pool back to Canopy maintainers.

# The Wilderness 
Canopy's vibrant economy represents a safe way for humans to take their communities online. 

Most social feeds allow their users to post as much content as they want for "free", but in fact users who post to Twitter, Facebook, etc are performing labor for those publishers, creating content that those platforms assume ownership over.

These publishers use techniques that amplify the most popular content. Those with enough knowledge can learn how to game the ranking formulae. On a platform where posting is free, voting is free, and accounts are free, a person or organization with enough willpower can find any number of methods to make sure their voice overpowers the voice of authentic users.

Any platform that represents itself as free is foundationally vulnerable to (if not explicitly created for) exploitation by spammers, propagandists, and identity brokers.

# Win 'em with UX
As much as the cryptoeconomic setup of Canopy is a huge social good in itself, it won't mean much without a user base. Canopy is:

* Simple
* Engaging
* Fun

**Simple**: 
* No confusing terminology. None.
* No 3rd party browser extensions required (yes this can be done today)
* No wait times on transactions
* Managed keys or advanced users can import their own
* Easily used in wallet / Dapp browser
* (maybe) integrate with Slack / Discord / etc

**Engaging**
* Transactions everywhere should feel significant
* Back this up by providing visceral feedback to actions

**Fun**
* Most social feeds are too soulless, Canopies should be able to show the identity of their community
* The experience should feel like a game that everyone wins

# Tech
Canopy is built on Ethereum. In order to speed up finality of transactions, it uses Plasma (at first a third party service).

Canopy is mobile-first, built to be used in iOS or Android browsers. Also great in mobile wallets.

# Who are the maintainers?
We mentioned that "the maintainers" receive a partial payout from every windfall, but who are these maintainers?

Maintainers of Canopy are:
* Software Developers, Designers, etc
* Community Caretakers

This is to say that there is a financial incentive for early Community Caretakers to bring their communities into Canopy - fostering a community will bring a form of royalties. And of course, an incentive for technologists to build the platform.

# Tokenomics
Canopy has its own token, which should start at a very low cost. Users should feel like creation and curation costs anything from pocket change to lunch money, and _not more_.

Creating a Canopy will cost some money, and include some number of user accounts seeded with token. 

Creation and curation, the two primary member activities, are positive economic activities. The more posts created, the more votes cast in curation, the more valuable the Canopy economy will be.

We expect that the economy will be sticky: the average member should be turning over a few dollars of value in any given week, or not enough to want to immediately withdraw (e.g. Venmo). At the same time, members should be able to exchange Ethereum for platform token easily. 

As the total economic activity on Canopy increases, we expect the value of the token to increase. We intend to have an enormous supply of token such that inflation over time won't have a tremendous effect for any small user.

Our token will also represent an ownership stake in the platform itself.

In the future, posts on Canopy might be available for license, with profit going directly to the creator.

In the future, aggregated member data might be sold, with the revenue returning to the Canopy that it represents.

# Growth
Canopy does its best to mimic real world community in the digital world, so we will grow by pursuing real world communities.

* Should we allow tiering / collation of clans / alliances / etc?

# The First User Tests
User tests will begin the week of 12/17. A description of the test, method, and hypotheses to be tested can be found [here](user_tests.md).

# Culture
Culture is hugely important. The tone of the first few communities will set the pattern for the entire rest of the ecosystem.

[More on culture here](culture.md).