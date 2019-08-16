# bd-15-hlt-assessment-sjncube

Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate. You will use these data to predict the compresive strength of a concrete block. The actual concrete compressive strength (MPa) for a given mixture - our training data was determined in a laboratory. Data from here

We now want to be able to predict concrete compressive strength without needing to measure it in a lab. You will need to read the data into spark, clean it by removing some missing values, and prepare it for model fitting. You will then need to fit an appropriate machine learning model, and output your predictions and saved model.

You can find the data in the file concrete.csv. Once you have built your best model with these data. Please make predictions on these new data concrete_unmeasured.csv for which we do not know the concrete compressive strength.
