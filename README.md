# Route-Optimisation
### Локальная установка

```bash
# Копируйте репозиторий и введите папку
git clone https://github.com/igmirnyy/Route-Optimisation.git
cd Route-Optimisation

# Установите необходимые библиотеки в virtual env и активируйте ее
python -m venv .venv
source .venv/bin/activate

pip install -r requirements
```

> Замечание: В случае если jupyter уже установлен глобально, а вы хотите использовать локальную версию,
> создайте ссылку на локальный jupyter с помощью
>
>`ln -s .venv/bin/jupyter jupyter`
> 
> Затем запустите jupyter с помощью `./jupyter`. 
> 
### Запустите jupyter с директории python
jupyter notebook python/

### Если у вас установлен PyCharm
```bash
В главном меню выспользуйтесь опцией 'Get from VCS' и выберите git, вставив ссылку  https://github.com/igmirnyy/Route-Optimisation.git

В созданном проекте, перейдите в файл requirments.txt и нажмите на кнопку 'install requirements'

Затем в нижнем меню выберите 'Terminal' и введите jupyter notebook, чтобы запустить сервер jupyter
```
### Получение API ключа
Зарегестрироваться на сайте [OpenRouteService](https://openrouteservice.org/dev/#/login)
```bash
Перейти на вкладку Dashboard

Внизу страницы выбрать тип токена 'standard' и дать ему название

Выше в списке появиться токен с названием и api ключом
```
