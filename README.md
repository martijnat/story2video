# story2video

Simple script to turn a story in plaintext to a video by turning each
part (sentence/paragaph) into an image with a voiceoiver and combining
everything into one video. The script relies on flux for images and
chatterbox-tts for voice but they can be individually swapped out for
other models.

# examples


https://github.com/user-attachments/assets/7d6fc38b-3db8-4ef3-9bed-4fc660919f65


https://github.com/user-attachments/assets/fbb98c8e-2105-40a3-85b1-3c780bdec4e0




# requirements

```text
pip install diffusers chatterbox-tts transformers accelerate torchaudio ffmpeg-python bitsandbytes sentencepiece
```

# Usage

Simply open the script and edit the story variable, then run the script.
