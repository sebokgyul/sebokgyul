### FFmpeg - AArch64 NEON

- `llviddsp`: NEON left and gradient prediction for the HuffYUV, MagicYUV, UtVideo and Lagarith decoders, 2.0–9.5x faster than C ([commit](https://github.com/FFmpeg/FFmpeg/commit/ea4162f223e5068c13210a6cc7a84c7d84f2ba3a), [PR #25382](https://code.ffmpeg.org/FFmpeg/FFmpeg/pulls/25382))
- `sbrdsp`: rewrote `hf_gen`, whose old NEON version was slower than C; now 1.35–2.16x faster than C ([commit](https://github.com/FFmpeg/FFmpeg/commit/fa59c23a59a721efd0590ec5fe5028dd6493568b), [PR #25558](https://code.ffmpeg.org/FFmpeg/FFmpeg/pulls/25558))
- Fixed a buffer over-read in the UtVideo decoder ([commit](https://github.com/FFmpeg/FFmpeg/commit/7a55e7d4f3698bb72d26aba8f5a41559f8ee6612)) and two bugs in the llviddsp checkasm test ([1](https://github.com/FFmpeg/FFmpeg/commit/8e6a5f19880d0bc5f20bad315f042841e3b21a49), [2](https://github.com/FFmpeg/FFmpeg/commit/a77727882a20211c59e1029abaa70e5cfacb8ce4))

[All commits](https://github.com/FFmpeg/FFmpeg/commits/master/?author=sebokgyul)
