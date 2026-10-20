# Diagnóstico de Reels — 20-oct-2026

Fuente: `hpix/ig-reels-scraper`, 50 Reels por cuenta, capturado el 20-oct-2026.
Costo total de la captura: US$0,18. Outliers medidos contra la mediana de cada cuenta.

## 1. Benchmark de las 4 cuentas

| Cuenta | Seguidores | Mediana de vistas | % de seguidores | Cadencia | Duración mediana |
|---|---|---|---|---|---|
| @jorgeacondeoficial | 58.328 | **590** | 1,01 % | 0,18 Reels/día | 50 s |
| @sandlerdanmacias | 85.702 | 1.328 | 1,55 % | **2,50 Reels/día** | 49 s |
| @crece30x | 426.023 | 14.898 | **3,50 %** | 1,28 Reels/día | 47 s |
| @andresbilbao | 1.023.896 | 16.304 | 1,59 % | 0,19 Reels/día | 63 s |

@sandlerdanmacias es el comparable real: mismo nicho, 1,5× mis seguidores,
2,25× mi mediana de vistas y **14× mi cadencia**.

## 2. Hallazgo bloqueante: publicación duplicada

Se están publicando **copias del mismo Reel con 1–2 minutos de diferencia**.
La primera copia recibe distribución; las duplicadas quedan en 0–2 vistas.

| Fecha | Hora | Código | Vistas |
|---|---|---|---|
| 19-oct | 17:59 | Der2aasp6bz | 619 |
| 19-oct | 18:00 | Der2f4ipYwA | **1** |
| 19-oct | 18:01 | Der2ih2peRl | **1** |
| 16-oct | 23:23 | DekswzFOnU2 | 100 |
| 16-oct | 23:24 | Deks4r3uTBJ | **0** |
| 16-oct | 23:24 | Deks9VsOT-M | **2** |
| 16-sep | 23:56 | DdXhCgCuR4v | 568 |
| 16-sep | 23:58 | DdXhTCpOTcy | **140** |

5 de los últimos 50 Reels (10 % del output) son re-publicaciones.
El patrón arranca el 16-sep y se agrava en octubre.

### Caída de alcance en la misma ventana

| Ventana | n | Mediana de vistas |
|---|---|---|
| Hace más de 90 días | 3 | 13.705 |
| 31–90 días | 34 | 614 |
| **Últimos 30 días** | 13 | **86** |

El alcance cayó **7×** (614 → 86) en el periodo exacto en que empiezan las
publicaciones triples. Causa probable: detección de contenido duplicado de
Instagram penalizando la cuenta. Hipótesis a descartar antes de atribuirlo
al contenido.

## 3. Los comentarios son el motor que no estoy usando

- Mis 50 Reels: **152 comentarios en total** (3 por Reel).
- Un solo Reel de @crece30x: **44.379 comentarios** (2,78 M vistas, 30 s,
  CTA "Comenta cualquier palabra y te enviamos el podcast completo").
- Mi Reel de 148 K vistas tiene 32 comentarios.

El outlier de @crece30x (187× su propia mediana) y el de @andresbilbao
(282.929 vistas, 1.796 comentarios, 13-oct) usan el **mismo** CTA literal.
Mis últimos 13 Reels acumulan 17 comentarios y ningún CTA de palabra clave.

## 4. Duración: la evidencia se repite

Mediana de mis últimos 30 días: 56 s. Lo que pasó de ahí:

- 39 s → 522 vistas y **13 comentarios** (el más comentado del mes)
- 40 s → 235 vistas
- 56 s → 619 vistas
- 61 s → 153 vistas
- 70 s → 73 vistas
- 71 s → 100 vistas
- 77 s → 113 vistas

Los top 6 de @crece30x: 30, 25, 34, 69, 34 y 41 s. Techo operativo: 45 s.

## 5. Lo que sigue vigente del diagnóstico del 19-oct

- La mediana de 590 vistas (1,01 % de seguidores) se confirma sobre 50 Reels.
- El outlier de 148.548 vistas (251,8× la mediana) sigue siendo el techo.
- Mis mejores piezas recientes: "elegí perder ventas a propósito" (6.188 =
  10,5×, 46 s) y "el vendedor más caro es el fundador" (3.752 = 6,4×, 48 s).

## 6. Dato nuevo de perfil

El nombre visible de la cuenta ya es **"Jorge Conde | Sistemas de Ventas con IA"**,
no el que figuraba en el contexto. La bio cierra con "👇 Inicia aquí".
