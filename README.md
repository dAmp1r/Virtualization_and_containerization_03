# Virtualization_and_containerization_03

Задание 1.

[docker hub](https://hub.docker.com/r/damp1r/custom-nginx)

Задание 2.

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/2.1.png)                    
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/2.2.png)                      
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/2.3.png)                              
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/2.4.png)                         

Задание 3.

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/3.1.png)                       
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/3.2.png)    

`нажав внутри контейнера CTRL+C мы завершили процесс и остановили контейнер`                

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/3.3.png)     

`nginx внутри контейнера прослушивает 81 порт`

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/3.4.png)                

Задание 4.

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/4.png)                    

Задание 5.

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/5.1.png)

`compose.yaml(предпочтительно) или compose.yml, который находится в рабочем каталоге, также поддерживает docker-compose.yaml и docker-compose.yml для обратной совместимости с более ранними версиями. Если существуют оба файла, предпочитает канонический compose.yaml.`

![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/5.2.png)             
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/5.3.png)                  
![](https://github.com/dAmp1r/Virtualization_and_containerization_03/blob/main/5.4.png)               

`Docker Compose обнаружил контейнеры, которые ранее были запущены в рамках проекта, но отсутствуют в текущей конфигурации. Это может случиться, если удалили или переименовали сервисы в файле docker-compose.yaml. Docker предлагает использовать флаг --remove-orphans для удаления этих контейнеров, чтобы избежать конфликтов и освободить ресурсы.`
