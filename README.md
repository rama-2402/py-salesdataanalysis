# py-salesdataanalysis
Sales Data Analysis is a practice project performing Exploratory Data Analysis on some example sales data. This project is to learn and understand different data analytic techniques to gain insight from a raw sales data.

## Packages Used
This project uses the following python libraries for data analysis
* Numpy
* Pandas
* Matplotlib
## Clone the project
The packages used in the project are installed in a python virtual environment to avoid conflicts with existing packages. Follow the steps to clone and run the project in jupyter notebook
```
git clone https://github.com/rama-2402/py-salesdataanalysis.git
cd py-salesdataanalysis/
```
After navigating to the project directory, Create a virtual environment and install the packges using the following commands.
```
python3 -m venv venv/

#If you are using bash shell 
source venv/bin/activate 

#If you are using Fish shell
source venv/bin/activate.fish

#To install the necessary dependencies
pip install -r requirements.txt 

#To run the jupyter notebook 
jupyter notebook
```
## Troubleshooting
```
#Nuke the environment
rm -r venv/

#Install a new environment and dependencies
python3 -m venv venv/                 
pip install -r requirements.txt 
```

## Analysis
Following analysis has been made on the sales data
* Data cleaning
* Finding Months with highest sales 
* Finding Cities with highest sales 
* Finding a Hour of the day to show ADs to drive more sales
* Finding the product pairs that are most often bought together
* Finding products that are most sold during holodays


### INSIGHTS AND OBSERVATIONS

- Observation: The month of **December** has the highest sales recorded in the year 
    - Insight: This could indicate the customer behavior of **spending more during holidays** 
- Observation: The month of **Kanuary** has the lowest sales recorded in the year 
    - Insight: This could indicate the customer behavior of spending less or rather **depleted savings right after holidays**
- Observation: The city of **"San Francisco"** has the highest sales recorded in the year
- Observation: The store has recorded an average **"peak sales"** during the hours of **"11AM - 1PM"** and **"5PM - 7PM"** eeryday throughout the year. 
   - Insights: Running an a general or a targeted **Ad campaign** just hours before the peak sale hours could drive more sales to the stores. 
- Observation: **iPhone and Lightning cables** are the most often **purchased products in pairs.**
   - Insights: This gives us an insight on the customer behavior of purchasing tech products in pairs and having a **discounted sale on relevant products in pairs** could drive more sales to the store. 


#### CREDITS
The sales data for this exploratory analysis has been taken from the materials provided in [freecodecamp](https://youtu.be/GPVsHOlRBBI). The exploratory analysis was done in my point of view using different approach.
