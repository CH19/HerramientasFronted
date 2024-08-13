# Usar un web scraping con selenio
selenio es una biblioteca de python que nos ayuda hacer web scraping en páginas dinamicas con javascript
su documentacion esta en: https://selenium-python.readthedocs.io

## Confirmar que la pagina se usa selenium

Selenium debe ser el ultimo recurso al hacer web scraping, por su alto consumo de recurso y porque generalmente la liberria request es mas rápido, para confirmar que
la pagina que vamos a usar es necesario selenium podemos desactivar Javascript y ver si los datos carga, se recomienda la extensión [disable javascript](https://github.com/SergeyPirogov/webdriver_manager)

## pasos para usar selenio
- Tener chrome instalado
- instalar la dependencia [web driver manager](https://github.com/SergeyPirogov/webdriver_manager)
- Instalar la propia depedencia selenium
