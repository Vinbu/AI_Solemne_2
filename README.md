# AI_Solemne_2
Repository for AI Software for head and tail´s salmon detection.  
Software tested in a Portatile Computer with 16 GB RAM and Nvidia RTX 3050 GPU.  
### Requirements
- OS Linux (Code tested in WSL Ubuntu 24.04.1 LTS)
- Python equal to or greater than version 3.12
- pip
- A GPU with similar features to an RTX 3050.
### Dependencies
This project works with `pyproject.toml` to manage dependencies
1. **Create virtual environment** (recomended):
```bash
python -m venv yolov8-env
source yolov8-env/bin/activate      # Linux / macOS
```
2. Clone the repository
3. Install dependencies
```bash
pip install .
```
This will install dependencies listed in pyproyect.toml.  
4. Download Images and Labels 
To get access contact with this repository project administrator.
Next you will get access to the folder:  
https://drive.google.com/drive/folders/1fYlchR5h9JAGNJMpDIGHWBPnX7_6bIHl?usp=sharing  
Download the content and copy the folders "content" and "singular_images" in the project root where you have cloned the repository.  
5. Run code
In the repository root, open using jupyter lab or notebook the solemne_2_notebook.  
Then you only have to run the cells in descending order, you will notice that you will construct the YOLO folders structure and distribute randomly with a seed the images in content, but there are images also in singular_images folder, this are images that are selected because the particular position that comes the fishes, so we distribute them based on train, test and validations percentages, 75, 15 and 10 percent respectively.
