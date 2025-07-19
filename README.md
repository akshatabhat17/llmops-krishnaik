
mkdir <project_folder_name>

cd <project_folder_name>

code .

conda create -p venv python=3.12 -y
conda activate <path_of_env>

pip install -r requirements.txt

git init
git add .
git commit -m <git message>
git push
git clone https://github.com/sunnysavita10/document_portal.git

## Minimum Requirements for this Project
- LLM Model
- Embedding Model
- Vector Database - in memory, in disk, cloud based

## Setup.py
setup.py file helps in creating a package of the document-portal 
