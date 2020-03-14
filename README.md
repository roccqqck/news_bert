### use my conda environment(linux). Download this link (Save link as)
https://github.com/roccqqck/news_bert/raw/master/bertenv.environment.yml
```
wget https://github.com/roccqqck/news_bert/raw/master/bertenv.environment.yml
conda env create -f bertenv.environment.yml
conda activate bertenv
```

### or my pip requirements python=3.7 cuda=10.0 cudnn=7.6.4
```
python3.7 -m venv ~/.local/venvs/bertenv
source ~/.local/venvs/bertenv/bin/activate
python3.7 -m pip install -r https://github.com/roccqqck/news_bert/raw/master/bertenv.requirements.txt
```