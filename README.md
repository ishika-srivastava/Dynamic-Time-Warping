# DYNAMIC TIME WARPING
Dynamic Time Warping (DTW) was introduced in 1994 by Berndt and Clifford. It is used to compare or calculate the distance between two arrays or time series with different lengths.
DTW algorithm has earned its popularity by being extremely efficient as the time-series similarity measure which minimises the effects of shifting and distortion in time by allowing “elastic” transformation of time series in order to detect similar shapes with different phases.
Since the Dynamic Programming algorithm lies in the core of DTW it is common to call this distance function the “cost function” and the task of optimal alignment of the sequences becomes the task of arranging all sequence points by minimising the cost function (or distance).

DTW technique has been used for speech and word recognition since the 1970s with sound waves as the source.
It can be used not only for pattern matching but also for anomaly detection.

![image](https://github.com/ishika-srivastava/Dynamic-Time-Warping/assets/102409555/a7ff3e82-3253-4f1e-bf91-163cad0079be)

- ### Time Complexity
  O(m*n)
  m and n represent the length of each sequence

- ### Faster techniques for DTW
  Pruned DTW, Sparse DTW and Fast DTW

- ### WHY TO USE DTW?
  It gives a non-linear (elastic) alignment between two-time series. 
  This produces a more intuitive similarity measure, allowing similar shapes to match even if they are out of phase in the time axis.

- ### REPRESENTATION OF DTW
  The basis of DTW is found in the computations of the distance/confusion matrix between two-time series.

- ### WARPING FUNCTION
  To find the best alignment between time series A and B, the path through the grid minimises the total distance between them. It is given as:
  #### P = p1,…,ps,…,pk     
  #### ps = (is, js)
  P is called a Warping Function
