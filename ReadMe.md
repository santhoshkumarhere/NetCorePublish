dotnet publish /p:Configuration=Release /p:EnvironmentName=QA

--LocalRun
$Env:ASPNETCORE_ENVIRONMENT = "QA"
dotnet run --no-launch-profile
