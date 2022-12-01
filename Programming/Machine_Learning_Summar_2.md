# ML Flow.
### 1. Problem Specification.
- Classification: discrete target variable.
- Regression: continuous target variable.
### 2. Pipeline Construction.
- Pipeline: a series of the whole machine learning process one by one, from the start to the end.
  - Component: each stage of pipeline.
- Independency: independent process to other components.
- Asyncronization: asyncronized update to other components.
### 3. Construction of Technical and Concrete Parts.
- Model Design.
- Uni Variate Problem/Multi Variate Problem.
### 4. Selection of Performance Measurement.
How to determine accuracy.
- RMSE (Root Mean Square Error).
  - In regression, most used.
  - $L_2$ norm.
  - $RMSE(X,h)=\sqrt{\frac{1}{m}\displaystyle\sum_{i=1}^{m}(h(x^{(i)})-y^{(i)})^2}$
- MAE (Mean Absolute Error).
  - In regression.
  - $L_1$ norm.
  - $MAE(X,h)=\frac{1}{m}\displaystyle\sum_{i=1}^{m}\left\lvert h(x^{(i)})-y^{(i)}\right\rvert$
 > $L_k$ norm.
 > - Scalar: one number.
 > - Vector: one assembly of scalars, e.g., $v = <1, -1, 2>$
 > - Norm $(L_K$ norm): one-number representation of vector.
 >    - $L_k$ norm of $v$ = $(\lvert v_1 \rvert+\dots +\lvert v_d \rvert^k)^\frac{1}{k}$ (d: number of elements of vector).
### 5. Installation of Virtual Environment.
- Virtual Environment.
  - Independent Running Environment by Project.
  - Can have different versions of packages from other virtual environments.
- Command (in prompt).
  - Creation: conda create -n *name_of_virtual_environment* (python=*version*)
  - Activation: conda activate *name_of_virtual_environment*
  - Deactivation: conda deactivate
  - Deletion: conda remove --name *name_of_virtual_environment* --all 
### 6. Data Validation.
Checking normality and correctness of data itself (regardless of problem).
### 7. Split Test Set from Train Set.
### 8. EDA (Exploratory Data Analysis) with Train Set.
Analysis and Manipulation, Mathmatical and Scientific Computaion, Visualization of Data using Pandas, Numpy, Matplotlib Libraries.
### 9. Data Rendering (including preprocessing).
- Nominal Variable/Numerical Variable Cheking.
- Uniting Various Units.
### 10. Model Seclection, Training, Test, Performance Improvement (tuning), Final Model Release.
### 11. Monitoring and Maintenance.
