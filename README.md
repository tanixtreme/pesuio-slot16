# pesuio-slot16
actual problem -> statistical solution
via EDA - exploratory data analysis

performance matrix(pm) - MAPE, MAE 
statistical solution is pm
data split - 70-30 , 70% training 30%testing  
first 70 values is for training and rest for testing , model gets 70% while training
smaller datasent- 80-20 split

mae-mean absolute error - difference between actual and predicted vale
mape- mean absolute percentage error - percentage of difference between actual and predicted value
mape=0 for the training dataset it is called overfitting( model is fitting very tightly in the dataset)

variance and bias 

sgq -> scenario gap quest 
scenario - stakeholders roles and responsibility , expectation 
future - some % inc or dec , action , outcome(benefit)

holt winters model - predict next quater 

Python libraries:NUMPY, PANDAS, MATPLOTLIB

SGQ- Scenario Gap Quest   
Scenario - Stakeholders, Roles and Responsibility, Expectation    
Gap-    
Future - some % inc or dec, action, outcome

Every model has seasonality and stationality- the data spit of 30% and 70% is used to determine 

if MAPE is 0%- overfitting(model is fitting very tightly to the data set.)
ypes of hypothesis testing- z,t,chi squared, ANOVA(null & alternate)

hypothesis testing inference -> pass parameters -> MODEL -> hyper tuning(done if actual value and prdeicted value has 50-55% similarity ratio, increases to 75%)

if actual value and prdeicted value has 5% similarity ratio-wrong prediction(skip that mode             ]_training data
if actual value and prdeicted value has 95% similarity ratio-no hyper tuning required                   ]

testing-if mape is < 15%-perfect prediction




seasonality graph-x-axis=date
                  y-axis=prediction value
if graph has slope-multiplicativity
if graph has no " -additivity

don't split data as 70-30 using python func, split manually cuz python splits data randomly and not yearwise or monthwise

Python documentation- helps us to determine the models to be imported (ARIMA model)

ARIMA- Auto Regressive Integrated Moving Average
pdq values-parameters
PACF- Partial Auto Correlation Graph }......for p and q values
ACF- Auto Correlation Graph (figure) }
in order to simplify the prediction graph-we can do a)differentiation continuously until we reach negative values->that will be the simplest graph(d value)
                                                    b)differencing " " " " " (2nd-1st, 3rd-2nd...)
                                                    c)apply log on both sides " " " " " 

seasonality: preditcatble data
stationality: cannot be predicted,p<0.05(after running adf test)
adf test,kpss test
Why two diff tests?                                                    

shortcut method-use three for loops in order to get the least aic value(d value)

model_fit.summary() gives the summary of the dataset
model_fit.predict() gives the prediction of datavalues
model_fit.forecast(step=n) gives the forecast for n values


PART I-
1)Problem Statement
2)SGQ
3)Representation

PART II-
1)EDA

PART III-
1)Model
2)LSTM(mainly for stock market analysis)
3)PM

PART IV-
PRESNTATION -> 1.TECH and NON-TECH
