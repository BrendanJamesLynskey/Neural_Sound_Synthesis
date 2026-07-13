# Neural Sound Synthesis

A twelve-part interactive series on the machine-learning techniques that generate sound — the human voice, music, and instruments. Deep technical detail, live in-browser demos, and the mathematics worked all the way through. Every sound is synthesised live via the Web Audio API; every diagram computes in real time.

### [Launch the hub](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis/)

Part of the [DSP & Music](https://github.com/BrendanJamesLynskey/DSP_and_Music) collection.

---

## The series

| # | Part | Pillar | Topics |
|---|------|--------|--------|
| 01 | [Foundations & the Landscape](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_01_Foundations_and_Landscape/) | Core | Representation domains, the generative-model taxonomy, the sample-rate problem, evaluation (MOS/FAD/CLAP) |
| 02 | Autoregressive Waveform Models | Core | WaveNet, dilated causal convolutions, μ-law, SampleRNN, WaveRNN |
| 03 | Neural Vocoders (GAN) | Voice | MelGAN, Parallel WaveGAN, HiFi-GAN, multi-period/multi-scale discriminators |
| 04 | End-to-End TTS | Voice | Tacotron 1/2, FastSpeech 1/2, VITS (flow + VAE + adversarial) |
| 05 | Neural Singing Voice | Voice | DiffSinger, NNSVS, voice conversion (so-vits-svc, RVC), pitch/vibrato control |
| 06 | Differentiable DSP | Core | DDSP harmonic-plus-noise, multi-scale spectral loss, timbre transfer |
| 07 | GAN Instrument Synthesis | Core | WaveGAN, SpecGAN, GANSynth, instantaneous frequency, latent timbre morphing |
| 08 | Diffusion & Flow Models | Core | DDPM/score-based, DiffWave, WaveGrad, noise schedules, guidance |
| 09 | Neural Audio Codecs | Music | SoundStream, EnCodec, DAC, residual vector quantization |
| 10 | Language-Model Music Generation | Music | AudioLM, MusicLM, MusicGen, Jukebox, tokens over transformers |
| 11 | Latent Diffusion: Text-to-Audio | Music | AudioLDM, Stable Audio, Riffusion, CLAP conditioning |
| 12 | Real-Time, Control & Frontiers | Core | RAVE, streaming, evaluation, watermarking & ethics |

Part 01 is live; the remaining parts are linked from the hub as they ship.

## Technology

Single-file HTML/CSS/JS · Web Audio API · HTML5 Canvas · KaTeX · Palatino + Lucida Console · No external dependencies · No build step
