---
description: Majority voting approach for voting systems
---

# Majority voting

<div align="left">

<figure><img src="../../.gitbook/assets/majority-voting.png" alt="" width="150"><figcaption></figcaption></figure>

</div>

**Overview**

A proposal must receive a majority of the votes, either through an initial vote or a subsequent voting process.



**Example majority voting systems**

* **Two-Round System (Runoff Voting)** - A voting system where if no proposal wins a majority of the votes in the first round, a second round is held with the top two proposals.
* **Binary Voting** - A voting system where voters can choose between two options, usually “yes” or “no”.
* **Exhaustive Ballot** - Voters cast a single vote for their preferred proposal. If no proposal achieves a majority, the proposal with the fewest votes is eliminated. Further rounds of voting are then held until one proposal achieves a majority.
* **Contingent Voting** - Voters rank proposals in order of preference. A proposal wins if it receives more than 50% of the first-preference votes. If no proposal achieves a majority, all but the top two proposals are eliminated. The second-preference votes of those who voted for the eliminated proposals are then counted and added to the totals of the remaining two proposals. This voting system is also a type of preference based voting.



**Very high binary decision suitability (Score - 5)**

* **Accuracy & expressiveness** - A binary voting system is the exact type of voting system that will often be used for a simple binary decision that requires a “yes” or “no” outcome. The decision is simple so majority voting approaches are suitable and have high accuracy and expressiveness.
* **Time required to participate** - The binary voting approach is simple by design so this voting approach would be one of the fastest voting systems to participate in.
* **Voting complexity** - Voting is very simple. No complex comparisons or rankings are involved and instead the voter is always just considering a single proposal and deciding between a yes or no outcome.



**Moderate single selection decision suitability (Score - 3)**

* **Accuracy & expressiveness** - A two round system could help to increase the accuracy however this would come at the cost of voting complexity and voter participation time required. Majority voting approaches might be more beneficial in situations where the outcome of the vote will have a large impact on the users of the network and due to that it might be important that a decision eventually leads to a majority outcome.
* **Time required to participate** - The problem with majority voting systems for a single selection decision is that there might not be a majority preference for a single proposal. The voting process could require multiple rounds to force a majority outcome. This could greatly increase the time required for people to participate in voting if multiple voting rounds were needed.
* **Voting complexity** - The larger the number of options there are the more complex it could become to get to a majority outcome. Using preference or score based voting can help with making it quicker to identify a winning proposal instead of using multiple rounds of voting to reach a majority.



**Very low multiple selection decision suitability (Score - 1)**

* **Accuracy & expressiveness** - If there are many proposals to choose from and many proposals can be selected as part of the outcome there is a decreased probability that a majority outcome will be achieved for every proposal. Multiple rounds of voting could be required to achieve a majority outcome. Voters would also be limited in being able to express the intensity of their preferences without being able to score or rank the proposals in some way.
* **Time required to participate** - If multiple rounds were required to reach a majority outcome this approach would likely take a large amount of time for voters to participate. If voting was done in one round it might not be sufficiently expressive enough for voters to reach a consensus about which proposals should be selected without accepting a plurality approach or using score or ranking based approaches.
* **Voting complexity** - It would be more difficult to reach a majority decision with a multiple selection decision that has many proposals that can be selected. The larger the amount of proposals the lower the probability that every proposal will reach a majority. Plurality voting is more practically feasible than majority approaches in these situations due to the complexity for voters of reading and understanding a large number of proposals. Proposals about priorities, ideas, contributors or delegated representatives could have large amounts of information attached to the proposal. This can increase the difficulty for voters to read these proposals and reach a majority decision. Requiring a majority outcome could make it difficult for voters to feasibly participate in these decisions due to the complexity.



**Total score = 9 / 15**
