# Multi-text NLLB-Seed
```
├── README.md
├── eng_Latn
├── multitext
│   ├── ace_Arab
│   ├── ...
│   └── vec_Latn
├── order_files
│   ├── ace_Arab-eng_Latn.order.txt
│   ├── ...
│   ├── eng_Latn-vec_Latn.order.txt
│   ├── reference_ace_Arab-eng_Latn.order.txt
│   ├── ...
│   └── reference_eng_Latn-vec_Latn.order.txt
└── re_ordered
    ├── ace_Arab-eng_Latn
    │   ├── ace_Arab
    │   └── eng_Latn
    ├── ...
    └── eng_Latn-vec_Latn
        ├── eng_Latn
        └── vec_Latn
```

Method:
- The reference eng_Latn was created by manually comparing all reference eng_Latn files and taking the cleanest consensus
- Lines from the new reference eng_Latn were matched to lines in each of the existing eng_Latn files to output 