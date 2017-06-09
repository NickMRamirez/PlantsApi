Publish:

```
cd PlantsApi.WebApi
dotnet publish -o bin/output -c Release -f netcoreapp1.1
```

Build and run:

```
cd ..
sudo docker-compose up --build -d
```

Just run (with two Web API containers):

```
sudo docker-compose up -d --scale webapi=2
```