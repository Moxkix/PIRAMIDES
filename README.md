# Observatorio Demografico Global

Plataforma web interactiva para explorar, comparar y analizar la estructura demografica de distintos paises a traves del tiempo. Incluye piramides de poblacion comparativas, series temporales de indicadores clave y fuentes de datos oficiales.

## Caracteristicas

- **Piramides de poblacion comparativas**: 6 paises (Japon, Niger, Espana, Alemania, India, Brasil) en 12 momentos temporales (1950-2050)
- **Eje porcentual sincronizado**: permite comparar paises de cualquier tamaño de poblacion
- **Series temporales**: Poblacion, Edad Mediana, Fecundidad, Esperanza de Vida, Crecimiento
- **Fuentes de datos**: 18+ fuentes primarias (UN WPP 2024, INE, UNFPA, Eurostat, ACNUR, etc.)

## Stack tecnologico

- React 18 + TypeScript
- Vite
- Tailwind CSS + shadcn/ui
- Recharts

## Instalacion

```bash
# Clonar el repositorio
git clone https://github.com/TU_USUARIO/observatorio-demografico.git
cd observatorio-demografico

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Compilar para produccion
npm run build
