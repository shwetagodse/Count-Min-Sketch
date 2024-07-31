Frequency estimation in large datastream using Count Min Sketch: In this problem we are given a stream of data points that are arriving one-by-one.
You have very limited memory available with you to store a small sketch/footprint of the data stream such that using that sketch we can estimate the 
frequency of a given query point. The size of datastream could potentially be in GB/TB however the sketch size is usually in MB/KB. We have to use the 
count sketch algorithm for the task. 

Then, validate the algorithm on the transaction dataset T10I4D100K (or any other dataset of similar scale). You can use the RMSE metric for evaluation  
-- square of the difference between the actual frequency of the item and its estimation from Count Min Sketch, sum it for all the query items, and compute
the square root of the result. Plot the RMSE for various values of the sketch dimension -- X axis should contain the sketch dimension and Y axis should 
contain the RMSE value.. 
