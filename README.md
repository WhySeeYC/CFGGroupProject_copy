# That Girl's Personal Finance App.
Last update: 2024-03-02

This project is a simple Flask app that provide features like savings, investing and budgeting. 
The app uses Alpha Vantage API to fetch current stock price for the investment feature; the savings feature currently uses native python code for calculation of fix bond interest return; the budgeting feature currently uses libraries such as numpy, pandas and regex to extract information from payslip and bank statement and resent data in graphical summary. 

For more details about the project, please see [Documentation](./Documentation%20-%20That%20Girl's%20Personal%20Finance%20App.pdf).

A video presentation for this project is available at [YouTube](https://youtu.be/NvrMJsGxq50?feature=shared). 


## File structure for this repo

- `static/` folder contains most importantly the `style.css` file for the aesthetics of the app. Other files include the test files. 
- `template/` folder contains html pages for the flask app, broken down by features as well as about as landing page, error as pages when response goes wrong.
- `app.py` construct the entire app
- `Budgeting.py` contains functions for budgeting feature
- `Savings.py` contains functions for savings feature
- `flask_investment.py` and `investment.py` contains functions for investment
- `sql-connector.py` suppose to spin up and use python to connect to a MySQL database but we have not manage to make this part work
- `unitest_savings.py` and `unittest_investment.py` are unit testing files to check the robustness of the flask app.
- `Presentation Graphics/` folder contains the material for assessment day. The snapshot of code were captured with [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode) extension in vs code. (Note that this is only in local machine because we want to keep the repo simply contains code)
 
 
## Contributors
Aisling, Jessika, Layla, Onyeoma, Sophie, YC
Many thanks to this group of amazing girls making this project come to life.
Many thanks to Aviva sponsoring our trainings.