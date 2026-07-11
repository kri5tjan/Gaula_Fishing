# Gaula Fiskestatus – live version

Replace the files in your GitHub Pages repository with all files and folders in this package.

The repository secret must be named exactly `NVE_API_KEY`.

After uploading, open **Actions → Update live fishing data → Run workflow**. The safe public data file will then update every 15 minutes. Weather loads directly from Open-Meteo. Catch data uses Elveguiden’s current undocumented website endpoint and includes a graceful fallback if it changes.
