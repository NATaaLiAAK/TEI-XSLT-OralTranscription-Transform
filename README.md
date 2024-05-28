# TEI-XSLT-OralTranscription-Transform
A project for transcribing oral discourse using TEI and transforming the transcriptions with XSLT.


## Some transcription errors made by Whisper (an automatic speech recognition (ASR) software) that I changed in the XML file :


```

<choice><orig>Désil</orig><reg>Désile</reg></choice>

<choice><orig>est un cotoyon</orig><reg>, euh… nous côtoyons</reg></choice>

<choice><orig>Aryas</orig><reg>ARIAS, hein…</reg></choice>

<choice><orig>ce travail nous intéresse</orig><reg>ces travaux nous intéressent</reg></choice>

<choice><orig>on a entendu</orig><reg>bien entendu,</reg></choice>

<choice><orig>collègue</origin><reg>colloque</reg></choice>

<choice><orig>tel</orig><reg>telle</reg></choice>

<choice><orig>désigné</orig><reg>désignée</reg></choice>

<choice><orig>tel</orig><reg>telle</reg></choice>

<choice><orig>vache</orig><reg>ouvrage</reg></choice>

<choice><orig>tour</orig><reg>ton</reg></choice>

<choice><orig>un remettre</orig><reg>à un</reg></choice>

<choice><orig>le songe</orig><reg>ils le songent</reg></choice>

<choice><orig>curil</orig><reg>puéril</reg></choice>

<choice><orig>à faire</orig><reg>affaire</reg></choice>

<choice><orig>quel que soit un cas</orig><reg>quelles que soient, en cas</reg></choice>

<choice><orig>leur arrivent</orig><reg>il leur arrive</reg></choice>

<choice><orig>d'</orig><reg>dans</reg></choice>

<choice><orig>meurs</orig><reg>mœurs</reg></choice>

<choice><orig>les dérotrement</orig><reg>le dire autrement</reg></choice>

<choice><orig>Il serait</orig><reg>Ils seraient</reg></choice>

<choice><orig>pour</orig><reg>au cours de</reg></choice>

<choice><orig>le</orig><reg>la</reg></choice>

<choice><orig>renhébérangé</orig><reg>Rede Béranger</reg></choice>

<choice><orig>bulle y-bondrille sous les tâmes</orig><reg>pudibonderie souhaitable</reg></choice>

<choice><orig>au lieu</orig><reg>aux jeux</reg></choice>

<choice><orig>traversées</orig><reg>traversée</reg></choice>

<choice><orig>dans</orig><reg>pendant</reg></choice>

<choice><orig>elle n'en considère</orig><reg>elles n'en considèrent</reg></choice>



```


## I could possibly make my .gitignore as this :


```


# General Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
*.egg-info/
.installed.cfg
*.egg
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*,cover
.hypothesis/

# Jupyter Notebook
.ipynb_checkpoints

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# Spyder project settings
.spyderproject
.spyproject

# Rope project settings
.ropeproject

# Visual Studio Code
.vscode/
*.code-workspace

# Ignorer les fichiers temporaires et de sauvegarde
*.tmp
*.bak
*.swp
*.swo
*~

# Ignorer les sorties de transformation (HTML, PDF, etc.)
/output/
/*.html
/*.pdf

# Ignorer les fichiers de configuration utilisateur
*.env
.env.local
.DS_Store
Thumbs.db


```

