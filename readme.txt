this is a sample project for hosting asp.net core web application as windows service.
once the service is built, run following command to register it as a windows service:
sc create APIinWindowsService binPath="C:\Users\Administrator\source\repos\WebApplication8\bin\Debug\net5.0\WebApplication8.exe"
then open services console and start the service.
It will be available in: http://localhost:5050/WeatherForecast/
We can set the port to be taken from the config file.

Based on:  https://www.thecodebuzz.com/host-asp-net-core-api-as-windows-services/