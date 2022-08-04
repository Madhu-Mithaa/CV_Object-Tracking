# Object-Tracking

# Mean Shift and Cam Shift

The mean shift algorithm is actually a broader statistical concept related to clustering. Like most other clustering algorithms, the mean shift algorithm attempts to look for places in the data set with a high concentration of data points, or clusters.

Before implementing the mean shift algorithm, an initial tracking box needs to be established. As the mean shift algorithm iteratively shifts points, the tracking box will move until surrounds the object of interest

Unfortunately, if the object shifts in size or changes orientation, the tracking box doesn’t accommodate the change.

The camshift (Continuously Adaptive Mean Shift)algorithm addresses this issue.
Working very similarly as the mean shift, the cam shift algorithm simply adjusts it so that the tracking box may change in size or even rotate to better correlate to the movements of the tracked object.


In our Case , The CamShift algorithm performs better than the MeanShift algorithm in person tracking tasks. This could be due to the fact that CamShift (Continuously Adaptive MeanShift) is an improved version of the mean shift algorithm. 
