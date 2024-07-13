---
description: Available positions using single points based points allocation approach
---

# Available positions single points per decision

<div align="left">

<figure><img src="../../../.gitbook/assets/points-per-decision.png" alt="" width="120"><figcaption></figcaption></figure>

</div>



**Overview**

The number of positions that can be filled determines the total amount of points that each voter gets to allocate. Each available position would result in a single point to allocate. In many funding decisions a rough estimation of the available positions would be required as each proposal could request a different amount of funding. In these situations the total budget could be divided by the average requested budget to get an estimation of the available positions.



**Low accuracy & expressiveness (Score - 2)**

Voters would not be able to easily express their exact preferences as they would only be able to allocate one point to indicate that they approve a proposal. The intensity of their preference would not be captured with this approach and they also might have other proposals that they equally prefer that they cannot select due to the limited number of points they can allocate. Compared to the other approaches that use multiple point allocations this approach is one of the worst for being expressive but the limited number of points can help with encouraging comparison between proposals which could increase the accuracy of the outcome. Each voter would be treated equally and would have the same voting experience in each decision.



**Low voting complexity (Score - 4)**

The complexity is relatively low due to the limited number of points a voter needs to allocate. The main complexity is determining which proposals will fit into the voters approval list. This could be difficult in situations where there are many proposals that a voter would like to approve but are prevented from expressing this due to the limited number of points they have to allocate.



**Very low voting time required (Score - 5)**

A larger number of positions would increase the amount of time it takes to vote however this approach should result in the minimum amount of votes being needed to make a decision so this approach could be one of the most effective for reducing the voting time required. Voters also only need to allocate a single point and don’t need to indicate the intensity of their preferences using multiple points.



**Very low game theory risks (Score - 5)**

Bad actors would not get any added benefit from diluted voting power as this would not be possible if every voter was using their full voting power when they allocate their available points. The amount of voting power they allocate would also always be a constant regardless of whether they allocate to one or many proposals as each point would either represent their full voting power or a proportional amount of their voting power. Even if a voter didn’t use all of their voting power they would have used the maximum they could have used on the proposals they did approve.



**Total score = 16 / 20**
