# Generating this fixture

1. Install .NET SDK (6.0.200)
1. `dotnet publish $(pwd)/../source-app --configuration Release --runtime ubuntu.18.04-x64 --self-contained false --output $(pwd)`
1. `rm ./react-app`

