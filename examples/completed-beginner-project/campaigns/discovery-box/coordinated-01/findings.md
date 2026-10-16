# Prepared synthetic-data findings

The source is data/classroom-campaigns.csv. These classroom rows support arithmetic and a test proposal, with different objectives and no randomized comparison.

| Campaign | CTR | Lead conversion | Cost per lead | Cost per order |
| --- | --- | --- | --- | --- |
| Brew guide | 2.5% | 20% | USD 2.78 | USD 22.22 |
| Discovery Box | 2.5% | 6% | USD 14.81 | USD 16.67 |

## Trace the formulas
CTR uses clicks divided by impressions, multiplied by 100. Lead conversion uses leads divided by landing visits, multiplied by 100. Cost per lead uses spend divided by leads. Cost per order uses spend divided by orders.

For Brew guide, 144 / 720 * 100 gives 20% lead conversion, 400 / 144 gives USD 2.78 cost per lead, and 400 / 18 gives USD 22.22 cost per order. The campaign objectives differ, so these figures leave a causal ranking unsupported. Revenue, profit, and ROAS require additional data.

## Next decision
Propose one bounded test using a defined audience, objective, and metric. Human review governs any future spending or launch.
