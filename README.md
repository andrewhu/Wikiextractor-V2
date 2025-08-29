# WikiExtractor V2

fixes some bugs

Original: https://github.com/langtech-bsc/Wikiextractor-V2

* Download dump from https://dumps.wikimedia.org

Usage
```bash
python Wikiextractor-V2/wikiextractor/WikiExtractor.py \
        enwiki-20250801-pages-articles-multistream.xml.bz2 \
        --json \
        --templates templates \
        --output extracted \
        --bytes 10M \
        --markdown --discard_sections \
        --discard_templates \
        --ignore_templates
```
