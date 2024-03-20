<img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" /><img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white" />

# ASP.NET Core Web API / Swagger/OpenAPI

## Getting Started
### Prerequisites

Mac (Apple silicon)

```
git clone git@github.com:underground/webapi.git
cd webapi
```

### Installation

```
brew install dotnet
dotnet tool install Swashbuckle.AspNetCore.Cli
```

### Development

```
dotnet run
```

-> Visit `http://localhost:5028` in your browser.

### Build

```
dotnet build -c Release
```

>Generate openapi
>
>TODO:
>```
>dotnet swagger tofile --output openapi.json bin/Release/net8.0/webapi.dll v1
>```
>

