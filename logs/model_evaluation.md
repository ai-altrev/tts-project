# TTS Model Evaluation

## Current Models

### 1. Jenny Model
Strengths:
- Larger file size suggests more detail
- Consistent quality across samples

Metrics:
- Short sample: 377.6KB
- Long sample: 1.0MB

### 2. LJSpeech (Tacotron2-DDC)
Strengths:
- Efficient file sizes
- Well-established baseline

Metrics:
- Short sample: 222.6KB
- Long sample: 532.2KB

### 3. Tortoise-v2
Strengths:
- Balanced performance
- Modern architecture

Metrics:
- Short sample: 237.1KB
- Long sample: 717.2KB

## Comparison Framework
- Using test_models.py for standardized testing
- Metrics being tracked:
  1. File size efficiency
  2. Processing speed
  3. Output quality (pending systematic evaluation)

## Next Steps
1. Implement systematic quality metrics
2. Complete comparative analysis
3. Document performance characteristics