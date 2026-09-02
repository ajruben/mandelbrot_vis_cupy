In this repo I experimented with [CUDA kernels](https://modal.com/gpu-glossary/device-software/kernel) via [CuPy](https://cupy.dev/) and [Datashader](https://datashader.org/) for visualising the famous [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set).

With this approach we can quickly scan the 'zoomed out' mandelbrot, at the penalty of floating-Point precision, and therefore resolution when zooming in. Therefore not suitable for generating the deep-zoom output.

See https://www.rubenswarts.nl/projects/3

<img width="828" height="828" alt="afbeelding" src="https://github.com/user-attachments/assets/bac9e6d1-3590-4726-8957-07fc37b9afa6" />

<img width="1024" height="1024" alt="afbeelding" src="https://github.com/user-attachments/assets/8b12ce27-509d-4d78-8480-4148551f7433" />

<img width="1080" height="1080" alt="afbeelding" src="https://github.com/user-attachments/assets/dce0b712-e457-4126-950d-ff4cc3575829" />

A fun follow-up may be an interactive Mandelbrot set visualisation program.

You can do whatever you want with this code :)
