# Dataset Information

## Raw Datasets

### 1.  OPUS-100 (English-Kannada)
- Source: Hugging Face (opus100)
- Samples: 10,000 sentence pairs
- File: data/raw/opus/opus100_en_kn_train.csv

### 2.  Samanantar (English-Kannada)
- Source: Hugging Face (ai4bharat/samanantar)
- Samples: 50,000 sentence pairs
- File: data/raw/samanantar/samanantar_en_kn. csv

## Processed Datasets

### Combined & Cleaned
- File: data/processed/combined_en_kn. csv
- Total: 58,965 clean sentence pairs

### Train/Val/Test Split
- Train: data/processed/train. csv (80%)
- Validation: data/processed/val. csv (10%)
- Test: data/processed/test.csv (10%)

## Preprocessing Steps
1. Text cleaning (whitespace, empty values)
2. Remove duplicates
3. Filter invalid pairs (no Kannada, same text, too long)
4. Split into train/val/test (80/10/10)
