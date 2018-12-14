# Canopy
## authentic human community

### Canopy is an online community built to foster authentic communication. It's owned by its users, users retain ownership of their content, and advanced techniques in voting and economics keep out spammers and propagandists. 

# What is a Canopy?
A Canopy is the upper layer of leaves in an area of forest, protecting the ecosystem that thrives beneath.

Our Canopy is a community bulletin board where members can share their thoughts, links, comments, photos, proposals, etc with complete confidence that they are in control of their content. There are many Canopies, each focused around a specific interest, organization, or geographic area. If desired, users can publish their content to one of our meta-canopies (need a better name) that is a board of the best content as created and curated by our members.

# Creation
Just as any interaction in the real world puts something at risk (ie reputation), Canopy requires its members to take a small risk when creating content.

When adding any content, a member must deposit a stake. They may choose any amount above a small minimum; the amount they stake determines the potential rewards they might get returned. Vitalik Buterin has called this technique of requiring up front risk in order to post content to the blockchain "Proof of Stake Hash Cache".

Members own the content they post, and a variety of cryptographic techniques that Canopy uses helps to ensure that member privacy settings are always respected, and that creators receive payment when / if their content is licensed.

# Curation
Curation of content on the platform takes place through voting, beginning with upvoting and downvoting.

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

**Return of creation stake**: when a member chooses to cash out their post (any point within 30 days of posting), they will receive a return of their initial stake based on their ratio of upvotes to downvotes. 75% positive votes will return 75% of initial stake.

**Transfer through curation votes**: When another member pays to make a positive vote, that payment will be sent on to the post's creator.

**Bonus payment**: when a member's post reaches a Curation Score threshold, they will receive an additional payment based on their initial stake, up to doubling their initial stake.

But the biggest rewards are returned to the Canopy community. While individual members tend are rewarded for their positive results, any money spent / surrendered to downvoting goes into that Canopy's community pool. This funds the bonus pool for individual posts as well as the community jackpot.

When the community pool reaches a certain threshold (could be account balance or could be voted by Canopy community), 70% of the money in the pool is distributed to all members who were active participants since the last bonus payout. 

A jackpot payout also pays 10% of the community pool back to Canopy maintainers.


# The Wilderness 
Canopy's vibrant economy represents a safe way for humans to take their communities online. 

Most social feeds allow their users to post as much content as they want for "free", but in fact users who post to Twitter, Facebook, etc are performing labor for those publishers, creating content that those platforms assume ownership over.

These publishers use techniques that amplify the most popular content. Those with enough knowledge can learn how to game the ranking formulae. On a platform where posting is free, voting is free, and accounts are free, a person or organization with enough willpower can find any number of methods to make sure their voice overpowers the voice authentic users.

Any platform that represents itself as free is foundationally vulnerable to (if not explicitly created for) exploitation by spammers, propagandists, and identity brokers.

# Win 'em with UX
As much as the cryptoeconomic setup of Canopy is a huge social good in itself, it won't mean much without a user base. Canopy is:

* Simple
* Engaging
* Fun

**Simple**: 
* No confusing terminology. None.
* No 3rd party browser extensions required (yes this can be done today)
* Managed keys or advanced users can import their own
* Easily used in wallet / Dapp browser
* (maybe) integrate with Slack / Discord / etc

**Engaging**
* Transactions everywhere should feel significant
* Back this up by providing visceral feedback to actions

**Fun**
* Most social feeds are too soulless, Canopies should be able to show the identity of their community
* The experience should feel like a game that everyone wins

3-specifics of Tech
5-Tokenomics
6-growth strategy