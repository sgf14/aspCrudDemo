purpose: dotnet/ asp MVC crud demo w/ sqlite db
source:  https://www.telerik.com/blogs/aspnet-core-basics-build-complete-crud-application-vs-code
https://medium.com/techiepedia/how-to-create-run-asp-net-core-mvc-project-with-without-entity-framework-in-visual-studio-code-b3569a38b368


to run app:
in terminal cd to todoApp folder and enter 'dotnet run'
it starts and gives you a port.  in browser use that:  http://localhost:[PORT]/Todo
do normal Cntl+C to stop server

db: sqlite local instance in this case.
got an error.  need to do cmd pallet nuget package gallery and pick entityframeworkCore.Tools (listed it in the error) since use of sqlite is deprecated
 https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Sqlite

C# SDK:
dotnet ver.  terminal = dotnet --version.  note had some trouble w/ initial downloaded ver 6, using ver 7 now and seems to work

note this nuget package gallery does most of the 'coding' for you.  trouble seems mainly with knowing which ones to choose.
  this was only an introductory example.

github branch change note