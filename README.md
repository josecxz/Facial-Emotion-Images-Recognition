# Facial Emotion Images Recognition

Brief implementation and notebook for facial emotion detection using image data and notebooks.

## Contents
- `Reference_Notebook_Facial_Emotion_Detection_Full_Code.ipynb` — main notebook with preprocessing, model training, and evaluation.
- `Facial_Emotion_Detection_Collab.ipynb` — collaborative notebook copy.
- `Facial_emotion_images.zip` — local archive of images (NOT tracked in Git; kept locally).
- `.gitignore` — ignores image folders and common Python artifacts.

## Setup
1. Create and activate a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. Open the main notebook with Jupyter or VS Code and run cells.

## Data and Large Files
- Image folders (e.g. `Facial_emotion_images`) are intentionally ignored by Git and are not pushed.
- Large files (notebooks or archives >50MB) may trigger GitHub warnings — use Git LFS if you want to track them:

```bash
git lfs install
git lfs track "*.ipynb"
git lfs track "*.zip"
git add .gitattributes
```

To stop tracking already-committed large files (keeps files locally):

```bash
git rm --cached path/to/largefile
git commit -m "Remove large file from tracking"
git push origin main
```

## Notes
- The `.gitignore` contains rules to ignore `**/Facial_emotion_images/**` and common image extensions.
- If you want me to migrate large blobs out of history (reduce repo size), I can run `git filter-repo` or BFG — this rewrites history and affects collaborators.

## License & Attribution
Add a license file or attribution here as needed.

---
Generated on December 29, 2025.
