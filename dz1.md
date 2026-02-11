# HW Security №1

1. 
# Результат команды tree ~/secure_project

![alt text](<Снимок экрана 2026-02-11 182239.png>)

2. 
# Копия содержимого файла evidence.log

Ввод

```bash
simka@Dmitry:~/secure_project$ cat evidence.log
```

Вывод

```bash
./secret_plan_v1.txt:The password is 12345
```

3. 
# Вывод history

```bash
 1  pwd
    2  il -la
    3  is -la
    4  ls -la
    5  mkdir -p secure_project
    6  cd secure_project
    7  mkdir -p docs
    8  mkdir -p src
    9  backup
   10  mkdir -p mkdir -p
   11  mkdir -p backup
   12  cd docs
   13  touch secret_plan.txt
   14  nano secret_plan.txt
   15  cd secure_project
   16  cd ~/secure_project
   17  cp docs/secret_plan.txt backup/secret_plan_v1.txt
   18  cd backup
   19  nano secret_plan_v1.txt
   20  grep -r "password" backup/
   21  grep -r "password"
   22  grep -r password . >> ~/secure_project/evidence.log
   23  cd ~/secure_project
   24  nano evidence.log
   25  sudo apt update && sudo apt install tree
   26  tree ~/secure_project
   27  tree ~/secure_project > report.txt
   28  tree ~/secure_project
   29  nano report.txt
   30  history
```