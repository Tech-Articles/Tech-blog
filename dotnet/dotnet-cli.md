
### Create solution file
`dotnet new sln --name demo-project`
`dotnet new sln -n demo`

 **Create Project**

 CLI Command| Project type |
---------|----------|---------
 
`dotnet new webapi -o demo.lib`
 `dotnet new mvc -o demo.mvc`
`dotnet new grpc -o demo.grpc`
 `dotnet new classlib -o demo.library` 
 `dotnet new mstest -o demo.test`

**Add Project to Solution file**
> `dotnet sln add  demo.webapi\demo.webapi.csproj`

**Run code**
> `dotnet run `

**Add Project Reference**
> `dotnet add demo.mvc.csproj reference demo.lib/demo.lib.csproj`