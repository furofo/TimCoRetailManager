# TimCoRetailManager

#Setup Instructions

1.  Clone this repository
2.  You may need to follow these steps if encountering error similar to this:
    Error:
    Could not find a part of the path 'C:\Users\furofo\Demos\TimCoRetailManager\TRMDataManager\roslyn\csc.exe'. why is this

    Solution:

        Updating the NuGet Package Source
            Ensure NuGet Package Source is Available:

            Open Visual Studio.
            Go to Tools > NuGet Package Manager > Package Manager Settings.
            In the settings window, navigate to Package Sources.
            Ensure that nuget.org is listed and enabled. If it is not listed, add it with the following details:
            Name: nuget.org
            Source: https://api.nuget.org/v3/index.json
            Install Microsoft.Net.Compilers Package:

            Open the Package Manager Console from Tools > NuGet Package Manager > Package Manager Console.
            Run the following command again:
            shell
            Copy code
            Install-Package Microsoft.Net.Compilers
