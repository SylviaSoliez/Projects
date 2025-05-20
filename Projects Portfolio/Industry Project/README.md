Project Abstract:
# STAT480  – Statistical Consulting (Spring 2023)
## Description:

I was assigned a partner to work on an unstructured project for a real industry client. The data was massive which included 15 KPIs, and 5 economic indicators (including the client’s business revenue) with some dating back to January 1900. The goal was to go nuts with the data, and report back with any interesting findings, particularly which KPIs and corresponding lags did well for predicting the client’s revenue. We decided to use lags and leads up to two years out, and ideally at least one year out.

## Analysis methodologies:

I worked on a prescriptive regression with ARIMA errors model. This topic was barely touched on in a previous class, but this was the clear choice to use based on the extensive research I performed.

## Programming:

I used JMP and R for EDA, and programmed in R. The data was in a .xlsx file.

## Post Project Debrief:

This was an intense project, and my first experience with an actual client. Halfway through the semester we had our first schedule meeting to kick off the project. It turned out that our client was very prepared, as it was more of a presentation on their end; but I was able to ask pertinent questions at the end.

I settled on modeling the data with Regression with ARIMA errors model. Fitting the model was a gruelingly long and manual process. The process itself was to prewhiten the data to the response and take the suggested lags from this and fit the model. I would then use ARIMA errors to make sure the model assumptions were in check. The model had an issue of scale, as there were many KPIs that had high collinearity and many lags across each one. The model fit the error assumptions for ARIMA, but as my professor said: “it’s pretty fragile if including insignificant variables are necessary to meet the assumptions.” The client’s revenue was also already being modelled with a MAPE of about .95. Keeping in mind the end goal though, the emphasis had to be placed on the KPIs, so this was really the only route.

If I were to start this project over, I’d definitely adopt a more open conversation with my professor about what direction to go in, and use office hours as much as I could. Analysis wise, I hope to learn better ways to do this, preferably with automation.

IThe only feedback I got from my partner was to be more confident in myself. They also mentioned I was “friendly and approachable in and out of class”.
