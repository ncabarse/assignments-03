# Question 1: 

When plugging in different numbers into the dartboard, I decided to increase the number of darts by 250. By doing this, I was able to see that the decimal places were much more accurate after each time, and the estimation would become closer and closer. 

Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 250 | java Dartboard
Pi Estimate: 3.344
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 500 | java Dartboard
Pi Estimate: 3.224
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 750 | java Dartboard
Pi Estimate: 3.1093333333333333
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 1000 | java Dartboard
Pi Estimate: 3.148
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 1250 | java Dartboard
Pi Estimate: 3.1712
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 1500 | java Dartboard
Pi Estimate: 3.152
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 1750 | java Dartboard
Pi Estimate: 3.0994285714285716
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 2000 | java Dartboard
Pi Estimate: 3.186
Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 2250 | java Dartboard
Pi Estimate: 3.1004444444444443


As the number of darts increase, the more accurate it gets bit by bit. 

# Question 2

After a certain number, there is a point of diminishing return where the number of darts will not change how accurate the estimation of pi will be. The point where the entire dartboard is filled is when it cannot become more precise. At around 165000 darts is when the entire dartboard is filled. 

Nicholas-Cabarses-Mac:piEstimator NICH$ java piEstimator 165000 | java Dartboard
Pi Estimate: 3.140969696969697
