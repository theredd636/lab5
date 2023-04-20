READ ME FILE

In this file I will go step by step to explain how our Cuda code works

Firstly we made a Global function called square

This takes in three floats called D out and D in1 and D in2

This function sets two temp varaibles f and g to D in 1 and D in 2

We then say at the D out at element index is equal to F + G

We also malloced the memory using Cuda mallic

Then we used the cudaMemCPY command with Din and Hin 1 and 2 with ARRAY_BYTES

Next we created 3 float arrays called H in H in 2 and H out

We then set H in1 equal 0 , 1 ,2 ,3 and H in2 = H1[i] + 3

And H out = H1[i] + H2[i]

We then print out the matrixs and the results

After this the Cuda Malloc was freed using CudaFree
