
#  E2E samples to get started with Intel oneAPI  AI analytics toolkit

This RHODS environment with Intel® oneAPI AI analytics toolkit aims to deliver high-performance DL workload on Intel® XPUs with Intel-optimized TensorFlow* and PyTorch*, Intel Model Zoo, and LPOT(Low precision optimization tool). The toolkit also includes drop-in acceleration for data preprocessing and machine learning workflows with compute-intensive Python* packages: Modin*, scikit-learn*, daal4py and XGBoost*.

This Jupyter hub environment also features e2e samples  to get started with understanding how Intel® oneAPI AI analytics toolkit delivers optimized solutions for DL and ML workflows. Below are the list of samples:

1. **E2E_use_case_with_Intel_optimized_Tensorflow_LPOT**: This sample utilizes Intel-optimized Tensorflow and LPOT( Low Precision Optimizations Tool) in the Intel® oneAPI API analytics toolkit offered in the RHODS environment. The sample will train MNIST with Intel-optimized Tensorflow on alexnet, followed by quantizing with LPOT to convert fp32 trained model to int8 low-precision model and perform optimized inference. This sample will also provide performance and accuracy comparisons on fp32 vs int8 inference highlighting the importance of using LPOT in Intel® oneAPI AI analytics toolkit to  perform low-precision inference. Open the lpot_sample_tensorflow.ipynb notebook and follow the instructions.

2.  **E2E_use_case_with_Intel_Modin_Intel_optimized_scikit-learn**: This sample will introduce users to trivial extensions of using Intel Modin and Intel® Extension for scikit-learn from the Intel® oneAPI API analytics toolkit offered in the RHODS environment.  The sample trains US Census data with Intel® Extension for scikit-learn and utilizes Intel Modin on Pandas to perform optimized data preprocessing calls such as read_csv and other ETL operations.  Open the census_modin.ipynb notebook and follow the instructions.

3. **E2E_use_case_with_Intel_optimized_XGBoost_daal4py**: This sample utilizes the Intel performant XGBoost package (> 1.0 version) to train on higgs dataset, and daal4py package for additional acceleration to run predictions.  Open the IntelPython_XGBoost_daal4pyPrediction.ipynb notebook and follow the instructions.

4. Intel Model Zoo is also shipped as part of the toolkit and can be found in the "models" folder. Go to models/quickstart on how to run various models offered as part of Intel Model Zoo 

For more samples, goto https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics
