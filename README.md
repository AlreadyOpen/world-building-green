# world-building-green

The World Bank's [Building Green](https://www.worldbank.org/en/building-green) dataset (building energy codes, requirements
and enforcement in 88 economies) as JSON for maps, every field kept, plus the original workbook, published monthly to
Hugging Face ([dataset](https://huggingface.co/datasets/alreadyopen/world-building-green),
[bucket](https://huggingface.co/buckets/alreadyopen/world-building-green)) and mirrored to
[Kaggle](https://www.kaggle.com/datasets/helenkwok/world-building-green). Built from
[pipeline-template](https://github.com/AlreadyOpen/pipeline-template).

**Terms:** noncommercial reuse with full attribution only, as the World Bank allows in its report's Rights and Permissions.
Not an open licence; this repo's Apache-2.0 covers the code only.

    python3 bake.py      # data/out/building-green.json + .xlsx + index.json
    python3 publish.py   # gate, then Hugging Face (HF_TOKEN)
