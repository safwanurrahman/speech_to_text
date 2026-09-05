# Speech to Text Colab Notebooks

Simple Google Colab notebooks for converting audio speech into text.

## Notebooks

- `bangla2text_colab.ipynb` - Bangla speech to Bangla text using BanglaSpeech2Text.
- `english2text_colab.ipynb` - English speech to English text using Faster Whisper.

## How to Use

1. Open the notebook in Google Colab.
2. Run the install cell.
3. Upload your audio file when prompted.
4. Run the transcription cell.
5. Download the generated `.txt` file from the `output` folder.

## Notes

- Larger models give better accuracy but take more time.
- For Bangla, use `large` for the best result.
- For English, start with `medium`; use `large-v3` for better accuracy.
