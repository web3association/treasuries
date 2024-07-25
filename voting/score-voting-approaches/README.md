---
description: >-
  Comparing different score voting approaches that could be used for making
  network and treasury decisions within Web3 ecosystems
---

# Score voting approaches

There are a number of score voting approaches that were highlighted in the voting approach comparison. These scoring approaches can be better understood by breaking down how points could be allocated and used by voters and what voting options could exist. These approach comparisons have helped to identify some of the more suitable score voting approaches that a Web3 ecosystem might want to consider. The comparisons mainly focus on decisions where there are multiple proposals and a single proposal or multiple proposals are being selected.



**Points allocation approaches**

The following compares the different ways that voters could be allocated points that they would then use to vote on proposals. A single point per proposal emerged as one of the most effective approaches for maximising simplicity and speed for voting whilst also being a more resilient solution for preventing bad actors from getting an advantage.

{% content-ref url="points-allocation-approaches/" %}
[points-allocation-approaches](points-allocation-approaches/)
{% endcontent-ref %}



**Score voting options approaches**

Voting options determine how a voter is able to allocate their points and voting power. Points could be allocated to approval or disapproval options or a combination of the two. For both decision based and proposal based points allocation approaches the combination of approval and disapproval voting options can be problematic as it can give bad actors an edge by being able to downvote competing proposals. Due to this approval and disapproval only options are preferred for voting systems that need to scale to a very large audience as they can be more effective at preventing bad actors from gaining an advantage in the decision process due to other people's voting behaviours.

* **Approval option only** - Points can only be allocated to an approval option. This is a simple and quick voting approach for voters. A big benefit of this approach is that for single point allocation approaches it prevents bad actors from getting any advantage over honest voting behaviour.
* **Disapproval option only** - Points can only be allocated to a disapproval option. A disapproval option has similar advantages and disadvantages as an approval only option. A disapproval option approach could be effective in situations when there are more fillable positions than there are submitted proposals. In these situations it might make more sense for voters to disapprove the worst proposals rather than voting on a larger number of proposals that they need to approve.
* **Approval & disapproval options** - Points can be allocated to either an approval or a disapproval option. This slightly increases the voting time required as now voters need to consider both upvoting and downvoting the proposals. This approach is more expressive as it enables voters to indicate which proposals they approve or disapprove of. The main problem with having approval and disapproval options is that bad actors would be incentivised to downvote any competing proposal which can give them more influence with their voting power. Normal voting behaviour wouldn’t counteract malicious voting behaviour. Approval & disapproval voting could be suitable in situations where the voters are public or there is more confidence that voters will not vote maliciously against other proposals.



**Victory condition approaches**

Points could be aggregated in a few different ways to determine the winning proposals. A total score approach that only has a single voting option would be the most effective at preventing game theory risks. Due to this a total score approach with only approval or disapproval voting would be preferred to prevent these game theory issues.

* **Total score** - An approval only voting option would not be at risk from bad actors as the score is only improved by any point that is allocated. If there was both an approval and disapproval option then the total score could be negatively influenced by bad actors who disapprove of any of the competing proposals.
* **Average score** - Has game theory risks for any multiple points approaches as bad actors could allocate the minimum points to a proposal just to drag the average score down.
* **Median score** - Has game theory risks for any multiple points approaches as bad actors could allocate the minimum points to a proposal just to drag the median score down.



**Applying the score voting examples to these approaches**

The different score systems listed in the voting approaches analysis have been mapped to the score voting approaches that have been outlined above:

{% content-ref url="applying-the-score-voting-examples-to-these-approaches.md" %}
[applying-the-score-voting-examples-to-these-approaches.md](applying-the-score-voting-examples-to-these-approaches.md)
{% endcontent-ref %}



## Suggested score voting approach



**Initial suggestion**

The score voting approaches that have been compared led to the following suggested approach:

* **Single point per proposal** - Voters would allocate a single point towards the proposals that they approve. This approach is simple and quick for voters. It also prevents bad actors from getting more influence over the decision due to certain voting behaviours as everyone would always be applying their full voting power.
* **Approval option only** - Voters would only be able to select an approval option to prevent bad actors from downvoting all other proposals apart from their own.
* **Total score** - The winning condition for this approach would be determined by the proposals that have the highest total score.



**Score voting approach improvement ideas**

The initial suggested score voting approach has a few key problems that could be addressed. The first is that the suggested approach is far less expressive for voters than alternative points allocation approaches. Voters would struggle to share the intensity of their preferences. It is also not effective for sharing dissenting opinions. A few improvement ideas can be explored to help remedy these problems:

{% content-ref url="voting-approach-improvement-ideas.md" %}
[voting-approach-improvement-ideas.md](voting-approach-improvement-ideas.md)
{% endcontent-ref %}



**Suggested score voting approach**

After applying the suggested improvement ideas with the initial suggestion an updated suggestion can be documented. Expressive approval voting with decision disapprovals could be an effective score voting approach for Web3 ecosystems to adopt at scale:

{% content-ref url="expressive-approval-voting-with-decision-disapprovals.md" %}
[expressive-approval-voting-with-decision-disapprovals.md](expressive-approval-voting-with-decision-disapprovals.md)
{% endcontent-ref %}
