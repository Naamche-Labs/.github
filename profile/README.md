<div align="center">

# Naamche Labs

### Open AI for the 32 million people who speak Nepali.

[**naamchelabs.com**](https://naamchelabs.com) &nbsp;·&nbsp; [Models](https://naamchelabs.com/models) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/Aarjan) &nbsp;·&nbsp; [Research](https://naamchelabs.com/research)

</div>

---

Most speech and language AI is built for English first and measured on clean, read-aloud audio. Nepali on a real phone call, Nepali mixed with English, a Nepali voice that sounds like someone from Nepal: almost nothing open handled these well. We build models that do, from Kathmandu, and we release the weights, the benchmarks and the code with every one.

## Models

| | What it does | Result | Links |
|---|---|---|---|
| 🗣️ **Swar** स्वर | Nepali voice cloning: 20 to 30 seconds of a voice, then it speaks Nepali, English and the mix | Lowest pronunciation error on NepTTS-Bench: **2.92%** (OmniVoice 4.32%, ElevenLabs v3 12.91%). #1 on the Nepali voice-cloning benchmark | [Code](https://github.com/Naamche-Labs/swar) · [Weights](https://huggingface.co/Aarjan/swar) · [Page](https://naamchelabs.com/models/swar) |
| 📞 **Kriti Telephony v2** | Nepali speech-to-text for real phone calls: call-centers, IVR, code-switched speech | **#1 on NepTel 0.2**, real Nepali phone calls: **32.49** WER. FLEURS Nepali 24.77. 40x real time on one CPU thread | [Code](https://github.com/Naamche-Labs/kriti-telephony) · [Weights](https://huggingface.co/Aarjan/kriti-telephony) · [Page](https://naamchelabs.com/models/kriti-telephony) |
| 🎙️ **Kriti** | General Nepali speech-to-text, 119M parameters | Shares **rank #1 of 19** evaluated systems at **24.08%** WER | [Code](https://github.com/Naamche-Labs/kriti) · [Weights](https://huggingface.co/harrrshall/kriti) · [Page](https://naamchelabs.com/models/kriti-v1) |

## Benchmarks

- **[Nepali voice-cloning benchmark](https://github.com/Naamche-Labs/nepali-voice-cloning-bench):** zero-shot Nepali voice cloning on FLEURS, with data, scorer and leaderboard.
- **[Kriti reproducibility](https://github.com/Naamche-Labs/kriti-reproducibility):** verifiable evidence and replay for every Kriti number.

## How we work

- **Open by default.** Weights, training recipes and per-sample outputs ship with every release, so anyone can re-score our numbers.
- **Honest numbers.** We report confidence intervals, the decoding settings behind each score, and what did not work.
- **Real conditions.** Phone lines, noise and Nepali mixed with English, not only clean studio audio.
- **Consent first.** Only clone a voice with that person's permission.

---

<div align="center">

[**naamchelabs.com**](https://naamchelabs.com) &nbsp;·&nbsp; Kathmandu, Nepal &nbsp;·&nbsp; [hello@naamchelabs.com](mailto:hello@naamchelabs.com)

</div>
