# SOS-2022
Advances in Nuclear Fusion

**Python Assignment:**

You have two graphs, each of which has an x-axis and y-axis range of real numbers from 0 to 100. 
You have 100 points marked in each of the plots and the claim is that the location of points in both plots is the same. 
However, the graphs do not exactly overlap. The points might have slightly different coordinates in both plots. 
Can you devise a measure of how different the two plots are? 
There may be more than one solutions. Assume that you have the datasets for the graphs.

In the solution, make some dataset and demonstrate your code for that.

**My Approach:**
I began thinking about how, if there were a line connecting the scattered points (say they have some sort of strong correlation or form a distinct curve)
of Dataset 1, and D2 being very similar to D1, then we could also draw out a similar curve connecting D2. This would essentially create 2 offset curves, 
and the area between them would be a measure of the lack of overlap.
This method comes with quite a few caveats:
  firstly, how will you decide how to connect the points. in each dataset, they can be connected in any order.
    here, I decided to connect them in order of increasing x-coordinate, after trying circular/ loop-like iterations (summing the x- and y-coordinates, 
    and connecting the points on increasing order of this sum), and not gaining much out of the additional computation effort. 
      one alternative I thought of here, was that if the 
      
why area?
0
0
