## Meeting Planner GraphQl Service

Using .Net v6 C#, Data API Builder [![Azure DAP](https://img.shields.io/badge/nuget-0077B5?style=for-the-badge&logo=microsoft)](https://github.com/Azure/data-api-builder) 0.9.7, PostgresQL to store data and other [![NuGet](https://img.shields.io/badge/nuget-0077B5?style=for-the-badge&logo=nuget&logoColor=black)](https://www.nuget.org/) pkgs

------------
##### Run this project on your local machine
You need `dotnet CLI` check dotnet version `dotnet --version` or use `Visual Studio` instead


1: Clone with git.

```
git clone https://github.com/raulcv/dab-rest-graphql-api
```

2: Install azure dap dotnet pkg with dotnet CLI

```
dotnet tool install --global Microsoft.DataApiBuilder
```

3: Configure your database environment

Copy and Paste > Run sqldefinition.sql file in your postgresQL server.
Create a `.env` file and include a: `my-db-connection-string='with-your-connection-string'`

Finally RUN

 ```
 dab start
 ```

You did it!!!

#### Start Fetching the REST API or querying with GraphQl banana cake pop playgorund.

REST API
```
GET /api/Book/id/1000
```

GraphQl Api
```
{
  books(first: 5, orderBy: { title: DESC }) {
    items {
      id
      title
    }
  }
}
```



------------------------------------------------------------------------
<p align="center">
	With :heart: by <a href="https://www.raulcv.com" target="_blank">raulcv</a>
</p>

#
<h3 align="center">🤗 If you found helpful this repo, let me a star 🐣</h3>
<p align="center">
<a href="https://www.buymeacoffee.com/iraulcv" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
</p>