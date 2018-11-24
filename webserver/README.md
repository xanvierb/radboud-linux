# 8. Webserver opzetten

Dit is alweer de laatste opdracht in deze reeks. Deze opdracht is wat meer uitzoek werk. Je gaat een webserver installeren en hier wat HTML in zetten.

- installeer de NGINX webserver
- Er staat nu een standaard website op http://localhost/ (alleen bereikbaar op je VM)
- Zoek het bestand op dat geserveerd wordt en zet hier onderstaande code in (pas aan waar je wilt)

```html
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HTML geserveerd door NGINX</title>
</head>
<body>
    <h1>Het is gelukt!</h1>
    <p>Het is gelukt om dit te hosten onder NGINX, gefeliciteerd!</p>
    <img src="https://media.giphy.com/media/IB9foBA4PVkKA/giphy.gif" />
</body>
</html>

```