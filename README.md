# InvalidOperationException Index.View
An unhandled exception occurred while processing the request. InvalidOperationException: The view 'Index' was not found. The following locations were searched: /Views/Home/Index.cshtml /Views/Shared/Index.cshtml

(EN-US)Solution for resolved this error when starting Web APP to first time. CASE in Visual Studio 2022 with .NET CORE 7
(PT-BR)Solução para resolver esse erro quando vamos iniciar o WEB APP pela primeira vez.
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/bb1838bd-9cda-4103-8ccc-80c44f8a072b)

(PT-BR) é necessario 2 Dependencias instaladas: 
Is Necessary 2 dependency installed:

(PT-BR) O primeiro pacote é Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation.
1- In Manage NuGet Packages, the first package is Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation.
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/1b59fd7e-49d1-4f04-8541-ea7edce9e740)

(PT-BR) O segundo pacote é Microsoft.VisualStudio.Web.CodeGeneration.Design
2- The second package is Microsoft.VisualStudio.Web.CodeGeneration.Design.
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/3d56641f-90af-45ee-8b77-937fa5472a79)

(PT-BR) Instalando ambos na sequencia vamos para o Program.CS e adicionar o seguinte codigo  ------- .AddRazorRuntimeCompilation() --------.
Installing both in the sequency go to program.CS and ADD the sequency CODE ------- .AddRazorRuntimeCompilation() --------.

(PT-BR) Antes de adicionar o codigo:
Before:
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/c8637b25-6a27-4f3b-9a27-a28be2ea0661)

(PT-BR) Depois de adicionar o codigo:
After:
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/2ab4d180-e388-415a-8a4a-6df68e4f909e)


Good work, the problem resolved for now. 
![image](https://github.com/Matbmuniz/InvalidOperationException_Index.View/assets/55324902/1fdf00fb-a9db-4a50-ba28-6c96ea05298f)


