FROM mcr.microsoft.com/dotnet/core/aspnet:2.2 AS runtime

COPY /bin/Release/netcoreapp2.2/publish/ /app
COPY SwaggerDemo.NetCore.XML /app

ENV ASPNETCORE_URLS http://+:56884
ENTRYPOINT ["dotnet", "app/SwaggerDemo.NetCore.dll"]
