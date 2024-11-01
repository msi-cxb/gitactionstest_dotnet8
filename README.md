[![Validation of Console App](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml/badge.svg)](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml)


# To publish using msbuild #

```
msbuild .\gitactionstest_dotnet8.sln -t:clean /p:Configuration=Release
nuget restore .\gitactionstest_dotnet8.sln
msbuild .\gitactionstest_dotnet8.sln -t:build,publish /p:Configuration=Release
```

```
msbuild .\gitactionstest_dotnet8.sln -t:build,publish /p:Configuration=Release /p:PublishProfile=.\Properties\PublishProfiles\FolderProfile.pubxml
```

    <PublishSingleFile>true</PublishSingleFile>
    <PublishReadyToRun>false</PublishReadyToRun>
    <PublishTrimmed>false</PublishTrimmed>
