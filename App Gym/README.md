# Ironclad Gym

Aplicacion web estatica. La version actual conserva `index.html` como punto de entrada para poder abrirla directamente en el navegador.

## Estructura prevista

- `assets/images/`: logo y fotografias locales.
- `css/`: tokens, layout, componentes y responsive.
- `js/data/`: catalogos de ejercicios y calendario semanal.
- `js/state/`: estado de entrenamiento y persistencia local.
- `js/features/`: fecha, ejercicios, series y temporizador.
- `js/ui/`: renderizado de paneles y modales.
- `js/utils/`: formateadores y utilidades.

La migracion se puede hacer por bloques sin cambiar el contrato de las funciones globales usadas por los botones inline de la pagina.
