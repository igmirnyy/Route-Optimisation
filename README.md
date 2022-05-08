# Route-Optimisation
### Локальная установка

```bash
# Копируйте репозиторий и введите папку
git clone https://github.com/GIScience/openrouteservice-examples.git
cd Route-Optimisation

# Install the requirements in a virtual env and activate it
python -m venv .venv
source .venv/bin/activate

pip install -r requirements
```

> Note: In case jupyter is already installed globally, and you want to use the local version, you can create a symlink to
> the local jupyter with:
>
>`ln -s .venv/bin/jupyter jupyter`
> 
> Then, run jupyter commands with `./jupyter` instead. 
> 
### Launch the Jupyter server on the python directory
jupyter notebook python/
