# HelloWorld-Asp.Net-App
on your windows cmd prompt: 

### Create a .NET Core Project

dotnet new sln -o HelloWorldApp <br>
cd HelloWorldApp <br>
dotnet new mvc -n HelloWorldApp.Web <br>
dotnet sln HelloWorldApp.sln add HelloWorldApp.Web\HelloWorldApp.Web.csproj <br>
dotnet restore <br>
dotnet build --no-restore --configuration release <br>
dotnet publish --no-build --configuration release <br>

##### Publish To Azure Repos

Add .gitignore file as below to the root directory where git hidden folder is present <br>
git init <br>
git add . <br>
git commit -m "Add build tasks" <br>
