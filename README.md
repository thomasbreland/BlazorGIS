# BlazorGIS

To demonstrate .NET / Blazor Wasm / GIS in static deployment to GitHub Pages

## WIP

GIS
ServiceWorkers / Progressive Web Application (PWA) / Push Notifications

## Notes on deployment:

Must enable HTTPS for Blazor app.
Use files in project-level publish folder for the project itself, i.e., BlazorGIS/BlazorGIS/publish
Use BlazorGIS/BlazorGIS/publish/wwwroot for GitHub Pages
Build file uses results from output of `dotnet publish -c Release --property:PublishDir=publish`
