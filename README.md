# Reporte de Reconfiguraciones CORFO

Este repositorio contiene el análisis de reconfiguraciones de proyectos CORFO / INNOVA, incluyendo:

- **Código** para procesar y visualizar datos (`.ipynb`, scripts de Python).
- **Datos**: `df_reporte.csv` (excluido del control de versiones).
- **Gráficos** generados: carpeta `img/` (excluida).
- **Prompts** utilizados para generar reportes en Jupyter: `prompts.txt`.
- **Archivos de configuración**: `environment.yml`, `pass.env` (excluidos).

## Estructura de carpetas

```text
📁 reporteria_reconfiguraciones
│
├─ 📁 maquetas/html  
│   ├ Folleto_Final.html  
│   └ Folleto_Final_ConGraficos.html
│
├─ 📁 img  (gráficos generados, ignorados)
│   ├ grafico_1.png
│   └ ...
│
├─ df_reporte.csv  (datos originales, ignorado)
├─ prompts.txt  (plantillas de consulta para generación de markdown)
├─ environment.yml
├─ pass.env  (credenciales, ignorado)
└─ reporte_reconfiguraciones.ipynb
```

## Uso

1. Crear entorno Conda:
   ```bash
   conda env create -f environment.yml
   conda activate tu_entorno
   ```
2. Abrir y ejecutar el notebook `reporte_reconfiguraciones.ipynb`.
3. Los prompts en `prompts.txt` son plantillas para generar los análisis en Markdown.


# Reporte de Reconfiguraciones CORFO

Este repositorio contiene el análisis de reconfiguraciones de proyectos CORFO / INNOVA, incluyendo:

- **Código** para procesar y visualizar datos (`.ipynb`, scripts de Python).
- **Datos**: `df_reporte.csv` (excluido del control de versiones).
- **Gráficos** generados: carpeta `img/` (excluida).
- **Prompts** utilizados para generar reportes en Jupyter: `prompts.txt`.
- **Archivos de configuración**: `environment.yml`, `pass.env` (excluidos).

## Estructura de carpetas

```text
📁 reporteria_reconfiguraciones
│
├─ 📁 maquetas/html  
│   ├ Folleto_Final.html  
│   └ Folleto_Final_ConGraficos.html
│
├─ 📁 img  (gráficos generados, ignorados)
│   ├ grafico_1.png
│   └ ...
│
├─ df_reporte.csv  (datos originales, ignorado)
├─ prompts.txt  (plantillas de consulta para generación de markdown)
├─ environment.yml
├─ pass.env  (credenciales, ignorado)
└─ reporte_reconfiguraciones.ipynb
```

## Uso

1. Crear entorno Conda:
   ```bash
   conda env create -f environment.yml
   conda activate tu_entorno
   ```
2. Abrir y ejecutar el notebook `reporte_reconfiguraciones.ipynb`.
3. Los prompts en `prompts.txt` son plantillas para generar los análisis en Markdown.

