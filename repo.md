[< к содержанию](./readme.md)

## Перенос изменений в удаленный репозиторий

1. В открытом **Tерминале**  создаем с помощью команды `git init`  пустой ***Локальный репозиторий***

2. Вносим все наши изменения  в **Индекс**:

        $ git add 
    
![skrin](./assets/github.png)

3. Теперь фиксируем изменения в Индексес ключем -m и прописываем сообщение

        $ git commit -m "first commit"

![skrin](./assets/github1.png)

Получаем сообщение об успешном коммите 24 файлов

4. Теперь мы готовы перейти в последнему шагу - перенос в удаленный репозиторий на GitHub

- И сначала нам нужно показать адрес, куда нужно отправить все содержимое Индекса:

        $ git remote add origin https://github.com/Nataschannov/task-3.14.git

 - теперь готовы отправлять:

        $  git push -u origin main

![skrin](./assets/github2.png)  

Успешно зафиксировано

5. Проверяем удаленный репозиторий на GitHub

![skrin](./assets/github3.png)

Все наши файлы внесены

![skrin](./assets/github_result.png)

# ура !!!! :))))

