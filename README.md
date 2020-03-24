# Projektowanie interfejsów webowych
## Wykorzystane technologie
- nginx 1.17.5
- bootstrap 4.0

## Uruchomienie serwera z obrazu
```zsh
docker build -f Docker/Dockerfile -t wpieklik-piw . && docker run -p 8080:80 wpieklik-piw
```

## Adres strony: `localhost:8080`
### Przykładowy zrzut ekranu
![page-screenshot index.html](https://user-images.githubusercontent.com/50461146/77427354-87620b80-6dd6-11ea-8405-243ea3e0d32e.png)

