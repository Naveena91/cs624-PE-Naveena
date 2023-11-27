INPUT:
  Created Bottom Tab Navigator and added Screens to the Cities App.Four tabs such as,Add City,Cities, AddCountry and Countries. When clicked on AddCountry tab we need to enter the "Country Name" and "Currency" in a designated input field. Countries screen will show the added Country Name and Curreny.

PROCESS:
   It takes the entered "Country Name" and "Currency" and processes this information. It may involve tasks like data validation (ensuring the inputs are in the correct format), checking for duplicates, etc. If the input is valid, the system adds this new country and its currency to the list of countries. The system retrieves the list of countries and currencies that have been added using the "AddCountry" tab. The reusable CenterMessage component displays a message "No saved Countries" centered within the display. Created the AddCountry component that will allow to add new countries to the countryies array. This component will contain a form with two text inputs: one to hold the country name and one to hold the currency. Countries.js displays a list of countries that have been added to the application.import the CenterMessage component. React Navigation has a way to control certain options around the navigation within a route

OUTPUT:
  Displays the Countries tab to show the added Countries list and their currency.Displays the entire list of countries and currencies added using AddCountry tab


