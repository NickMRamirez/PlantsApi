FROM microsoft/dotnet:1.1.2-runtime
ENV ASPNETCORE_URLS=http://+:80
EXPOSE 80
WORKDIR /app
ADD bin/output /app
ENTRYPOINT ["dotnet", "PlantsApi.WebApi.dll"]