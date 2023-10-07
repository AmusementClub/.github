# Welcome to 私立七森中ごらく部 / AmusementClub

## Programs
- [x265](https://github.com/AmusementClub/x265): a fork of x265 Yuuki mod with aMod and some custom features and performance optimizations.
- [VapourSynth-Classic](https://github.com/AmusementClub/vapoursynth-classic): our VapourSynth fork without random _incompatible_ API breaks; high performance & lower memory consumption. We also host [VS-C](https://AmusementClub.github.io/doc/) and [VS R54](https://AmusementClub.github.io/doc3/) VapourSynth docs.
- [Public Tool Pack](https://github.com/AmusementClub/tools): we periodically release public versions of internal tool pack used in production encoding. It includes curated list of plugins & scripts that work well together.


## VS Plugins
- [assrender](https://github.com/AmusementClub/assrender): a plugin that renders ASS/SSA subtitle using libass.
- [vs-boxblur](https://github.com/AmusementClub/vs-boxblur): AVX2-vectorized box filter.
- [vs-dfttest2](https://github.com/AmusementClub/vs-dfttest2): Accelerated DFTTest re-implemetation for VapourSynth, with CUDA, SIMD (CPU), and generic GCC vector (CPU) backends.
- [vs-fgrain-cuda](https://github.com/AmusementClub/vs-fgrain-cuda): [Realistic Film Grain Rendering](https://www.ipol.im/pub/art/2017/192/) for VapourSynth, accelerated with CUDA. For CPU-only plugin, see [EleonoreMizo's chickendream](https://github.com/EleonoreMizo/chickendream).
- [vs-mlrt](https://github.com/AmusementClub/vs-mlrt): efficient ML/AI Filter Runtimes for VapourSynth (with built-in support for waifu2x, DPIR, RealESRGANv2/v3, and Real-CUGAN).
- [vs-nlm-ispc](https://github.com/AmusementClub/vs-nlm-ispc): non-local means denoise filter, drop-in replacement of the venerable [KNLMeansCL](https://github.com/Khanattila/KNLMeansCL) for VapourSynth, but without the OpenCL dependency (CPU only).
- [vs-nlm-cuda](https://github.com/AmusementClub/vs-nlm-cuda): non-local means denoise filter, drop-in replacement of the venerable [KNLMeansCL](https://github.com/Khanattila/KNLMeansCL) for VapourSynth, but accelerated with CUDA (~10% faster with 1 stream, up to ~50% faster with multiple streams.)


We also host Windows binary releases for the following plugins:
- [vs-ComparePlane](https://github.com/AmusementClub/vs-ComparePlane): AVX optimized PSNR implementation.
- [VapourSynth-WNNM](https://github.com/AmusementClub/VapourSynth-WNNM): Weighted Nuclear Norm Minimization Denoiser for VapourSynth.
- [VapourSynth-ILS](https://github.com/AmusementClub/VapourSynth-ILS): CUDA implementation of Real-time Image Smoothing via Iterative Least Squares for VapourSynth (Experimental).


For plugin developers, we have:
- [vs-api3](https://github.com/AmusementClub/vs-api3): a solution for dual api3/api4 plugins.


We also have a large number of forked VS plugins, and those are mostly for internal uses/experiments, though you're welcome to use them. Some of the notable ones are listed below:
- [DCTFilter](https://github.com/AmusementClub/VapourSynth-DCTFilter): DCTFilter with arbitrary DCT block size and other enhancements.
- [FFT3DFilter](https://github.com/AmusementClub/VapourSynth-FFT3DFilter): significant speedups.
- [fmtconv](https://github.com/AmusementClub/fmtconv): with experimental custom kernel support.


## VS Scripts
- [vapoursynth-script](https://github.com/AmusementClub/vapoursynth-script): a collection of useful VS funcs (e.g. [lexpr](https://github.com/AkarinVS/vapoursynth-plugin#expr) based Rgtools).


## Random Stuff
- [ResampleHQ's resampling kernel virtualization](https://AmusementClub.github.io/ResampleHQ/), preserved from now defunct website.
- [OKEGui](https://github.com/AmusementClub/OKEGui): (Chinese only) fork of [OKEGui](https://github.com/vcb-s/OKEGui) (One-Key Encode GUI) batch BDRip encoding helper.
- [WenQuanYi Bitmap Song TTF](https://github.com/AmusementClub/WenQuanYi-Bitmap-Song-TTF): A vector .ttf version of WenQuanYi Bitmap Song font. It has over 27,842 characters in 5 sizes.

