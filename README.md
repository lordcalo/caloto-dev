# Caloto.dev

Web estatica para publicar `caloto.dev` gratis en Cloudflare Pages.

## Rutas

- `/`
- `/partykit/`
- `/partykit/privacy/`
- `/partykit/terms/`
- `/spendflex/`
- `/spendflex/privacy/`

## Desarrollo local

Puedes abrir `index.html` directamente en el navegador o servir la carpeta con:

```bash
python3 -m http.server 8080
```

## Despliegue en Cloudflare Pages

1. Sube este repositorio a GitHub.
2. En Cloudflare, entra en **Workers & Pages**.
3. Crea una nueva aplicacion de **Pages** y conecta el repo.
4. Configura:
   - Framework preset: `None`
   - Build command: vacio
   - Build output directory: `/`
5. Despliega y usa el dominio `*.pages.dev` gratuito.

Despues puedes conectar el dominio propio `caloto.dev` desde Cloudflare.
