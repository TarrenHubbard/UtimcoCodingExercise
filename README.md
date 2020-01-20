# UtimcoCodingExercise
This is a repo for Utimco and their coding challenge
UtimcoJsonParser

Prerequisites:
This project is intended to run in .net core 3.0
Find your OS here https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md to make sure you are able to run this code.

If you need help installing .net core 3.0, check here for steps in insure you install correctly. 
https://docs.microsoft.com/en-us/dotnet/core/install/runtime?pivots=os-windows

Installing in dev:
If you wish to contribute to this code, make sure you have the correct SDK installed for .net core 3.0, https://docs.microsoft.com/en-us/dotnet/core/install/sdk?pivots=os-windows

Once this is done, you should be able to open this solution in visual studio, or whatever your ide of choice is. There are two solutions, one is the application istelf, the other is the test solution. Please make sure to add in unit tests for any changes you may make.

Deployment:
Please see here for the possible deployment options, https://docs.microsoft.com/en-us/dotnet/core/deploying/
This solution comes bundled with a folder profile to build a .exe. 
If this is not usable in your case,
If you wish to use the .net cli, https://docs.microsoft.com/en-us/dotnet/core/deploying/deploy-with-cli
If you wish to publish with Visual Studio, https://docs.microsoft.com/en-us/dotnet/core/deploying/deploy-with-vs?tabs=vs156

Running:
This code expects two command line arguments to be passed in, the first is a path to your json file and the second is a bool to turn on more robust logging. This is off by default, but if you encounter any issues executing this script, I would recommend turning this on to get the stack trace.

Built With .Net Core 3.0 https://dotnet.microsoft.com/download/dotnet-core/3.0
