---
title: Discrete choice modeling for better prioritization questions
tags: [ "UX research", "UXR tools", "quantitative research", "mixed methods"]
date: 2025-04-20
description: An introduction to survey techniques for ranking and prioritization, including MaxDiff, Conjoint Analysis and Constant Sum.
---
_This article follows my series [Quant for Qual Researchers, a work in progress](https://www.zoracabrera.com/blog/quant-for-qual-researchers-a-work-in-progress/), which I started for qual researchers who want to upscale their toolbox but don't know where to start._

Discrete choice modeling methods measures the relative importance of a set of options for a group of people. There are several survey formats that fall within this type of analysis, all of which aim to model what people care most about. The basic idea behind this approach consists of placing a series of choices next to each other and asking study participants choose between them. They work based on the assumption that “when confronted with a discrete set of options, people choose the option of maximal benefit or utility.” <sup>1</sup>

## The benefits
They provide the most benefits when we need to measure something that does not have a standardized rating system.

Daniel Kyne of Opinion X has a series of very useful articles on discrete choice modeling. He explains that discrete choice modeling can be used to answer several ranking questions within the world of product research and user experience design:

<blockquote> 

1. Preference — what do they like most?
    
2. Pain — what’s their biggest unmet need?
    
3. Value — what’s worth most to them?
    
4. Friction — what’s their biggest barrier to action?
    
5. Motivation — what’s their biggest driver of action?
    
6. Risk — what concerns them most?
    

Which makes it perfect for research scenarios like:

1. Customer Segmentation — finding groups of customers that care about the same things.
    
2. Roadmap Prioritization — planning what to build by understanding your customers’ top needs.
    
3. Assumption Testing — proving whether your hypotheses about people’s preferences are true.
    
4. Value Analysis — figuring out which products or features customers perceive as highest value.
    
5. Message Testing — seeing which phrases resonate strongest with your target customers. <sup>2</sup>
</blockquote> 

## Couldn’t I use a Likert scale?
If you are trying to determine the level of satisfaction with one product, you could use a Likert scale question, where your customer can rate the product on a scale of “1 - very dissatisfied” to “5 - very satisfied.“ However, if you are trying to learn which of 10 different features customers value the most, a Likert scale may not be the most effective. This is because all or most customers may rate multiple items as “very important.”

## Different types of methods

 There are  different types of discrete choice modeling methods or formats, including:
- Rank choice voting
- Pairwise comparison
- MaxDiff surveys
- Points allocation
- Conjoint analysis

### Rank choice voting
This approach provides a list of options and asks participants to number them from most important to least important. It’s best used when you have a small list of items (no more than 10), as a longer list may become difficult to manage. This approach best answers the question of “what’s most important?”
### Pairwise comparison
When you have a longer list of choices, you may want to consider Pairwise comparison. This approach choose participants 2 options at a time and asks them to select one. Pairs are presented randomly. To determine the winner, Pairwise looks at the number of times the option won, and calculates it as a percentage. For example if the option was presented 100 times randomly, and won 90 times, then its win rate is 90%.
### MaxDiff
MaxDiff works similarly to Pairwise. Instead of showing the participant 2 options, it shows them a list of at least 3 options and asks them to select the most important item and the least important item. Because participants shows more  items at a time, MaxDiff creates a bigger cognitive load than Pairwise. Therefore it is typically recommended to keep the number of options per questions to no more than 6. Although MaxDiff adds complexity for participants at a question level, it does provide less number of questions for participants, so it may be preferable to Pairwise when the list of items is longer and there is a bit more budget.
### Points allocation or Constant Sum
In points allocation (alternatively known as constant sum) participants are given a series of points, and are asked to distribute them amongst a set of options. This approach answers “what’s most important?” And provides a point of comparison that allows us to understand “how much more important is it?” For example if someone has 12 points and allocates 3 points to A, 2 points to  B, and 9 points to C, we can tell that C is significantly more important than the other options.

To make points allocation more tangible for participants, you may consider framing your question in terms of dollars or time. For example, “if you had $150 to spend, how much would you plan to pay for each of these services?” Or, say you have 8 hours in a an average work day, “how much time do you typically spend on each of these tasks?”
### Conjoint analysis
Conjoint analysis is the most different out of these 5 methods. It also has the narrowest application: simulating a purchase scenario of a well-understood product.

This method asks participants to choose between 2 to 6 different “profiles“ of a product. The keyword here is “profiles.” Each option has a set of attributes. For example, a participant may be presented with 3 different profiles of used cars. Each profile would have the attributes of “year,” “model”, and “mileage.” The underlying assumption here is that people “evaluate products based on their _combination of attributes_." <sup>3</sup>

Conjoint analysis can take many different formats by combining some of the methods above as well as a few unique methods. It also can be tricker and more expensive to analyze as it involves many more variables. This [article goes over the analysis](https://www.opinionx.co/blog/conjoint-analysis-calculation) in more detail. However, it can be useful for simulating a purchase scenario, when certain criteria is met. As Daniel Kyne explains:

<blockquote> 
<p>That means that conjoint is really only suited to research scenarios:</p>

1. That simulate a simple, well-considered purchase between similar products.
    
2. Where only one person is involved in the purchase decision.
    
3. Where the customer already knows what kind of product they need.
    
4. Where you know which attributes the customer use to compare products.
    
5. Where those attributes have no overlap in meaning or possible options.” <sup>3</sup>
</blockquote> 

## Watch-outs/Considerations

- Discrete choice analysis requires a detailed-oriented and cross functional approach (co-creation with users, business, and researchers) to appropriately create a model. For example you may need to spend time ensuring not to include unrealistic options or offerings that may not exist in the marketplace. <sup>4</sup>
- Omitting key variables or choices may significantly impact the resulting model, leading to inaccurate results
- These approaches are great for answering order of importance, but they will not explain why something comes to the top. Thus often a good idea to pair this type of research with qualitative studies.

---
## Quoted References

1. ["Discrete Choice Model and Analysis"](https://www.publichealth.columbia.edu/research/population-health-methods/discrete-choice-model-and-analysis) by Columbia University Mailman School of Public Health
2. ["Discrete Choice Model Analysis"](https://www.opinionx.co/blog/discrete-choice-modeling) by Daniel Kyne
3. ["13 Types of Conjoint Analysis Explained"](https://www.opinionx.co/blog/conjoint-analysis-types) by Daniel Kyne
4. ["What are Conjoint Analysis and Discrete Choice Analysis?"](https://www.burke.com/beyondmeasure/what-are-conjoint-analysis-and-discrete-choice-analysis/) by Burke Inc

## Additional References
- ["Better Questions for Segmentation: Use of Max-Diff"](https://trcmarketresearch.com/whitepaper/better-questions-for-segmentation-use-of-max-diff/) by Rajan Sambandam
- More by Daniel Kyne:
	- [Points Allocation Survey Method](https://www.opinionx.co/blog/points-allocation)
	- [The Most Misunderstood Research Method In All The Land](https://www.opinionx.co/blog/most-misunderstood-research-method)
	- [How To Calculate Conjoint Analysis Results](https://www.opinionx.co/blog/conjoint-analysis-calculation) 