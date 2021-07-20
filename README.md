# openaspirin
A method to make aspirin tablets (acetylsalicylic acid) from natural materials.

Definitions:
This project uses the process graph (p-graph) method of F. Friedler et al. to represent the process. Please read "Graph-theoretic approach to process synthesis: axioms and theorems" (Friedler et al. 1992) at https://doi.org/10.1016/0009-2509(92)80315-4 before contributing.

The main branch is for the complete process from material vertices to the final "aspirin tablet" material vertex.
A "step" will be defined as a triplet of: material vertex, subsequent adjacent operation vertex, and subsequent material vertex from that operation.

Contributions:
All steps in this repository are given in text (.txt) files, EACH FOR A SINGLE STEP (e.g. "step_1_{description}.txt").
What goes in place of {description} should be short and be of the form "{resultingmaterialname}_from_{processname}_ {startingmaterialname}".
Use the following order for contents in each text file:
1. Description: Give a description of what the step sequence will accomplish for the overall process in the main branch.
2. Inputs: state as input the prior step's final material vertex.
3. Outputs: state as output the final material vertices resulting from this step sequence.
4. Procedure: describe step-by-step the procedure used to transform the inputs to the outputs.
5. Yield: state the purity of the output if applicable.
6. Time cost: state the time cost in units of time/mass.
7. Notes: state any other notes that are helpful to people
8. Demonstration: Give a full YouTube link (not shortened) of a demonstration of the procedure above. You MUST include a demonstration before submitting a text file. We will use YouTube because of that platform's few predatory links, fast loading, and good quality transcoding to save on internet data use.

For time cost, assume a precision of [time/mass] ± 100%.

END README