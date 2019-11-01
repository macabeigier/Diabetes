## Diabetes

>About 422 million people worldwide have diabetes, particularly in low-and middle-income countries. Diabetes is a chronic, metabolic disease characterized by elevated levels of blood glucose (or blood sugar), which leads over time to serious damage to the heart, blood vessels, eyes, kidneys, and nerves. The most common is type 2 diabetes, usually in adults, which occurs when the body becomes resistant to insulin or doesn't make enough insulin. In the past three decades the prevalence of type 2 diabetes has risen dramatically [[1]](https://www.who.int/health-topics/diabetes)


## Goals of the exercise

1- Take the original _Diabetes_ dataset and preprocess it to get the toy dataset that comes with `scikit-learn`.

2- Given features like age, sex and blood sugar and lipid levels predict the disease progression of diabetes patients after one year.


## Diabetes dataset

>Database obtained from Bradley Efron, Trevor Hastie, Iain Johnstone and Robert Tibshirani (2004): "Least Angle Regression", Annals of Statistics (with discussion), 407-499.
There are ten baseline variables and six blood serum measurements obtained for each of n = 442 diabetes patients, as well as the response of interest, a quantitative measure of disease progression one year after baseline. Each row corresponds to the values of one patient [[2]](https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html)

**_Variables_**:

_age_<br/>
_sex_: 1 (male), 2 (female) <br/>
_bmi_: body mass index (kg/m<sup>2</sup>) <br/>
_bp_: average blood pressure (mm Hg)

**_Blood Serum Measurements_**:

_s1_: tc, total cholesterol (mg/dl)<br/>
_s2_: ldl, Low Density Lipoprotein (LDL) (mg/dl), "bad cholesterol"<br/>
_s3_: hdl, High Density Lipoprotein (HDL) (mg/dl), "good cholesterol"<br/>
_s4_: tch, ratio total cholesterol / HDL<br/>
_s5_: ltg, triglycerides (mmol/l)<br/>
_s6_: glu, glucose (mg/dl)

**_Response_**:

_y_: a quantitative measure of disease progression one year after baseline