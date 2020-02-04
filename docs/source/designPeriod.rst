#############
Design Period
#############

Experiment design
#################

Every long-term experiment must have an experimental design. In the GLTEN metadata schema, the experiment design can include the following:

* Experiment design, including the number of replicates and plots.
* Crops and crop rotations.
* Factors, also known as treatments and interventions.
* Measurements and observations made.

Overtime LTEs modifications can be made to an experiment which change the overall design. The GLTEN metadata schema uses the Design Period concept
to describe these significant changes. For example, in 1968 the 
 `Broadbalk wheat experiment <https://www.glten.org/experiments/1>`_ introduced crop rotations and modern short stem cultivars; in the GLTEN,
this is treated as a separate design period to the preceding years. 

Not every change needs to be documented as a different design period. The recommendation is to create a new design period for a significant change, 
such as introducing a new factor. 

Recommended fields
******************

Design Period Name
    The name given to the design period. If you only have one design period this can be left blank, but it is recommended to provide a name for experiments with two or more periods 

Start Year, End Year & ongoing
    If the experiment only has one period this can be left blank. If youre experiment has two or more design periods you should indicate the start and years for each period. Only the most recent period can be ongoing. 

Design type
    Select an appropriate experiment design type from the list. If none matches, select *other* and provide a description in the *Design description* text box.

Design description
    Use this text box to provide a more detailed description of the experiment design. 

Description
    Use this to provide comments about this design period, for example, minor changes.

Number of plots
    Use this to indicate the number of plots in the experiment. In the GLTEN schema, a plot is defined as the primary unit (area of land) of interest.

Number of replicates
    The number of replicates (i.e. plots receiving the same factor levels). 

Optional fields
***************

Harvests per year
    Indicates the maximum number of harvests per year. 

Factorial
    Indicates whether or not the experiment is factorial, i.e all combinations of factor levels 
    are present in the experiment.

Crops
#####

Add the crops grown on your experiment here. In most cases you shouldn't specify cultivars or varieties here. 
If your LTE is evaluating different cultivars you should specify these as a *Factor*. 

If crops are grown in rotation you can specify the rotation order in the next section. 

Crop Rotations
##############

The crop rotation section lets you describe the crop rotation(s) used in your experiment. 

If you use crop rotation as a factor in your experiment you should still enter the rotations here 
and **not** in the *Factors* section. 
You should use the *Is factor?* option to indicate the crop rotation is a factor category. 

For more detail on crop rotation terminology please review the :ref:`crop rotations help <cropRotations>`. 

Mandatory fields
****************

Crop rotation name
    This is a meaningful name for the rotation and is especially helpful if you have several different rotations.

Is factor
    Check this box if crop rotations are used as an experimental factor.

Phasing
    Use this to state whether or not the rotation is fully phased (i.e. all phases of the rotation are present each year) or not.

Phases
    Add each crop as a phase. The drop down list is generated from the list of crops added to the previous *Crops* section, 
    so make sure you have added all the crops cultivated in the LTE design period (if not you can easily go back and add them).
    
    If two crops occur in the same phase click the *same phase* button for the later crop. 
    You now should see the two crops are now listed in the same phase.

Optional fields
***************

Start Year and End Year
    If the crop rotations have changed during the design period, use these fields to state when a specific rotation was used. 

Factors
#######

For more detail on factors terminology please review the :ref:`factors help <factors>`.

Measured Variables
******************
