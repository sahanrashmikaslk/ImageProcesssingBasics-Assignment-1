# EC7212 – Computer Vision and Image Processing  
## Assignment 1 (Take-Home)
### Reg. no: EG/2020/4047
### Name: Lelwala LGSR

This repository contains a complete Python solution (code + explanations) for the four tasks in Assignment 1:

| Task | Description |
|------|-------------|
| 1 | **Intensity-level reduction** – posterize an 8-bit image to any power-of-2 level count |
| 2 | **Spatial averaging filters** – apply 3×3, 10×10, 20×20 mean filters |
| 3 | **Image rotation** – rotate by 45 ° and 90 ° |
| 4 | **Block averaging / pixelation** – replace every non-overlapping 3×3, 5×5, 7×7 block with its mean |

### Folder layout

```

.
├── README.md
├── ImageProcessing_Assignment1.ipynb
├── images          ← input Sample image
└── results         ← output images

````

### Quick start

1. **Install libraries**

```bash
pip install numpy opencv-python matplotlib
````

2. **Run the notebook**

```bash
jupyter notebook ImageProcessing_Assignment1.ipynb
```

3. **Use your own image**
   Copy a file (e.g. `myphoto.jpg`) into `images/` and change the `img_path` line in the first code cell.


The script saves results into the `results/` folder and shows previews in pop-up windows.
