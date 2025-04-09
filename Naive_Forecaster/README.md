# Naive Forecaster

This is the baseline version of an ongoing project with the goal of systematicaly evaluating economic forecast performance in Germany.

The currently available script is Naive Forecaster, which pulls real-time quarterly GDP-data from the Bundesbank (German Central Bank) and creates naive forecasts based on simple averages, simple moving averages or AR models, where a number of parameters may be customized. The model, training scope and prediction horizons may be selected. Puts out human-readable Excel-sheets into model-named result folders. You can find some explanations in the header of the code.

Future developments will evaluate these naive methods and conduct extensive evaluation of ifo's and possibly other's past forecast performance against them
