### t-sne
t-sne is a much newer techinque which is used mainly for visualization of low dimension data which does a great job. Invented in 2008

It performs neighbourhood embedding while dimensionality is reduced by calculating its neighbour distance in the high dimension and replicating them even when transformed to low dimension such that information lost is decreased

### how it works:

All datapoints from the scatter plot is put down on a single axis and as distance information is saved by the model, points lie near to their neighbours as they were in higher dimensions. After putting them on a single axis, a t distribution is placed on top of them and a perpendicular line is drawn from each point to the disb and the distance is calculated as unsampled distance and then all points are sampled by diving their distance with the average distance such that the sum of distances of all points add up to one

Since we have grouped the points before plotting them on the disb, Closer points have scores that differ by less and the distant points differ by a large amount. From every point the distance from itself to all other points are calculated and consensus is made out of this that whether this point is my neighbour or not
