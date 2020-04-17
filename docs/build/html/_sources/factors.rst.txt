.. _factors:

#######
Factors
#######

Factors are the treatments or interventions which are manipulated on your experiment.

What is a factor?
=================

Why do we use the term factor?
==============================

People use several different terms to describe factors, including treatments, variables and interventions.
We use the term factor to be consistent with published formal ontologies for statistics and agriculture. 
We have deliberately avoided the term *treatment* as this can be confused standard farm practice for an experiment.

For example, if nitrogen fertilizer is applied at different rates to different plots then nitrogen fertilization is the 
*factor* and each rate is a different *factor level*. Nitrogen **should** therefore be documented as a factor in the GLTEN
metadata schema. If phosphorous is applied to the experiment plots but at the same rate for all plots 
then it is not considered a factor. In this example phosphorous is part of standard management practice for the 
experiment and **should not** be documented as a factor in the GLTEN metadata schema.

A factor can therefore be anything which is varied across the experiment by the researcher. A factor is
a general type, range or category of treatments. 

What is a factor level?
=======================

A factor level is one of the different interventions for a factor. For example, for the factor Nitrogen fertilization, rates of 50, 100, 150 and 200 kgN/ha 
would each be a factor level; the factor *Nitrogen fertilization* has 4 factor levels.

A factor level can also be categorical. For example, the factor *tillage process* can have 3 factor level categories:
no tillage, minimum tillage and conventional tillage

What is a factor level combination?
===================================

In an experiment with two or more factors, a factor level combinations is a group of one factor level from some or all of the 
different factors. 

For example, an experiment has two different factors with the following factor levels:

* Nitrogen fertilizer exposure (factor)
    #. 0 kgN/ha (factor level)
    #. 50 kgN/ha
    #. 100 kgN/ha
    #. 150 kgN/ha
    #. 200 kgN/ha
* Tillage process
    #. no tillage
    #. minimum tillage
    #. conventional tillage

An example of a factor level combination here would be 50 kgN/ha x minimum tillage.
If this is a full factorial experiment, where every possible combination of factor levels are present
there would be 15 factor level combinations in the study (5 Nitrogen levels x 3 tillage levels).

In the GLTEN metadata schema, for a full factorial experiment it is not necessary to describe every factor level combination. 
The factor level combination section is reserved instead for non-full factorial experiments. Using the factor level
combinations section you can describe the combinations which are present.  

