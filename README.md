# seed-everything
Guarantee the reproductivity of your deep learning algorithm implemented by Pytorch\\
# Motivation
Based on my experience, I have seen too many papers whose results cannot be replemented almost the same as they claimed. Some of them are **far away from** the claimed results. 
To the best of my knowledge, except for some **hidden** reasons(You know it), the main cause is that most algorithms run on GPUs. Due to some optimization mechanisms on **Pytorch** and **cuda**, the results are different even on the same GPU at different times. And the results on GPUs and CPUs are different, too. 
# Solution
You just need a **seed_everything** function to get the same results every time on the same device, no matter on GPU or CPU. This function also guarantee the same results on GPUs or CPUs that are one the same server. Powerful function right? Trust me, it's both benificial for you and other researchers in deep learning.  
I hope you support this function, and support deel learning.  
