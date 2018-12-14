# MVCWebAPI_ExchangeRate_Home_Assignment
created a MVC WebAPI application for getting exchange rate by given date period.

After the analysis of test assignment, created a new aplication using MVC5.
Step 1: Created a new parent model as Rateexchange with the properties like start_at and rates as dictionary and with the child model as CurrencyType with the properties of all currency type as double.
Step 2: Create a new controller called as RateExchangeController.
Step 3: Added a new view namely index.cshtml under Views/RateExchange
Step 4: In RateExchangeController, created ActionResult to return the view and JsonResult ExchangeRate.
Step 5: In index.cshtml, within document.ready / btnSubmit click call 
        $.ajax method to invoke url: '/RateExchange/ExchangeRate',with the parameters.
        
To run:
Please open the APICalldemo.sln in visual studio environment.
Step 1: You can provide the startdate and enddate in "yyyy-mm-dd" format eg:2018-01-15.
Step 2: Enter the currency type as SEK,NOK,INR,HUF etc in base and target currency fields.
Step 3: Click submit button.
Step 4: Results with Min, max and average value will display. Here, the date is not being shown.
