# motor_constructivo-
motor_constructivo/
├── README.md                          ← guía completa
├── .gitignore
│
├── 00_fuentes/                        ← vacías, esperando PDFs
│   ├── indalum/  euroseries/  conalum/
│   ├── smart_frame/  herralum/  pens/
│   ├── saint_gobain/  cuprum/  comenza/  otros/
│
├── 10_extraido/                       ← salidas de extracción
│   ├── texto/  imagenes/  batches/  ocr/
│
├── 20_normalizado/
│   ├── catalogos.csv                  ← 55 filas precargadas
│   ├── productos.csv                  ← headers listos
│   ├── indalum/4000.json              ← plantilla
│   ├── euroseries/60.json             ← plantilla
│   ├── conalum/corrediza_3.json       ← plantilla
│   └── smart_frame/mc_450.json        ← plantilla
│
├── 30_assets/
│   ├── perfiles/  ensambles/  cavidades/
│   └── ilustraciones/  herrajes/  vidrios/
│
├── 40_sql/
│   └── 00_schema.sql                  ← schema completo con 10 tablas + vista
│
├── 50_scripts/
│   ├── pdf_to_text.py                 ← pdftotext
│   ├── pdf_to_images.py               ← pdftoppm
│   ├── ocr_batch.py                   ← tesseract
│   ├── build_db.py                    ← carga todo
│   ├── ingest_catalogo.py             ← carga un JSON
│   └── export_motor.py                ← exporta motor.json
│
├── 60_db/
│   └── motor_constructivo.db          ← con 55 catálogos + 18 series semilla
│
├── 70_salidas/
│   └── reportes/cobertura.md          ← resumen por fabricante
│
└── 90_backup/