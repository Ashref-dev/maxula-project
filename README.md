# maxula-project
Databse is on Neon pg, Blazor Server app is on Azure Cloud

## command to run tailwind:
npx tailwindcss -i wwwroot/app.css -o wwwroot/app.min.css --watch

## command to run blazor
dotnet watch run

### Random anecdotes

Blazor uses a specific model class for every for validation,
so if the login uses a different model wiht more unusezd fields, it'll not work unless all fields are filled with data.# Maxula-project
