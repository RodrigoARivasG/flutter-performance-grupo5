# Flutter Performance — Grupo 5

## Descripción

Proyecto de investigación desarrollado para la asignatura
Técnicas de Calidad de Software de la Universidad Tecnológica
de El Salvador (UTEC).

Su propósito es evaluar las métricas de rendimiento y la
optimización de animaciones complejas en Flutter, comparando
su comportamiento en dispositivos Android y entornos web.

## Objetivo

Evaluar el rendimiento de una aplicación desarrollada en Flutter
mediante diferentes escenarios de carga gráfica, identificando
el efecto de las estrategias de optimización implementadas.

## Tecnologías utilizadas

- Flutter
- Dart
- Flutter DevTools
- Chrome DevTools
- Android
- Google Chrome
- Visual Studio Code

## Escenarios de evaluación

- Transiciones de pantalla.
- Desplazamiento de listas extensas.
- Transformaciones y animaciones simultáneas.

## Estrategias de optimización

- V0: Versión original sin optimizaciones.
- V1: Reconstrucción localizada de widgets.
- V2: Construcción de listas mediante ListView.builder.
- V3: Reutilización de componentes mediante AnimatedBuilder.

## Métricas evaluadas

- Fotogramas por segundo (FPS).
- Tiempos de procesamiento UI y Raster.
- Cuadros fuera del presupuesto temporal (Jank).
- Consumo de memoria administrada, según la evidencia disponible.

## Metodología experimental

Se realizaron 24 pruebas distribuidas de la siguiente manera:

- 9 pruebas piloto en Android.
- 9 pruebas piloto en Web.
- 3 pruebas de optimización en Android.
- 3 pruebas de optimización en Web.

Cada prueba contó con 10 segundos de calentamiento y
30 segundos de medición.

Los resultados corresponden a un estudio exploratorio.

## Instalación

Clonar el repositorio y ejecutar:

```bash
flutter pub get
```

### Ejecución en Android

```bash
flutter run --profile
```

### Ejecución en Web

```bash
flutter run --profile -d chrome --web-port=8080
```

## Integrantes — Grupo 5

| Nombre | Carné |
|---|---|
| Argueta Ortiz Oscar Andrés | 25-0389-2022 |
| Ascencio Huezo Nidelson Ovidio | 25-1670-2022 |
| Cruz Ramírez David Salomón | 25-0616-2022 |
| Gómez Saravia Mauricio Enrique | 25-2061-2022 |
| Jiménez Ventura Georgina Lisseth | 25-3274-2022 |
| Rivas Guzmán Rodrigo Alonso | 25-0964-2022 |

## Asignatura

Técnicas De Calidad De Software.

## Docente

Ing. Noé Elías Rodríguez Merlos.

## Institución

Universidad Tecnológica de El Salvador.

Facultad de Ciencias Aplicadas — Escuela de Informática.

## Ciclo

02-2026

## Año

2026.

---

Proyecto desarrollado con fines académicos y de investigación.
