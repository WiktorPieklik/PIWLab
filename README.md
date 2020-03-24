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
![screenshot index.html](https://user-images.githubusercontent.com/50461146/77431383-e9be0a80-6ddc-11ea-9275-71ac89c6bc7b.png)

