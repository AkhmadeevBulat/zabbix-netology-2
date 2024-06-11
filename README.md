# Домашнее задание к занятию «Система мониторинга Zabbix. Часть 2.»

---
## Ахмадеев Булат Наилевич

---

## Задание 1

### В первую очередь я запустил вторую машину для теста его производительности и установил на нем Zabbix-агент:
![alt text](images/zabbix-agent-na-vtoroi-machine.png)

### А также добавил его в Hosts:
![alt text](images/HOST-LINUX-TEST.png)

### В Zabbix сервере по пути "Configuration > Templates" создал новый шаблон "TestTemplateNetology":
![alt text](images/new-template.png)

### С следующими макросами для удобства:
![alt text](images/macroses.png)

### Добавил два item'а:
![alt text](images/CPU.png) 
![alt text](images/RAM.png)


### Проверил их работу:
![alt text](images/test-items.png)
![alt text](images/top.png)

---

## Задание 2 и 3

### Zabbix-агенты уже установлены на две машины (на машине из первого задания и на сервере Zabbix).
### Добавил две машины как новые хосты:

Ниже будут скриншоты привязки хостов и полученные метрики:
![alt text](images/new-hosts.png)
![alt text](images/test-default-items.png)
![alt text](images/test-custom-items.png)


---

## Задание 4

### Создал два дашборда:
![alt text](images/items-values.png)
![alt text](images/graph.png)

---
