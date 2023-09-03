# The Continuous Feedback Manifesto (Draft)

Many developers are familiar with Continuous Deployment and Continuous Integration as established development practices. Continuous Feedback describes the inverse process that aims to bring back data from the code runtime environments and into the hands of developers. With Continuous Feedback the goal is not to maximize throughput and velocity from code to prod but to maximize the scope of feedback from prod through test and dev and back to code.

## Continuous over Manual
Continuous feedback needs to happen automatically, as the developer works, and cannot rely on manual processes or dashboard checks

## Proactive vs. Reactive
Continuous feedback must used before a problem occurs or very early in its development, rather than a reaction to existing bugs or production issues.

## Code centric vs. Service centric
Traditional APMs focus on SREs, IT, and DevOps whereas CF is focused on developers and their code and code changes.

## Clarity over Raw data
Raw data requires additional cognitive effort to process whereas Continuous Feedback focuses instead on the significance of the data to the developer's code 

## Data streams over single occurrences
Activities such as debugging or trace analysis focusing on a specific instance can be meaningless without analysis of the entire dataset. Continuous Feedback processes the data stream rather than focus on any specific outlier.

