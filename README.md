[![Validation of Console App](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml/badge.svg)](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml)


# To publish using msbuild #

```
msbuild .\gitactionstest_dotnet8.sln -t:clean,build,publish /p:Configuration=Release /p:PublishProfile=FolderPublish
```

