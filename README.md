# «Базовые объекты K8S» - Дрибноход Давид

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

#### Ответ:

1. Соcтавил файл pod.yaml, указал имя pod hello-world и image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/7a54e254-750e-4645-9d05-0a95fd0dcf5c)

2. Запустил pod

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/85d3844a-9a4f-461c-bc27-de5ba12d3518)

3. пробросил порт и подключился

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/afc304ef-4b14-4109-937a-d8f240974118)

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/59ef6e6b-93ae-4bfa-9a61-a91de6f746ea)

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

#### Ответ:

1. Составил файл service.yaml Pod с именем netology-web и image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2, а также Service с именем netology-svc и подключил к netology-web

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/fcae09f5-4d6b-42e0-8feb-9de2761019bf)

2. Запустил pod и service

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/355341cd-9a27-421e-8251-e56f71de1922)

3. пробросил порт и подключился

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/36605b6c-b301-4dc0-a937-91031a0c1f48)

![image](https://github.com/DrDavidN/12-02-hw/assets/128225763/905f2e63-a0b6-45e2-b912-cf3c9ce53fa8)

------
