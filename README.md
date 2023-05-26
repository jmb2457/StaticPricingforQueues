# StaticPricingforQueues
This repo contains a jupyter notebook which is used to produce the numerical results found in the article "Static Pricing for Queueing Systems."

To reproduce the results, scroll to the cell which starts with "#Test Parameters." Then enter the number of servers you want to test, the demand type, and the number of instances. If you wish to test different demand parameters, edit the generation of a, b, and p0 in the following loop. Once the parameters are ready, run all cells from top to bottom. After the run is completed, the performance ratios are contained in 6 different lists. The final few cells report the mean and the minimum of the performance ratios for the instances just run.
