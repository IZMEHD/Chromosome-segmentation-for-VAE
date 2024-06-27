# Chromosome-segmentation-for-VAE

Please see the Python notebook demo provided


This VAE is a by product of our work which investigates the effect of segmentation strategies on SNP sequences from chromosome 22. 
We investigate how VAE performance is impacted by segmentation strategies. 
To achieve this, we first developed a performant VAE architecture that can accurately represent the potential performance improvements which may result from an optimized SNP sequence segmentation. 
We first investigated the effect of segment size and discussed ways to identify the optimal segment size to maximize VAE performance. 
We have shown that VAE performance highly depends on segment size and that the optimal segment size depends on the amount of data available and on the position within the chromosome. 
We have demonstrated that it is possible to achieve a reconstruction accuracy of 98.60% by optimizing the segment length throughout the chromosome. 
Additionally, a faster method utilizing SNP correlation was developed, which achieves a reconstruction accuracy of 98.58%.
