# Classification_ML on APS

Background - APS generate pressurized air for various uses in truck such as brake & gears changes.

Problem Statement – APS failure can be due to specific component related to APS (Positive) or non-APS related (Negative). (Binary Classification problem)

Objective – Minimize the cost associated to AFS failure

Cost Metric (2 type of costs):
	1. Missing Faulty Truck leads to future breakdown
		cost: $500 (Type 2 error – False Negative)
	2. Unnecessary checks done by mechanic
		cost: $10 ( Type 1 error – False Positive)

Total Cost = $500 * (no of instance) + S10(No of instance)


