# Datos — Air Quality (UCI)

El archivo de datos **no se versiona** en este repositorio. Descárgalo y colócalo en esta
carpeta (`air_quality/data/`) con el nombre `AirQualityUCI.csv`.

## Descarga

```bash
curl -L -o AirQualityUCI.zip "https://archive.ics.uci.edu/ml/machine-learning-databases/00360/AirQualityUCI.zip"
unzip AirQualityUCI.zip
```

O descárgalo manualmente desde:
https://archive.ics.uci.edu/dataset/360/air+quality

## Notas sobre el formato

- Separador de columnas: `;`
- Decimales con coma: `,`
- Fechas: `DD/MM/YYYY` y hora `HH.MM.SS`
- **Valores faltantes codificados como `-200`**
- Las dos últimas columnas del CSV están vacías.
