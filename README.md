dataset/
├── README.md
├── LICENSE_DATASET.txt
├── SOURCES.md
├── .gitignore
├── manifests/
│   ├── datasets.jsonl
│   ├── samples_train.jsonl
│   ├── samples_dev.jsonl
│   └── samples_test.jsonl
├── schema/
│   ├── evidence.schema.json
│   ├── sample.schema.json
│   └── dataset.schema.json
├── raw/
│   ├── text/
│   ├── images/
│   ├── tables/
│   └── pdf/
├── processed/
│   ├── text_chunks/
│   ├── image_captions/
│   ├── table_linearized/
│   └── multimodal_pairs/
├── indexes/
│   ├── bm25/
│   ├── dense/
│   └── faiss/
└── cache/
    └── (ignored)
