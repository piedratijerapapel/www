# Sitio web de Piedra Tijera Papel

## Desarrollo

**Descargar este repositorio**  
`git clone https://github.com/piedratijerapapel/www.git`

**Crear archivo de configuración de Automad CMS** en: /shared/data.txt

```txt
sitename: Piedra Tijera Papel
-
theme: ptp/papel
-
textTeaser: una mirada a la historia del diseño gráfico en Colombia.
-
appleTouchIcon: /shared/apple-touch-icon.png
-
favicon: /shared/favicon.ico
-
flickr_api_key: YOUR FLICKR API KEY
-
flickr_user_id: YOUR FLICKR USER ID
-
flickr_api_secret: YOUR FLICKR API SECRET
-
oauth_token: YOUR FLICKR OAUTH TOKEN
-
oauth_secret: YOUR FLICKR OAUTH SECRET
-
urlSearchResults: /
-
sitesubtitle: Una historia del diseño gráfico en Colombia

```

**Iniciar servidor local**  
`php -S localhost:3000`

También se puede iniciar vía NPM o Yarn  
`yarn run start`
