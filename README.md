
       > git clone https://github.com/juniormorales/demoarqui.git
       > cd Cake-Shop/
    ```
    - Abrir el proyecto `CakeShop.sln`
    -  `Ctrl+Shift+B` 
    - Abrir `Administrador de paquetes de consola` desde `Herramientas` y escribir `update-database`.
    - Presionar `Ctrl+F5`

- **Using CLI**
    ```
        > git clone https://github.com/juniormorales/demoarqui.git
        > cd Cake-Shop/Cake-Shop/
        > npm install
        > dotnet restore
        > set ASPNETCORE_ENVIRONMENT=Development
        > set ConnectionStrings:DefaultConnection="<YOUR CONNECTION STRING>"
        > npm i webpack -g
        > webpack --config webpack.config.js
        > npm run build
        > dotnet build 
        > dotnet ef database update
        > dotnet run 
