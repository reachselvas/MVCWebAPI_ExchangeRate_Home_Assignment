# MVCWebAPI_ExchangeRate_Home_Assignment
created a MVC WebAPI application for getting exchange rate by given date period.

After the analysis of test assignment, created a new aplication using MVC5.
Step 1: Created a new model with the properties like Startdate, Enddate, fromcurrency and tocurrency.
Step 2: Create a new controller called as RateExchangeController.
Step 3: Added a new view namely index.cshtml under Views/RateExchange
Step 4: In RateExchangeController, created ActionResult to return the view and JsonResult ExchangeRate.
Step 5: In index.cshtml, within document.ready call 
        $.ajax method to invoke url: '/RateExchange/ExchangeRate',with the parameters.
        
After running the aplication, the method has been called and faced an issue like "The remote server returned an error (405)
Method not allowed"

To run:
Please open the APICalldemo.sln in visual studio environment.
