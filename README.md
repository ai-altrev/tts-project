# TTS Project

A comprehensive Text-to-Speech project supporting multiple TTS models and focused on processing documentation for audio generation.

## Project Structure

```
📁 tts-project/
  📁 config/           # Configuration files
  📁 data/            # Audio and transcription data
  📁 docs/            # Documentation files
  📁 models/          # TTS model files
  📁 outputs/         # Generated audio outputs
  📁 scripts/         # Processing and testing scripts
```

## Quick Start

1. Install dependencies:
```bash
conda env create -f environment.yml
# or
pip install -r requirements.txt
```

2. Prepare your environment:
- Place raw recordings in `data/raw_recordings/`
- Configure audio settings in `config/audio_config.py`
- Adjust training parameters in `config/training_config.py`

3. Run tests:
```bash
python scripts/test_system.py
```

## Project Status

See our [Project Log](https://github.com/ai-altrev/tts-project/issues/2) for current status and development history.

## Features

- Multiple TTS model support (Jenny, LJSpeech, Tortoise)
- Audio preprocessing pipeline
- Comprehensive testing framework
- Extensive documentation processing capabilities

## Documentation

The `docs/` directory contains detailed documentation about the project, including:
- Recording scripts
- Model specifications
- Processing pipelines
- HD Knowledge base (64 gate files)

## Contributing

Please read through our Project Log issue to understand the current state and focus areas before contributing.