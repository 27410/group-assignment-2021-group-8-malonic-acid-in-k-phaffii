# Scripts

The scripts in this folders contain code and descriptions of the model analysis.

## create_pathway
Defines all pathways and returns a model with the selected pathway added.  
The function can be called alone or get assigned to a new variable, but it always alters the handed model. In order to not touch manipulate the existing model work within _with model:_ or create a copy of your model with _model.copy()_ before handing that copy to this function.

## improving_aspartate_supply
Adds two reactions through the enzymes: 
1. Aspartase (fumaric aminase)
2. Phosphoenolpyruvate Carboxykinase (ATP forming)

Evaluates the impact of these additions through FVA and Escher visualisation

## methanol_aasimilation
Analysing NADH and NADPH generation under different conditions and how they are affected by enforcing malonic acid production. Experimenting with manual cofactor swaps. 

## optimizing_use_of_malonic_semialdehyde
Adding alternative malonic-semialdehyde producing reactions and removing a reaction that consumes it.

## substrate_alternatives
Analyzing included carbon_sources for biomass growth and malonic acid production.

## selection_and_assessment_of_existing_GSM
Exploring the carveme and Kbase models and checking if growth on methanol is possible.


## Optimization_FSEOF
Flux scanning based on enforced objective flux analysis with a forced flux towards malonic acid production

## Optimization_OptCouple
OptCouple algorithm from supplementary material (Jensen 2019). Did not work.

## Optimization_OptSwap
OptSwap algorithm from cameo.

## Optimization_OptKnock
OptKnock algorithm from cameo. Did not work.

## Optimization_OptGene
OptGene algorithm from cameo.

## Optimization_GrowthCouplingPotential
Up to date OptCouple and OptKnock algorithms from github. Did not work.