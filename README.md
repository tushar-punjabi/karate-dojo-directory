# Kyokushin Chile — Directorio Nacional de Dojos

Directorio centralizado de dojos de Karate Kyokushin en Chile. Proyecto comunitario sin fines de lucro.

## 🚀 Deploy en Vercel (gratis, 2 minutos)

### Opción A — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### Opción B — Drag & Drop (sin cuenta de GitHub)
1. Ve a https://vercel.com/new
2. Arrastra la carpeta del proyecto
3. Haz clic en "Deploy"
4. Listo. Obtienes una URL pública tipo `kyokushin-chile.vercel.app`

### Opción C — GitHub + Vercel (recomendado para actualizar fácil)
1. Sube esta carpeta a un repo en GitHub
2. En vercel.com → "Import Project" → selecciona el repo
3. Cada vez que hagas `git push`, el sitio se actualiza automáticamente

## ✏️ Cómo agregar un dojo

Edita el array `DOJOS` en `index.html` (busca el comentario `DOJO DATA`):

```js
{
  name: "Nombre del Dojo",
  sensei: "Sensei Nombre Apellido X° Dan",
  city: "Ciudad",
  region: "Nombre de la Región",
  address: "Dirección completa",
  phone: "+56 9 XXXX XXXX",
  email: "contacto@dojo.cl",
  web: "https://www.dojo.cl",   // o "" si no tiene
  org: "IKO",                    // IKO | KWU | WKB | IFK | INDIE
  schedule: "Lunes, miércoles y viernes 19:00–21:00"
},
```

### Organizaciones disponibles
| Código | Organización |
|--------|-------------|
| `IKO`  | IKO Kyokushinkaikan / variantes |
| `KWU`  | Kyokushin World Union / FCHKC |
| `WKB`  | World Kyokushin Budokai Chile |
| `IFK`  | International Federation of Karate |
| `INDIE`| Independiente / sin afiliación |

## 🌐 Dominio personalizado (opcional, gratis)
En el dashboard de Vercel → Settings → Domains → agrega `kyokushinchile.cl` (necesitas comprar el dominio ~$15 USD/año en NIC.cl).

## OSU! 押忍
