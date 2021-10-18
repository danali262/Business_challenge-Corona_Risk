# Business_challenge-Corona_Risk
A data-driven roadmap to assessing covid risk in every Dutch region : Through multiple linear regression, we provide travellers with an overview of risk areas by postcode 

**What it does**

This app runs on a model that predicts a risk level from "On track for containment" to "Tipping point" based on the data of a region. The user enters a postcode and the risk level and corona stats from the region are displayed. While the "risk level" is normally measured through the number of cases / population ratio, we thought there are many more factors to be considered. We propose training a model on all the stats concerning the pandemic in a specific region and assigning our own risk scale according to the current data.

**How we built it**

For this mock-up we generated our own dataset: this is a placeholder for the real data which would be eventually pulled from RIVM. We wanted something to prototype and test our idea quickly and create a solid proof of concept, and we also wanted to find out how we can generate (partially randomised) data, since this practice can have many speculative applications.

**Built with**

python
sklearn
streamlit

**How to run it**

Run the deployment.py code with streamlit.cli.

https://devpost.com/software/business-challenge-coronarisk
