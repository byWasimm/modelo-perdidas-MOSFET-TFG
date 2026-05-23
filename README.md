# Modelo analítico de pérdidas en MOSFETs

Trabajo Fin de Grado — Grado en Ingeniería Electrónica Industrial y Automática  
Universidad Rey Juan Carlos, curso 2025/26  
Autor: Wasim Lourighi El Mousaoui  
Tutora: Alba Rodríguez Lorente

## Descripción

Modelos analíticos en MATLAB para estimar las pérdidas totales en MOSFETs 
de potencia a partir de parámetros del datasheet, sin caracterización 
experimental previa. Cubre dos regímenes de conmutación:
- Hard switching (conmutación forzada)
- ZVS / iZVS / CCM (conmutación suave y zona intermedia)

## Archivos

| Archivo | Descripción |
|---|---|
| `hard_switching_loss_model.mlx` | Modelo de pérdidas en hard switching con iteración electrotérmica |
| `ZVS_loss_model.mlx` | Modelo ZVS/iZVS/CCM con clasificación automática de régimen |
| `Calculo_DC_Phase_ZVS.xlsx` | Hoja de cálculo para dimensionado de dead time óptimo |

## Uso

Rellenar las Secciones 1 y 2 de cada script con los parámetros del 
datasheet del MOSFET y las condiciones del convertidor. 
Ver instrucciones detalladas en los comentarios del código.

## Referencias

Modelos basados en: AN1002 (MCC Semiconductors), Prado et al. (2022), 
Kasper et al. (2016), Miftakhutdinov (2014), Christen & Biela (2019).
