"# PathSF-Data-Prep" 
The Path Selection Function (PathSF) approach employed here is presented in [Zeller et al. 2016](https://www.researchgate.net/publication/283492008_Using_step_and_path_selection_functions_for_estimating_resistance_to_movement_pumas_as_a_case_study), Using step and path selection functions for estimating resistance to movement: pumas as a case study. In contrast to traditional Step and Path Selection Functions, this approach allows the examination of different scales of selection for explanatory variables. Following a resource selection framework, the 'used' data is the explanatory variables under each telemetry path. The 'available' data is summarized by a kernel around each path. This kernel can be estimated from the distribution of movement steps in the data or some other biologically relevant kernel. This example uses a Gaussian kernel. By adjusting the bandwidth of the kernel, different extents of available can be examined, which correspond to different scales of selection. 

This code provides an example of how to prepare the data to run a Path Selection Function with this approach. This code does not provide information on running the conditional logistic regression models. There may be another rmarkdown file providing this information in the future.

