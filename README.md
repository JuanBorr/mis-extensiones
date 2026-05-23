# Repo Personal Mihon

Este repo lista solo las fuentes que pediste y que aparecen actualmente como extensiones en Keiyoushi:

- NovelCool ES
- HentaiHand
- IMHentai
- DoujinsHell
- Ikigai Mangas
- ManhwaWeb
- Olympus Scanlation
- VCP/VMP
- Zonatmo.to

## Como usarlo

1. Copia los APKs indicados en `apks.txt` dentro de `apk/`.
2. Sube esta carpeta a GitHub, preferiblemente en una rama llamada `repo`.
3. En Mihon agrega la URL cruda del indice:

```text
https://raw.githubusercontent.com/JuanBorr/mis-extensiones/main/index.min.json
```

## Importante

`index.min.json` no crea extensiones por si solo. Mihon necesita que cada archivo APK exista en `apk/` con el mismo nombre declarado en el indice.

El fingerprint de `repo.json` es el de Keiyoushi porque estos APKs deben ser los APKs firmados por Keiyoushi. Si recompilas o firmas tus propios APKs, cambia ese fingerprint por el de tu llave.

TMOHentai no esta incluido porque no encontre una extension publicada con `https://tmohentai.app/`. Para agregarlo habria que crear una extension nueva en Kotlin y compilar su APK.
