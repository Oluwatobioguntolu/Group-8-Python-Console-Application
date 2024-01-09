# Global Holiday Planner

**Overview:**

This project combines data analysis, user input processing, and real-time currency conversion to offer personalized travel recommendations by creating  a tool that helps users plan an international holiday based on various criteria, including population, country size, flag color preferences, and real-time exchange rates using data generated form two APIs  
The first API returns data about information(such as population, sq. m, flag colour etc) of selected countries. The second API generates the current exchange rate of the selected country in comparison to 1 USD.  
The 'Global Holiday Planner' empowers users to effortlessly plan their dream international getaway by seamlessly integrating real-time exchange rates. Users input their desired destination, gaining intriguing details about the country's population, size, and flag colors. As users enter their budget in USD, the project unfolds the magic by showcasing real-time exchange rates, allowing them to choose the perfect currency for a personalized international adventure.



## Features

1. **Holiday Information**: Retrieve detailed information about holidays for a selected country and date range.

2. **Country Details**: Get comprehensive details about a country, including population, capital, and official languages.

3. **Currency Exchange Rates**: Real-time currency conversion rates for effective travel planning.

   

## Getting Started

1. Clone the repository to your local machine.

  ```bash

  git clone: https://github.com/Oluwatobioguntolu/Group-8-Python-Console-Application.git

  ```

2. Install the required Python packages.

  ```bash
from pip._vendor import requests
from pprint import pprint as pp

  ```

3. Follow instructions in the code to set up API keys for holiday information, country details, and exchange rates.

4. Run the application.

  ```bash
Group-8-Python-Console-Application.py

  ```

## APIs Used

1. **Country Details API**: ['https://restcountries.com/v3.1/name/' + country + '?fullText=true']

2. **Exchange Rate API**: ['https://v6.exchangerate-api.com/v6/d6463bde9e2ea9ae97de9ad2/latest/USD']



## Usage

1. Choose a country and date range to fetch holiday information.

2. Explore country details to enhance your travel knowledge.

3. Check real-time currency exchange rates for accurate budgeting.




## Team members and Contributions

# Team Lead:

- Oluwatobi Oguntolu - Sourced the two API keys used, wrote the codes needed to generate data from the APIs

# Team Members:

 - Khadijat Agboola - Contributed to the code, scenario and repository

 - Temitope Olatidoye - Updated the README

 - Elizabeth Soetan  - Commenting on the code
   
 - Oumaima Nakrimi
   
 - Ifunanya Nicholas
   
 - Maureen Nwobodo

Feel free to reach out to the team lead or any team member for questions or clarifications. Happy holiday planning!
In this project, we are using two APIs to build a python application. The first API returns data about information of selected countries. The second API generates the current exchange rate of the s...

**Conclusion:**

In wrapping up the Global Holiday Planner project, we have not just crafted a travel tool but a shared adventure in coding. 
Our collective efforts have given rise to a project that seamlessly weaves together data analysis, user input, and real-time currency conversion.

This project is more than lines of code; it’s a testament to our teamwork, problem-solving skills, and the joy of bringing an idea to life. 
With each input prompt and currency conversion, we have painted a picture of a tool that can guide users through the intricacies of international travel.
