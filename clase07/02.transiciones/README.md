# Instalando PNPM 
<https://pnpm.io/es/installation>
Nota: Ejecutar el comando como administrador
```sh
Invoke-WebRequest https://get.pnpm.io/install.ps1 -UseBasicParsing | Invoke-Expression
```
## Verificando que funcione PNPM
```sh
pnpm --version
```
## Crear un proyecto VITE
```sh
pnpm create vite ./ --template vanilla
```  
## Arrancar servidor de desarrollo
```sh
pnpm dev
```
## Instalando dependencias
```sh
pnpm add <nombre-dependencia>
```