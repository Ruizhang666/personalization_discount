# personalization_discount



1. Investigating the Causal Relationship:

	•	Focus: Understanding whether discounts have a causal effect on profits.
	•	Approach: You began by exploring causal inference techniques like regression and the Frisch–Waugh–Lovell (FWL) theorem, which allowed you to isolate the impact of discounts on profits while controlling for other factors.
	•	Key Insight: You learned how to estimate the average treatment effect (ATE) of discounts and whether discounts are, on average, beneficial or harmful to profits.

2. Regression Discontinuity Design (RDD) and Difference-in-Differences (DiD):

	•	Focus: Investigating causal effects using specific methods like RDD and DiD when randomization isn’t feasible.
	•	RDD: You identified a cutoff point (like customer tenure or age) where the treatment (discount) changes and used that discontinuity to estimate the causal effect of the discount.
	•	DiD: You used time-based differences to compare treated and control groups before and after an intervention (like increasing discounts for a group of customers).
	•	Key Insight: These methods helped you deal with real-world scenarios where true randomization is impossible, providing insights into how interventions affect profits over time or across groups.

3. Personalization by Groups:

	•	Focus: Segmenting customers into groups based on features and distributing discounts to those groups.
	•	Approach: You grouped customers by personalization scores (e.g., sales prediction bins, age, tenure) and distributed discounts accordingly. This was the first step toward targeted discount strategies.
	•	Key Insight: Group-based personalization allows you to make more targeted decisions by giving discounts to customers who are expected to respond positively based on their group characteristics. It’s more effective than uniform discounting but still a coarse-grained approach.

4. Personalization for Individuals (CATE):

	•	Focus: Moving from group-based to individual-level personalization by estimating the Conditional Average Treatment Effect (CATE) for each customer.
	•	Approach: Using double/debiased machine learning (DML), you predicted the individual response to discounts based on customer features. You applied the residualized regression technique to estimate the treatment effect for each individual.
	•	Key Insight: You learned how to tailor discounts at the individual level, providing a fine-grained, personalized strategy that maximizes profitability by targeting customers who are most likely to respond positively to discounts.

5. Optimizing Discount Strategy:

	•	Focus: Determining whether to give a discount and, if so, how much.
	•	Approach: The culmination of all the work is being able to not only determine who should receive a discount based on their treatment effect (positive or negative), but also to optimize the amount of discount. With techniques like CATE and DML, you have the tools to make individual-level decisions about how much discount each customer should get based on their personalized response.
	•	Key Insight: This project allows you to apply your knowledge to optimize the discount amount for each individual, ensuring that the discounts given out are profitable and data-driven, avoiding wasteful spending on customers who won’t benefit.
