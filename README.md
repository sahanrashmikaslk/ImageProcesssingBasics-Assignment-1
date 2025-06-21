# EC7212 – Computer Vision and Image Processing  
## Assignment 1 (Take-Home)

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
├── notebooks
│   └── ImageProcessing\_Assignment1.ipynb   ← main Jupyter Notebook
├── images          ← put any input images here
└── results         ← output images are written here automatically

````

### Quick start

1. **Install libraries**

```bash
pip install numpy opencv-python matplotlib
````

2. **Run the notebook**

```bash
jupyter notebook notebooks/ImageProcessing_Assignment1.ipynb
```

3. **Use your own image**
   Copy a file (e.g. `myphoto.jpg`) into `images/` and change the `img_path` line in the first code cell.

### Command-line script (optional)

If you prefer plain Python instead of Jupyter, a fully equivalent script is provided at
`notebooks/ImageProcessing_Assignment1.py`. Run:

```bash
python notebooks/ImageProcessing_Assignment1.py --image images/myphoto.jpg
```

The script saves results into the `results/` folder and shows previews in pop-up windows.

````

---

## 2. `notebooks/ImageProcessing_Assignment1.ipynb`

> **Tip:** GitHub renders notebooks automatically.  
> If you’re copying through the web editor, create a new file, paste the **entire JSON** below, and save with the `.ipynb` extension.  
> (You can also download this chat as raw text, extract the block, and save.)



### How to commit

1. **Create the folders** in your local repo (or GitHub “Add file → Create new file”).
2. Paste the contents shown above into the correct paths.
3. `git add . && git commit -m "Assignment 1 solution"`
4. Push to GitHub.

That’s it!
Open the notebook in GitHub to verify it renders; open locally to run.
Let me know if you need any tweaks or if the JSON paste is too big to handle.
