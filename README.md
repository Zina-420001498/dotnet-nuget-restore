# dotnet-nuget-restore
Project check4Prime consumes a service 'Prime' from nuget package, previously generated by project 'dotnet-build-test-nuget-pack'.

To athenticate to GitHub package registry added PAT to the repo secrets.

To restore nuget packkage added the following to the check4prime.csproj:

  <ItemGroup>
    <PackageReference Include="PrimeService" Version="0.1.0" />
  </ItemGroup>
  
  
