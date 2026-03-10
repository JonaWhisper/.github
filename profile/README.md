# JonaWhisper

Open-source dictation app with local AI processing — speech-to-text, punctuation, grammar correction, and spell-check.

## Repositories

| Repo | Description |
|------|-------------|
| [jonawhisper](https://github.com/JonaWhisper/jonawhisper) | Main application (Tauri + Rust + Vue) |
| [jonawhisper-model-tools](https://github.com/JonaWhisper/jonawhisper-model-tools) | Model conversion & quantization pipelines |
| [jonawhisper-spellcheck-dicts](https://github.com/JonaWhisper/jonawhisper-spellcheck-dicts) | Spellcheck dictionaries (SymSpell freq + bigrams) |

## Models (HuggingFace)

| Model | Type | Languages |
|-------|------|-----------|
| [jonawhisper-gec-t5-small-onnx](https://huggingface.co/JonaWhisper/jonawhisper-gec-t5-small-onnx) | Grammar correction | Multilingual |
| [jonawhisper-t5-spell-fr-onnx](https://huggingface.co/JonaWhisper/jonawhisper-t5-spell-fr-onnx) | Spell correction | FR |
| [jonawhisper-flanec-base-onnx](https://huggingface.co/JonaWhisper/jonawhisper-flanec-base-onnx) | Grammar correction | EN |
| [jonawhisper-flanec-large-onnx](https://huggingface.co/JonaWhisper/jonawhisper-flanec-large-onnx) | Grammar correction | EN |

