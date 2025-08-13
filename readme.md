
  564  sudo apt update
  565  pwd
  566  ll
  567  cd Documents
  568  ll
  569  cd python
  570  ll
  571  mkdir PythonCursoEstInfeDataSciIA
  572  ll
  573  cd PythonCursoEstInfeDataSciIA
  574  ll
  575  conda env list
  576  conda create env CursoEstInfeDataSciIA
  577  conda create env --name CursoEstInfeDataSciIA
  578  conda create --name CursoEstInfeDataSciIA python numpy matplotlib pandas
  579  conda activate CursoEstInfeDataSciIA
  580  pip freeze > requirements.txt
  581  ll
  582  conda env export --from-history > environment.yml
  583  ll
  584  git init
  585  git branch -M main
  586  git add .
  587  git status
  588  git remote add origin git@github.com:CarlosCortes2020/PythonCursoEstInfeDatqaSciIA.git
  589  git remote .v
  590  git remote -v
  591  git status
  592  git push origin main
  593  git commit -am "First commit to connect repositories"
  594  git status
  595  git push origin main
  596  code .
