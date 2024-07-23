# StaticPricingforQueues
This repo contains a jupyter notebook which is used to produce the numerical results found in the article "Static Pricing for Queueing Systems."

To reproduce the results, scroll to the final cell. Then enter the number of servers you want to test, the demand type ('linear', 'exponential', or 'logistic'), the model type ('congestion' or 'sojourn'), and the number of instances. If you wish to test different demand parameters, edit the generation of a, b, and p0 in experiments function. Once the parameters are ready, run all cells from top to bottom. The results of runs are saved in a pickle file, and re-loaded if such a pickle file already exists. The results are saved in a dictionary format.
