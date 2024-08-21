# kuber1
## Задание 1
dashboard - вроде получилось, но ничего не отображается, пока не сильно понимаю почему.<img width="1325" alt="Снимок экрана 2024-08-21 в 18 15 58" src="https://github.com/user-attachments/assets/cd699f88-b36a-4708-8486-74b7d9a50d89">
## Задание 2
Получилось настроить kubectl, хоть это было и сложно. Процесс был таков:
```
#установил microk8s
#скачал и закинул bin в /usr/bin - потому что centos 9
microk8s.kubectl config && touch ~/.kube/config 
#Закинул туда всю портянку и все заработало

```
