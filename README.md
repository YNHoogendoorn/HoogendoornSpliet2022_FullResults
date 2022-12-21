# HoogendoornSpliet2022_FullResults
Repository containing the full results regarding run instances of Jabali, Rei, Gendreau, and Laporte (2014). These results are from the paper "An improved integer L-shaped method for the vehicle routing problem with stochastic demands" by Hoogendoorn, and Spliet.

The .zip file "jabalietal2014_instances" contains the instance files of Jabali et al. (2014). We do not own these files and these are published with permission of the owner.

Next to the .zip file, the repository contains one Excel sheet, in which the full results are detailed. There are 27 classes of instances with 10 instances each. Each of them is named n_m_f_1_x, where n is the number of customers (including depot), m is the number of routes, f is the average fill rate and x is the instance number (ranging from 0 to 9).

Per instance 5 solver settings are run, named "Jab", "BM", "RS", "PRS" and "P+MRS". We refer to our paper for the explanation of the settings. Per instance and per setting, we show 
1. Sol. Val: the solution value (either optimal or best-known solution, if unavailable);
2. Gap: the optimality gap after 1 hour of solving (if 0, the found solution is optimal);
3. Time: the time needed to reach optimality, in seconds (or 3600 if the runtime exceeded 1 hour);
4. Nodes: the number of nodes explored in the branch-and-cut tree.

Per instance class an aggregate row is shown in boldface underneath the 10 instances of that class. This row shows, per setting
1. the number of instances of this class solved (in the column "Sol. Val");
2. the average optimality gap of the unsolved instances of this class, or 0 if all instances are solved (in the column "Gap");
3. the average time needed to solve the instances of the class, where unsolved instances are ignored (in the column "Time").

Finally, at the bottom of the sheet, in the row "All instances", we show the total number of solved instances per setting, in the columns "Sol. Val".
