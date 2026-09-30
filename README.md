# Límbico

Un asistente con memoria que vive en tu computadora.

Lo que hablas con él se guarda **en tu equipo**, cifrado con una contraseña tuya.
No hay servidor, no hay cuenta y no hay nadie del otro lado leyendo nada.

**Estado: beta.** Funciona y también se rompe. Se reparte por invitación mientras dure
esta etapa.

## Qué hace

- Recuerda lo que le cuentas y lo trae de vuelta cuando hace falta, sin que se lo pidas.
- Olvida lo que deja de importar, en vez de acumularlo todo.
- Sabe cuándo "no" sabe algo, y lo dice en lugar de inventárselo.
- Guarda tus fotos con lo que hay dentro de ellas, cifradas.

## Qué necesitas

- Windows 10 u 11, 64 bits.
- Una llave de API de Google, OpenAI o Anthropic — **la tuya**, así controlas el gasto.
- O un modelo local con [Ollama](https://ollama.com), no sale nada de tu
  computadora.

## Descarga

En [Releases](../../releases). Comprueba la huella SHA-256 que va publicada junto al
archivo:

```powershell
Get-FileHash .\Instalador_Limbico_v1.4.1.exe -Algorithm SHA256
```

**Windows va a avisarte al instalar.** El instalador todavía no está firmado; el
certificado va después. Por eso se publica la huella.

## Tu contraseña

No se guarda en ningún sitio. Si la pierdes, **tus recuerdos no se pueden recuperar,
tampoco por mí**. Apúntala donde guardas Contraseñas importantes.

---

Hecho por Alexios, en Monterrey.
```

### Texto de la Release `v1.4.1`

```markdown
Primera versión pública en beta.

**SHA-256**
`7974BA91011DBA2B25AEA1E4DB786D15E7A896477D99D9D3A79F1748A0960F6E`

**Requisitos:** Windows 10/11 de 64 bits, y una llave de API propia (Google, OpenAI o
Anthropic) o un modelo local con Ollama.

**Windows va a avisarte al abrirlo.** El instalador aún no está firmado. Comprueba la
huella de arriba con `Get-FileHash` y sabrás que el archivo es el que subí.

**Tu contraseña no se guarda en ningún lado.** Si la pierdes, los recuerdos no se
recuperan. Apúntala.

