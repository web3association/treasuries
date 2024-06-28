---
description: Preference based voting approach for voting systems
---

# Preference voting

<div align="left">

<figure><img src="../../.gitbook/assets/preference-voting.png" alt="" width="150"><figcaption></figcaption></figure>

</div>

**Overview**

Preference based voting systems allow voters to rank proposals in order of their preference rather than selecting just one proposal. Ranking helps to provide a more nuanced expression of voter choices, allowing the voting system to consider not only the most preferred proposal but also secondary and further preferences.



**Examples of preference based voting systems**

* **Instant-Runoff Voting (IRV) & Ranked-Choice Voting (RCV)** - Voters rank proposals in order of preference, and if no proposal wins a majority of first-choice votes, the proposal with the fewest votes is eliminated. Votes for the eliminated proposal are transferred to the remaining proposals based on voters' next preferences. This process repeats until one proposal has a majority. This approach is also a type of majority based voting system.
* **Bucklin Vote** - Voters rank proposals in order of preference. All first-choice votes are counted, and if no proposal has a majority, second-choice votes are added to the totals. This process continues with third choices, and so on, until a proposal achieves a majority. This approach is also a type of majority based voting system.
* **Condorcet Method** - Voters rank proposals, and the proposal who would win a head-to-head comparison against every other proposal is declared the winner.
* **Supplementary Vote (SV)** - Voters mark their first and second choices. If no proposal receives a majority of first-choice votes, all but the top two proposals are eliminated, and the second-choice votes are added to the totals of the remaining two proposals. This approach is also a type of majority based voting system.
* **Borda Count** - Voters rank proposals, and points are assigned based on the rankings (e.g., 1 point for last choice, 2 points for second-last, etc.). The proposal with the highest total points wins. This approach is also a type of majority based voting system.
* **Coombs’ Method** - Voters rank proposals in order of preference. In each round, the proposal with the most last-place votes is eliminated, and the process repeats until one proposal remains or a proposal achieves a majority of the remaining votes.
* **Single Transferable Vote (STV)** - Voters rank proposals in multi-option decisions. Proposals must achieve a certain quota of votes to be selected. Votes are initially allocated to first preferences, and excess votes for selected proposals are transferred to other proposals based on preferences. This process continues until all available positions are filled. This approach is also a type of proportional based voting system.



**Very low binary decision suitability (Score - 1)**

A preference voting approach is not very suitable for a simple binary decision. A yes or no outcome is required which means a preference based outcome would not be relevant as any ranked outcome of just two options would just be translated into a binary yes or no majority decision outcome.



**High single selection decision suitability (Score - 4)**

* **Accuracy & expressiveness** - Preference based voting would be effective at accurately ranking the proposals based on the voters preferences. The main issue with preference based voting would be that not every set of options could be easily ranked into a single ordered list. A voter might have a similar amount of preference for different groups of proposals where they prefer these options equally. Preference based voting can be highly effective when there is a limited number of proposals to rank and in situations when it is fair to expect that the voter will be able to read and understand each proposal - which would be required for them to make an informed decision when ranking each proposal.
* **Time required to participate** - For decisions that have a limited number of proposals the time it takes to rank them would still take a moderate amount of time but this should not be too excessive. If the number of proposals is high then the participation time required could be much higher and become excessive. A preference approach could be suitable for many of the example use cases listed which would likely have a limited number of proposals to select from.
* **Voting complexity** - Preference voting approaches become increasingly complex as you increase the number of proposals that the voter is required to rank. This also can make it very difficult for a voter to make an informed voting decision unless they understand each of the proposals in enough detail. Preference voting will be more suitable in situations when there are a limited number of proposals that need to be compared and ranked so that the complexity for voters doesn’t become excessive.



**Low multiple selection decision suitability (Score - 2)**

* **Accuracy & expressiveness** - The complexity with decisions where multiple proposals can be selected is that the difficulty in ranking those proposals will likely increase as the number of proposals increases that the voters need to compare and rank. For a voter to rank the proposals accurately they will need to have a sufficient understanding of the proposals and be able to compare those proposals against each other. This approach can be useful for getting a more exact outcome on which proposal is most preferred, however it also could be far too complex to expect voters to rank proposals about priorities, ideas, contributors and delegated representatives. In these example decisions the proposals could have a large amount of information and be difficult to compare at scale. A voter might want to express their opinion that there are a number of proposals that they equally prefer and a number of proposals that they equally disapprove of. A preference based approach would prevent them from being able to express that. Preference voting approaches could be effective when high accuracy is required at the expense of the expressiveness and time required for voters to participate.
* **Time required to participate** - It would be extremely time consuming to rank a large number of proposals that had any reasonable amount of complexity to read and understand. Out of the different voting approaches that exist this one would be one of the most time consuming for a multiple selection decision with numerous proposals that need to be considered.
* **Voting complexity** - The complexity for voters to rank a large number of proposals that have moderate to large amounts of information to digest is very high. It is unlikely an effective way to make decisions due to this complexity. If voters want to make an informed decision they are forced to read every proposal and understand them enough to make a comparison between each of them. This becomes less feasible in situations where there are many proposals of moderate length. For the examples of ranking priority, idea, contributor and delegated representative proposals this complexity could likely be excessive.



**Total score = 7 / 15**
