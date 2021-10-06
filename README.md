# ContosoPizza

```cmd
dotnet new webapi --no-https
dotnet build
dotnet watch run
dotnet run
```

```cmd
dotnet tool install -g Microsoft.dotnet-httprepl
httprepl http://localhost:5000
ls
cd Pizza
get
post -c "{"name":"Hawaii", "isGlutenFree":false}"
put 3 -c  "{"id": 3, "name":"Hawaiian", "isGlutenFree":false}"
get 3
delete 3
get
exit
```
