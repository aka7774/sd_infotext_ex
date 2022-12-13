# sd_infotext_ex
Extend Infotext for PNG

## PNG Info

For Example:
```
masterpiece, best quality, navel
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name
Steps: 15, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2592017842, Size: 512x1024, Model hash: 1a7df6b8, Hypernet: anime_2, Eta: 0.67, Clip skip: 2, ENSD: 31337, Model sha256: 67a115286b56c086, VAE sha256: f921fb3f29891d2a, Hypernet sha256: 15dfc4e10f59ccb2, GPU: NVIDIA GeForce RTX 2070, Options: xformers
```

- sha256 is first 16 characters.
- Options: xformers medvram lowvram.

## Perfect reproduction

- Don't use "Euler a" Sampler
- Don't use above Options
- Don't use Batch size (!= 1)
- Don't use GTX16X0 or lower GPU
