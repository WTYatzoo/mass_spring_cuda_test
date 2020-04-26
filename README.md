# mass_spring_cuda_test
<img src="https://github.com/WTYatzoo/WTYatzoo.github.io/raw/master/gallery/3_version_mass_spring.png" width="400" />

This figure is the result of three versions of mass-spring based cloth simulation with a cloth-fixed rigid sphere coupling example: left: using classical newton method, middle: using fast mass-spring method based on the paper Fast Simulation of Mass-Spring Systems, right: using modified fast mass-spring based on the paper A Chebyshev Semi-Iterative Approach for Accelerating Projective and Position-based Dynamics with a CUDA version Jacobi solver acceleration.

See the dynamic video here:  https://www.bilibili.com/video/BV1K541147fz/ . From the left to right, it is the comparison of Chebyshev Semi-Iterative Approach, fast mass spring and Newton method for the cloth simulation without processing self-collisions. In the highlighted detail, we can see that the oscillation happens. Notice the obvious oscillation at the 12th second in the left part of this video which is the result based on Chebyshev Semi-Iterative Approach !!! Observe here：<img src="https://github.com/WTYatzoo/WTYatzoo.github.io/raw/master/gallery/oscillation.jpg" width="400" />
