# Steps

`dotnet build /p:ContinuousIntegrationBuild=true -c Release`

`dotnet pack --no-restore -o ./temp --no-build -c Release`

Open `/temp/MyRazorClassLibrary.1.0.0.nupkg` in NuGet Package Explorer
