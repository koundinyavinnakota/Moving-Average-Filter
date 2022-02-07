# Moving-Average-Filter

The moving average filter is a simple Low Pass FIR (Finite Impulse Response) filter commonly used for regulating an array of sampled data/signal. It takes M samples of input at a time and takes the average of those to produce a single output point. As the length of the filter increases, the smoothness of the output increases, whereas the sharp modulations in the data are made increasingly blunt.

In this project, the moving average filter is applied on the data collected with the vehicle at rest, in an effort to calibrate the accelerometer.


Six different Moving averages(Two-point, Four-point, Eight-point, Sixteen-point, SixtyFour-Point and OneTwentyEight-point averages) have been computed for the data and the results have been compared.
