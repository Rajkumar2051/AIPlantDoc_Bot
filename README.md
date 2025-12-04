# PlantDocBot

AI Plant disease diagnosis via image upload and symptom chat.

## Structure
- `data/plantvillage`  (dataset - not included in repo)
- `data/plantdoc`      (dataset - not included in repo)
- `data/image_data.csv` (generated mapping)
- `AI_PlantDoc_Bot.ipynb` (notebook for Day 1 & Day 2)

## How to run
1. Open the notebook in Google Colab or Jupyter.
2. Run the Day 1 cell to create folders. Uncomment the `git clone` lines to download datasets in Colab.
3. Run the Day 1 scan cell to set `img_root`.
4. Run Day 2 to generate `image_data.csv` and display sample images.

## Notes
- **Do not commit large datasets** into the repo. Use `.gitignore` to exclude `data/`.
- Add a small `sample_images/` folder for demo images if you want to include examples.

