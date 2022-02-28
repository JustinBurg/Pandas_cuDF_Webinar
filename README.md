# Using Rapids
These notebooks compare RAPIDS on GPU's to conventional Python tools on CPU's.

1. cuDF compared to Pandas
The movies notebook compares the cuDF API to the Pandas API. In many cases switching code from CPU to GPU is seamless. In other cases some adjustments are required. Click here to download the data.

2. GPU compared to CPU
The babynames notebook compares performance between a single GPU and a single CPU. All tests showed double digit performance improvements when run on a Tesla P4. Results will vary depending on the system environment. Click here to download the data.
