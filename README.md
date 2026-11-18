# Noise and Grain Under Upscaling: Gain Goes Down, Clumping Goes Up, and Denoising First Usually Loses

A linear upscale cuts white-noise amplitude to 0.66-0.89x and concentrates the rest into clumps 2.6x wider than the source pixels. Pre-denoise loses 12/12 at the noise these images carry. In 4:2:0 the 2x2 chroma box cuts chroma noise to 0.31x, stops working after interpolation, and tolerates a radius that costs luma 6.3 dB.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-noise-and-grain-upscaling/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
