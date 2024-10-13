# BlazorGIS

*AdblockPlus might cause some issues on first render, just try refreshing or disabling AdblockPlus for this page.*

To demonstrate .NET / Blazor Wasm / Blazor JS Interop / GIS in static deployment to GitHub Pages

Most of my professional experience has been with ArcGIS, but for my portfolio I am experimenting with open-source alternatives. Here I am using OpenLayers.

Also uses Bootstrap, but that is just the default.

## WIP

Progressive Web Application (PWA) / ServiceWorkers / Push Notifications

## Notes on deployment

Must enable HTTPS for service worker / this Blazor app.

Use files in project-level publish folder for the project itself, i.e., BlazorGIS/BlazorGIS/publish

Uses BlazorGIS/BlazorGIS/publish/wwwroot for GitHub Pages

Build file uses results from output of `dotnet publish -c Release --property:PublishDir=publish`

## Datasets

GitHub Pages does not support Git LFS, and I am trying to keep it lightweight for PWA use anyway, so this has limited my options. I will keep searching. The project file is currently tracking an empty data folder.

## Notes to self

Remember to update service-worker-assets.js
