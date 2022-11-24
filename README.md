# estilos_programa

trello

https://trello.com/b/B4Q3b7LV/login-cspharma-front


layout

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>@ViewData["Title"] - arquitecturaPageRazor</title>
    <link rel="stylesheet" href="~/lib/bootstrap/dist/css/bootstrap.min.css" />
    <link rel="stylesheet" href="~/css/site.css" asp-append-version="true" />
    <link rel="stylesheet" href="~/arquitecturaPageRazor.styles.css" asp-append-version="true" />
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-sm navbar-toggleable-sm navbar-light bg-white border-bottom box-shadow mb-3">
            «<! ––«Aqui va la imagen del logo «––>«
            <img src="Pages\Images\cruz.jpg">
            «<! ––«Aqui esta el texto con el nombre de la empresa «––>«
            <h1 style="text-align: center">CSPharma</h1>
        </nav>
    </header>
    <div class="container">
        <main role="main" class="pb-3">
            @RenderBody()
        </main>
    </div>

    <footer class="border-top footer text-muted">
        <div class="container">
            &copy; 2022 - arquitecturaPageRazor - <a asp-area="" asp-page="/Privacy">Privacy</a>
        </div>
    </footer>
