# PlannerAI

This code is used to implement a state-space planner program. Specifically, the code for the Custom planner was created for this project. Each planner (Custom, Breadth First Search, Partial Order Planner, Graph Plan, Black Box, Heuristic Search Planner, and Regression) will attempt to solve general step-by-step planning problems in several different domains. The results are then compiled in results.html.

The purposes of each of the following files are stated below:

benchmarks - a folder containg all of the planning domains and problems that will be used

planners - a folder containing all planners that can attempt to solve the planning problems
- custom.jar
- bfs.jar
- pop.jar
- gp.jar
- bb.jar
- hsp.jar
- reg.jar
- ff.jar
- iw.jar

classes - a folder containing Java class files
- CustomSolver.class
- AStarSearch.class

src - a folder containg the source code
- CustomPlanner.java - implements the Custom planner
- AStarSearch.java - implements a planner that uses simple A* search through the space of states

All other files under the src directory are part of an external Planning framework.

planning.jar - a program to test the provided planners against a series of planning problems

To compile and run the program, run the run-planner.bat file (Windows) or the run-planner.sh file (Mac/Linux).

To view the results, open the results.html file.

Code is available upon request.
