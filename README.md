# LR6
Лабораторная работа №6

## Локальная работа после клонирования репозитория
подтянул изменения из GitHub

![Локальная работа](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/1%D0%B9.png)

## История операций всех веток
![История операций](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/2%D0%B9.png)

## Промежуточные коммиты
![Промежуточные коммиты](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/3%D0%B9.png)

## Конфликт при слиянии веток
![Конфликт при слиянии](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/4%D0%B9.png)

## Решение конфликта
Игнорировал побочную ветку, и оставил только те изменения, которые прописаны в ветке master

![Решение конфликта](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/5%D0%B9.png)

## Удаление коммита
![Удаление коммита](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/6%D0%B9.png)

## Оформление отчета в процессе
![Оформление отчета](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/7%D0%B9.png)

## Красивая история операций
![Красивая история операций](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/8%D0%B9.png)

## Git push
Вначале текущую ветку (report), потом все ветки.

![Git push](https://github.com/NIKFIRE4/LR6/blob/2cc7828b5ebf5f5fa7a5e2584946b6f99b4d588b/img/9%D0%B9.png)

## Список использованных команд
```bash
git clone https://github.com/NIKFIRE4/LR6
cd LR6
git log --all
git diff b4a235d7b4d26b38e500f9b40d698dfe5ecc6a7b
git branch -d branch1
git commit -m ""
git add .
git diff HEAD
git branch report
git checkout report
git merge
git log --pretty=format:"%h + %cd + %an + %s"
git push --all
git push origin -d branch1
