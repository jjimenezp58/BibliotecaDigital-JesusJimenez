# Biblioteca Digital API

API REST desarrollada con ASP.NET Core y .NET 10 para gestionar el catálogo de
libros y los préstamos de una biblioteca.

## Pruebas

El proyecto incluye pruebas unitarias, de integración y de extremo a extremo
(E2E). GitHub Actions las ejecuta automáticamente al enviar cambios, abrir o
actualizar un Pull Request hacia `main`, o iniciar el workflow manualmente.

## Análisis de calidad

El workflow de SonarQube Cloud analiza la calidad y la cobertura del código.
Espera el resultado del Quality Gate y guarda los informes TRX y de cobertura
como artefacto descargable durante 7 días.
