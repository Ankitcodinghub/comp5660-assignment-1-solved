# comp5660-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP5660 Assignment 1 Solved](https://www.ankitcodinghub.com/product/comp5660-evolutionary-computing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121326&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5660 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Synopsis

Problem statement

Your algorithm will designate a fixed number of (x, y) coordinate pairs as a solution representing a specific bridge design. The coordinate pairs represent nodes (connection points), which are automatically connected by frame elements (edges) if within a set distance from one another. These frame elements use set material and cross-section characteristics specified by a problem instance. During the physics simulation, frame elements will stretch, compress, and bend slightly under load until the forces in the bridge are at equilibrium, allowing their structural integrity to be determined. In addition to the coordinate pairs specified by your algorithm, there are pre-existing nodes at fixed locations that serve as the foundation of the bridge and connection points along the roadbed.

A solution’s fitness is evaluated with a function we have provided for you. This function constructs the bridge represented by your solution. The bridge is then tested using a physics simulation by applying an increasingly-heavy load to points within the roadbed until the bridge fails. Elements of the bridge will fail if their tensile, compressive, or bending stresses exceed the maximum amounts supported by their material and geometry. The bridge is considered to have failed if any element fails. The function then returns the force at which the bridge failed. Your algorithm’s goal is to find a solution that maximizes the value returned by this function, in order to design the strongest bridge possible under these conditions.

Version control requirements

After submission, your latest, pushed, commit to the default branch will be graded if it contains readyToSubmit.txt. In order to ensure that the correct version of your code will be used for grading, after pushing your code, examine your repo [https://github.com] and verify that you have submitted what you intended to. If for any reason you submit late, then please notify the TAs when you have submitted.

Submission, penalties, documents, and bonuses

The code pushed to the default branch after submission will be pulled for grading. Any files created by your assignment must be created in the present working directory or subdirectories within it. All Jupyter notebooks must be completed and submitted with results from running the full notebook. Your submitted code needs to execute as expected, within the base Conda Linux environment, without error. The TAs should not have to worry about any external dependencies or environments. Grading will be based on what can be verified to work correctly as well as on the quality of your source code. You must follow the coding requirements as stated in the syllabus. Always remember that the TAs will thoroughly examine everything by hand, and that your code being easy to read and understand is a substantial part of your grade (and their sanity).

Documents are required to be in PDF format; you are encouraged (but not required) to employ

LATEX for typesetting.

Deliverable Categories

There are three deliverable categories, namely:

GREEN Required for all students in all sections.

YELLOW Required for students in the 6000-level sections, bonus for the students in the 5000-level section. RED Bonus for all students in all sections.

Note that the max grade for the average of all assignments in Assignment Series 1, including bonus points, is capped at 100%. That is, if you received 100%, 100%, 90%, and 120% on the individual assignments, you will receive a 100% for Assignment Series 1.

Assignment 1a: Random Search

You must implement a random search algorithm which generates bridges by uniform random placement of coordinates within a predefined rectangular area.

In this assignment you are asked to complete the Jupyter notebook 1a notebook.ipynb, part of a Python class, and a report. The notebook will guide you through implementation where you will perform the experiments necessary to create the report. While implementing the changes listed in the notebook, think about what data you will need to record in order to write the report described below.

Once you’ve finished the notebook, you need to write a report. This report should include a stairstep plot showing evals vs fitness of the run which resulted in the most-fit solution. This report should also include statistical analysis (F-test and t-test) comparing the fitness obtained by each run to the sample data provided in your repository, and a brief discussion interpreting the results of the statistical tests. This sample data can be found in data/mysteryAlgorithmResults.txt. The deliverables of this assignment are:

GREEN 1 your source code and completed notebook

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s) should be saved to the data directory of your repo in a format that can be easily understood by the TAs (if you think you should include instructions on how to interpret your data, then you should!)

Grading

The point distribution is as follows:

Assessment Rubric Deliverable Category Green

Algorithmic 30%

Logging and output files 15%

Programming practices, readability, and implementation 15%

Report and plot(s) 20%

Statistical analysis 20%

Assignment 1b: Evolutionary Algorithm Search

You must implement an EA which generates bridges. This assignment will utilize the same framework that was utilized for Assignment 1a, and builds on some of the code you produced in that assignment. Treating the problem of bridge design as a black-box problem, your EA must generate bridges and use their evaluated fitness to search for higher-fitness solutions.

In this assignment you are asked to complete the Jupyter notebook 1b notebook.ipynb, several functions outside the notebook which will be reused in later assignments, and a report. The notebook will guide you through implementation of your EA, and will explain how to perform the experiments necessary to create the report. While completing the notebook, think about what data you will need to record in order to write the report described below.

Once you’ve finished the notebook, you need to write a report. This report should include an evalsvs-fitness plot showing the progress of evolution averaged over 30 runs. This report should also include statistical analysis (F-test and t-test) comparing the best fitness obtained by each run to data generated by the algorithm you implemented during 1a, and a brief discussion interpreting the results of the statistical tests. The report must also include every configured parameter used in your experiment.

The deliverables of this assignment are:

GREEN 1 your source code and completed notebook

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you should include instructions on how to interpret your data, then you should!)

YELLOW 1 Up to 10% (bonus points for COMP 5660 students) for an implementation of Stochastic Universal Sampling (see Figure 5.2, page 84 in the textbook) with accompanying report and statistical analysis comparing the impact on performance against another parent selection technique. You should create a new config file (i.e., create config file(s) in addition to green1b config.txt such that each file contains the configurations used in your comparison).

RED 1 an implementation of an extra variation (recombination or mutation) operator meaningfully different from the prescribed method(s). What does that mean? You tell us! Any correct algorithm that reasonably fits this definition can be submitted. Describe your design in your report and provide statistical analysis comparing performance against another recombination operator. Students can earn up to 15% for this investigation. You should create a new config file (i.e., create config file(s) in addition to green1b config.txt such that each file contains the configurations used in your comparison).

Grading

The point distribution is as follows:

Assessment Rubric Deliverable Category Green Yellow Red

Algorithmic and attempt at parameter tuning 40% 60% 60%

Passing unit tests 15% 0% 0%

Logging and output files 5% 5% 5%

Programming practices, readability, and implementation 10% 10% 10%

Report and plot(s) 15% 10% 10%

Statistical analysis 15% 15% 15%

Assignment 1c: Constraint Satisfaction and Multi-Objective Evolution

Using the EA you created in Assignment 1b, you must implement two new EAs. The first new EA is a constraint satisfaction EA that considers a new design constraint for allowing boats and other traffic to pass through the bridge. The second new EA is a multi-objective EA (MOEA) that considers both the weight your bridge can support and the total length of material needed to construct the bridge.

In this assignment you are asked to complete both of the Jupyter notebooks 1c0 notebook.ipynb and 1c1 notebook.ipynb, several functions outside the notebooks, and a report. The notebooks will guide you through implementation of your EAs, and will explain how to perform the experiments necessary to create the report. While completing the notebooks, think about what data you will need to record in order to write the report described below.

Once you’ve finished the notebooks, you need to write a report. The reporting requirements for each algorithm are different:

Constraint Satisfaction EA For each experiment, an evals-vs-raw-fitness plot showing the progress of evolution averaged over 30 runs, statistical analysis comparing the (F-test and t-test) comparing the best fitness obtained by each run to data generated by your EA employing both constraint satisfaction approaches described in 1c0 notebook.ipynb, and a brief discussion interpreting the results of the statistical tests. Note that for statistical analysis with the constraint satisfaction EA, you should use

the best raw fit ness.

Multi-Objective EA For each experiment, an evals-vs-fitness plot showing the progress of evolution for each objective averaged over 30 runs. This report should also include a plot of the best Pareto front found in any run, where we count Pareto front P1 as better than Pareto front P2 if the proportion of solutions in P1 which dominate at least one solution in P2 is larger than the proportion of solutions in P2 which dominate at least one solution in P1. Visualize the bridges of the individuals within the best Pareto front and comment on how they differ. Note: the green deliverables only require a single MOEA experiment without statistical analysis.

The report must also include every configured parameter used in your experiment or at least a reference to which file contains the parameters for each experiment discussed.

The same unit tests that were provided in Assignment 1b are included in your 1c repository. While failing unit tests will no longer count directly against your grade (they are not a deliverable), you will still be penalized if any of the algorithms implemented during 1b have errors. The unit tests can supplement your 1b feedback report in helping you resolve any remaining errors. The deliverables of this assignment are:

GREEN 1 your source code and completed notebooks

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you might should include instructions on how to interpret your data, then you should!)

YELLOW 1 Up to 10% (bonus points for COMP 5660 students) for implementing crowding as a diversity preservation mechanism. In order to maintain compatibility with the MOEA implementation prescribed within the notebook, crowding should be implemented such that a value [0,1) is added to all individuals in a level of non-domination proportional to that individual’s crowding distance relative to others in their non-domination level. Using a diversity metric of your choice, record the diversity of the Pareto front from the last generation of each run and perform statistical analysis (including F-tests

and t-tests) to compare against diversity observed in your GREEN deliverables. Plot the best Pareto front with crowding and compare with the front plotted from the GREEN deliverables to informally identify which algorithm performed better.

RED 1 Up to 10% bonus for implementing constraint satisfaction by casting it as a multi-objective problem that considers unpenalized fitness and negative count of constraint violations as the two maximization objectives. Perform statistical analysis (using F-tests and t-tests) to compare performance with your best Assignment 1c constraint satisfaction implementation using raw fitness. Report on your findings as appropriate.

RED 2 Up to 10% bonus for implementing a repair function that modifies an individual’s genotype such that the constraints are enforced (feel free to observe how constraint violations are checked in the constraint satisfaction simulation function). Perform statistical analysis (using F-tests and ttests) to compare performance with your best Assignment 1c constraint satisfaction implementation using raw fitness. Report on your findings as appropriate.

RED 3 The mayor of Auburn took a recent trip to the Golden Gate Bridge and has been inspired to request landmark-worthy bridge designs that make trade-offs between strength, required bridge material, and height. Up to 10% bonus for implementing and experimenting with 3-objective search using weight, negative bridge material, and bridge height. Find the best 3-objective Pareto front generated by a 30-run experiment using the criteria described earlier. Include in your report a 3D plot of this Pareto front. Using the individuals in this Pareto front and non-domination sort, form 2-objective Pareto fronts considering only the objectives shared with GREEN/YELLOW, respectively, and compare against the best Pareto fronts from those deliverables through informal analysis of Pareto front plots. Include these plots and your comparison in your report.

RED 4 We alluded in the notebook that rigorous analysis of multi-objective results is complicated! For up to 15% bonus, perform a rigorous comparison of the two MOEA configurations of your choice (that use the same objectives) using the hypervolume indicator metric as calculated using normalized values for each objectives. Include in your report a detailed description of the analysis technique as well as your results.

Grading

The point distribution is as follows:

Assessment Rubric Deliverable Category Green Yellow Red

Algorithmic 45% 60% 60%

Logging and output files 5% 5% 5%

Programming practices, readability, and implementation 20% 10% 10%

Report and plot(s) 15% 10% 10%

Statistical analysis 15% 15% 15%

Assignment 1d: Island-Model EA

Using the EA you created in assignments 1b and 1c, you must implement an island-model EA.

In this assignment you are asked to complete the Jupyter notebook 1d notebook.ipynb, several functions outside the notebook, and a report. The notebook will guide you through implementation of your EA, and will explain how to perform the experiments necessary to create the report. While completing the notebook, think about what data you will need to record in order to write the report described below.

Once you’ve finished the notebook, you need to write a report. This report should include an evalsvs-fitness plot showing the progress of evolution across all islands (e.g., calculate average and best fitness values across all islands) averaged over 30 runs. This report should also include statistical analysis (F-test and t-test) comparing the island topologies you implemented during this assignment, and a brief discussion interpreting the results of the statistical tests. The report must also include every configured parameter used in your experiment.

The deliverables of this assignment are:

GREEN 1 your source code and completed notebooks

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you might should include instructions on how to interpret your data, then you should!)

YELLOW 1 Up to 10% (bonus points for COMP 5660 students) for implementing an island-model MOEA using the MOEA components you implemented in Assignment 1c. Fitness should be calculated by performing non-domination sort on each island such that non-domination sort only compares individuals in the same population/island. This should provide interesting island-specific fitness definitions! Note that you should be able to reuse your island model implementation and the only modifications required should be to your main search function defined in the notebook. Your report should include an evals-vs-fitness plot showing the progress of evolution for each objective across all islands averaged over 30 runs. No formal statistical analysis is required.

RED 1 Up to 10% bonus for implementing an island topology meaningfully different from the prescribed topologies in the notebook. Experiment with your new topology using the single-objective task in the GREEN deliverables and perform statistical analysis (using F-tests and t-tests) to compare performance with your best configuration observed in this assignment. Report on your findings and methodology as appropriate.

RED 2 Up to 15% bonus for implementing and experimenting with heterogeneous island configurations (i.e., where the islands in your topology use different parameters). Experiment using the single-objective task in the GREEN deliverables and perform statistical analysis (using F-tests and t-tests) to compare performance with your best configuration observed in this assignment. Report on your findings and methodology as appropriate.

Grading

The point distribution is as follows:

Assessment Rubric Deliverable Category Green Yellow Red 1 Red 2 Red 3

Algorithmic 45% 50% 50% 50% 60%

Logging and output files 5% 5% 5% 5% 5%

Programming practices, readability, and implementation 20% 20% 10% 10% 10%

Report and plot(s) 15% 25% 15% 15% 25%

Statistical analysis 15% 0% 20% 20% 0%

References

[1] A. E. Eiben and J. E. Smith, Introduction to Evolutionary Computing. Second Edition, Springer-Verlag, Berlin Heidelberg, 2015, ISBN 978-3-662-44873-1.
