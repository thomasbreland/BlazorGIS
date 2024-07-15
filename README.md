# BlazorGIS

To demonstrate .NET / Blazor Wasm / GIS in static deployment to GitHub Pages

## WIP

GIS
ServiceWorkers / Progressive Web Application (PWA) / Push Notifications

## Notes on deployment:

Must enable HTTPS for Blazor app.
Use files in project-level wwwroot folder for the project itself, i.e., BlazorGIS/BlazorGIS/wwwroot
Build file uses results from output of `dotnet publish -c Release -o publish`
