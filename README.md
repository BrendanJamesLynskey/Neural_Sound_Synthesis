# Neural Sound Synthesis

A twelve-part interactive series on the machine-learning techniques that generate sound — the human voice, music, and instruments. Deep technical detail, live in-browser demos, and the mathematics worked all the way through. Every sound is synthesised live via the Web Audio API; every diagram computes in real time.

### [Launch the hub](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis/)

Part of the [DSP & Music](https://github.com/BrendanJamesLynskey/DSP_and_Music) collection.

---

## The series

| # | Part | Pillar | Topics |
|---|------|--------|--------|
| 01 | [Foundations & the Landscape](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_01_Foundations_and_Landscape/) | Core | Representation domains, the generative-model taxonomy, the sample-rate problem, evaluation (MOS/FAD/CLAP) |
| 02 | [Autoregressive Waveform Models](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_02_Autoregressive_Waveform/) | Core | WaveNet, dilated causal convolutions, μ-law, SampleRNN, WaveRNN |
| 03 | [Neural Vocoders (GAN)](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_03_Neural_Vocoders_GAN/) | Voice | MelGAN, Parallel WaveGAN, HiFi-GAN, multi-period/multi-scale discriminators |
| 04 | [End-to-End TTS](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_04_End_to_End_TTS/) | Voice | Tacotron 1/2, FastSpeech 1/2, VITS (flow + VAE + adversarial) |
| 05 | [Neural Singing Voice](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_05_Neural_Singing_Voice/) | Voice | DiffSinger, NNSVS, voice conversion (so-vits-svc, RVC), pitch/vibrato control |
| 06 | [Differentiable DSP](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_06_Differentiable_DSP/) | Core | DDSP harmonic-plus-noise, multi-scale spectral loss, timbre transfer |
| 07 | [GAN Instrument Synthesis](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_07_GAN_Instrument_Synthesis/) | Core | WaveGAN, SpecGAN, GANSynth, instantaneous frequency, latent timbre morphing |
| 08 | [Diffusion & Flow Models](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_08_Diffusion_and_Flow/) | Core | DDPM/score-based, DiffWave, WaveGrad, noise schedules, guidance |
| 09 | [Neural Audio Codecs](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_09_Neural_Audio_Codecs/) | Music | SoundStream, EnCodec, DAC, residual vector quantization |
| 10 | [Language-Model Music Generation](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_10_LM_Music_Generation/) | Music | AudioLM, MusicLM, MusicGen, Jukebox, tokens over transformers |
| 11 | [Latent Diffusion: Text-to-Audio](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_11_Latent_Diffusion_Text_to_Audio/) | Music | AudioLDM, Stable Audio, Riffusion, CLAP conditioning |
| 12 | [Real-Time, Control & Frontiers](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_12_Realtime_Control_Frontiers/) | Core | RAVE, streaming, evaluation, watermarking & ethics |

All twelve parts are live — read in order or jump to any technique.

## Technology

Single-file HTML/CSS/JS · Web Audio API · HTML5 Canvas · KaTeX · Palatino + Lucida Console · No external dependencies · No build step
