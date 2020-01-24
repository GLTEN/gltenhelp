#############
Design Period
#############

Every long-term experiment must have an experimental design. In the GLTEN metadata schema, the experiment design can include the following:

* Experiment design, including number of replicates and plots.
* Crops and crop rotations.
* Factors, also known as treatments and interventions i.e. the different things being tested.
* Measurements and observations made.

Overtime LTEs modifications can be made to an experiment which change the overall design. The GLTEN metadata schema uses the Design Phase concept
to describe these significant changes. For example, in 1968 the Broadbalk wheat experiment introduced crop rotations and modern short stem cultivars; in the GLTEN,
this is treated as a separate design phase to the preceeding years. 

Not every change needs to be documented as a different design phase. The recommendation is to create a new design phase for a significant change, 
such as introducing a new factor. 

Recommended fields
==================

Design Period Name
    The name given to the design period. If you only have one design period this can be left blank, but it is recommended to provide a name for experiments with two or more periods 

Start Year, End Year & ongoing
    If the experiment only has one period this can be left blank. If youre experiment has two or more phases you should indicate the start and years for each period. Only the most recent period can be ongoing. 

Design type
    Select an appropriate experiment design type from the list. If none matches, select other and provide a description in the *Design description* text box.

Design Description
    Use the Design Description text box to provide a more detailed description of the experiment design 

Description
    Use the Description text box to provide comments about this design period, for example, minor changes.

Number of plots
    Use this to indicate the number of plots in the experiment. In the GLTEN schema, a plot is defined as the primary unit (area of land) of interest.

Number of replicates
    The number of replicates (i.e. plots receiving the same factor levels. 

Optional fields
===============

Harvests per year
    Indicates the maximum number of harvests per year 

Factorial
    Indicates whether or not the experiment is factorial, i.e all combinations of factor levels are present in the experiment.

*****
Crops
*****

Add the crops grown on your experiment here. In most cases you shouldn't specify cultivars or varieties here. 
If your LTE is testing different cultivars you should specify these as a *Factor* 

If crops are grown in rotation you can specify the rotation order in the next section. 

**************
Crop Rotations
**************

The crop rotation section lets you describe the crop rotation(s) used in your experiment. 

If you use crop rotation as a factor in your experiment you should still enter the rotations here and **not** in the *Factors* section. 
You should use the *Is factor?* option to indicate the crop rotation is a factor catgegory. 

For more detail on crop rotation terminology please review the :ref:`crop rotations help <cropRotations>`. 

*******
Factors
*******

For more detail on factors terminology please review the :ref:`factors help <factors>`.

******************
Measured Variables
******************
