# **LR6**

## Лабораторная работа №6
## Система контроля версий

**Цель лабораторной работы:**
изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы
1. Аккаунт GitHub уже был создан, ссылка: https://github.com/FugiOG.
2. Была сделана копия репозитория https://github.com/Kurtyanik/LR6/ в личное хранилище (fork).
    ![1.png](./assets/1.png)
    ![2.png](./assets/2.png)
3. Git уже был установлен.

    ```console
    git --version
    ```
   
    Версия git:
    ![3.png](./assets/3.png)
4. Был настроен клиент git *(было введено имя пользователя и email)*.
    ```console
    git config --global user.name "4118 Горожанкин А.А."
    git config --global user.email "rememberov.andrei@yandex.ru"
    ```
    ![4.png](./assets/4.png)
5. Личный удалённый репозиторий был склонирован на компьютер.
    ```console
    git clone https://github.com/FugiOG/LR6.git
    ```
    ![5.png](./assets/5.png)
6. Был добавлен новый файл в репозиторий через интерфейс GitHub, затем изменения были подтянуты в локальный репозиторий.
    ![6.png](./assets/6.png)
    ![7.png](./assets/7.png)
    ```console
    git branch
    git pull
    ```
    ![8.png](./assets/8.png)
7. Была получена история операций для каждой из веток.
    ```console
    git log
    ```
    ![9.png](./assets/9.png)
    ```console
    git checkout branch1
    git log
    ```
    ![10.png](./assets/10.png)
8. Были просмотрены последние изменения.
    ```console
    git status
    ```
    ![11.png](./assets/11.png)
9. Было выполнено слияние в ветку master с разрешением конфликтов при помощи графического интерфейса.
    ```console
    git branch
    git merge branch1
    ```
    ![12.png](./assets/12.png)
    ![13.png](./assets/13.png)
    ```console
    git status
    ```
    ![14.png](./assets/14.png)