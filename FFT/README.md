
We use a parameter m to set the size of the FFT application. The number of jobs is N = 2m − 1 + m log(m,2), where m = 2k for some integer k. The number of recursive call tasks is 2m − 1 and the number of butterfly task is mlog(m,2). The number of recursive call level is 1+log(m,2), and the number of butterfly level is log(m,2). Furthermore, an FFT workflow enjoys a symmetry.
The aggregated execution time of the jobs on any path from the starting job to any of the exiting jobs is equal. Thus, any path in an FFT DAG is a critical
path. 

Here is an example picture of the FFT application with m=4.

![FFTimage](https://github.com/thewayonly/images/blob/master/imagefolder/FFT.png)
