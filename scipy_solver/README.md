# Comments on (CoulombPotential(x,args) + HamonicPotential(x,args))*10**22

At the beginning of optimization, I cannot get a reasonable crystal geometry. When I look at the output of objective function,
I found the absolute value is really small (around 10^-22). Then I realize maybe this value is too small compared to the accuracy
of the optimization algorithm. To handle this problem, one way is to change the accurary, but I choose the easiest one just
increase the value of objective function. This is why I times an additional factor 10^22.
