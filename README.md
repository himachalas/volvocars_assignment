Congestion Tax Calculator

Congestion Tax Calculator
Overview
The Congestion Tax Calculator is a .NET project that provides a simple implementation of a web API for calculating congestion tax based on specific criteria.

Project Structure
The project consists of the following components:

congestion-tax-calculator (Main Project)
This project contains the main implementation of the congestion tax calculator.

HttpController.cs: The HTTP controller responsible for handling requests and invoking the congestion tax calculation logic.

IVehicleTaxCalculator.cs: An interface defining the contract for vehicle tax calculation.

congestion-tax-calculator-tests (Test Project)
This project contains unit tests for the congestion tax calculator.

HttpControllerTests.cs: Unit tests for the HttpController class.

VehicleTaxCalculatorTest.cs: A mock implementation of the IVehicleTaxCalculator interface for testing purposes.

How to Run
Open the solution in Visual Studio or your preferred IDE.

Build the solution.

Run the unit tests in the congestion-tax-calculator-tests project to ensure the correctness of the calculator logic.

Start the application to test the API endpoints.

Testing
The unit tests in the congestion-tax-calculator-tests project cover various scenarios, including normal calculations, edge cases, and error handling.

Dependencies
Microsoft.AspNetCore.Mvc: The framework for building web APIs with ASP.NET Core.

Moq: A mocking library used for creating mock objects in unit tests.

Additional Notes
The project follows the Model-View-Controller (MVC) architectural pattern.

Error handling and validation are incorporated in the HttpController class to ensure the reliability of the API.

Feel free to extend and modify the project to meet specific requirements.
