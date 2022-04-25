# Module-6-Challenge - Housing Rental Analysis for San Francisco
This program analyzes the San Francisco housing market for investment in Rentals.

The Starter Code was provided along with the relevant San Francisco housing data from 2010-2016 along with the Geographical coordinates for the neighborhoods in San Francisco.

---

## User Story
A proptech company wants to offer an instant, one-click service for people to buy properties and then rent them. The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.  

Your job is to use your data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

---

## Acceptance Criteria  
The application must meet the following acceptance criteria:  

* Calculate and plot the housing units per year.

* Calculate and plot the average prices per square foot and the gross rents.

* Compare the average prices by neighborhood using interactive visualization.

* Build an interactive neighborhood map.

* Compose your data story

---

## The Application  

The application follows these stages: 
    
* Calculate and plot the housing units per year
        - using hvplot  
* Calculate and plot the average prices per square foot and the gross rents.  
        - using hvplot plot both on the same plot  
* Compare the average prices by neighborhood using interactive visualization.  
        - using hvplot. 
        - create an interactive widget for neighborhood 
* Build an interactive neighborhood map.  
        - using hvplot and GeoViews  


---

## Technologies
The application is developed using:  
* Language: Python 3.7,   
* Packages/Libraries: Pandas, hvplot.pandas
* Development Environment: VS Code and Terminal, Anaconda 2.1.1 with conda 4.11.0, Jupyterlab 3.2.9  
* OS: Mac OS 12.1

---
## Installation Guide
Following are the instructions to install the application from its Github respository.  

### Clone the application code from Github as follows:
copy the URL link of the application from its Github repository      
open the Terminal window and clone as follows:  

    1. $cd to_your_preferred_directory_where_you want_to_store_this_application  
    
    2. $git clone URL_link_that_was_copied_in_step_1_above   
    
    3.  $ls     
        Module-6-Challenge    
        
    4. $ cd Module-6-Challenge     

At this point you will have the the entire application files in the current directory as follows:

    * README.md                   (this file that you are reading)
    * Resources                   (Folder where San Francisco data resides)
        - housing_per_year.csv
        - neghborhoods_coordinates.csv
        - sfo_neighborhoods_census_data.csv
    * san_francisco_housing.ipynb      (the application jupter lab notebook)
    * Images                           (images folder - came with starter code)

---

## Usage
The following details the instructions on how to run the application.  

### Setup the environment to run the application
Setup the environment using conda as follows:

    5. $conda create dev -python=3.7 anaconda  
    
    6. $conda activate dev  
    
    7. $jupyter lab  

---

### Run the Application
THIS ASSUMES FAMILIARITY WITH JUPYTER LAB. If not, then [click here for information on Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/).  

After step 7 above, this will take you to the jupyter lab window, where you can open the application notebook **risk_return_analysis.ipynb** and run the application.  

**NOTE**:
>Your $ prompt will look something like __(dev) ashokpandey@Ashoks-MBP loan_qualifier_app$__ ,  with:  
    - '(dev)' indicating the activated 'dev' environment,   
    - ' ashokpandey@Ashoks-MBP ' will be different for you as per your environment, and   
    - 'loan_qualifier_app' directory is where app.py is located.  
    - '$' sign is the dollar prompt  

---

## Contributors
Ashok Pandey - ashok.pragati@gmail.com   
www.linkedin.com/in/ashok-pandey-a7201237

---

## License
The source code is the property of the developer. The users can copy and use the code freely but the developer is not responsible for any liability arising out of the code and its derivatives.

---