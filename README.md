# Linux_Lesson_32
## OSPF

### Описание репозитория

Лабораторный стенд для тестирования динамической маршрутизации с использование протокола OSPF.
![img](https://github.com/darknetworm/Linux_Lesson_32/assets/82410807/d1377dac-a775-4f0f-83ff-38aef5076920)
**Vagrantfile** - создает три маршрутизатора на основе ubuntu/focal64. Настройка функциональности роутеров производится с помощью Ansible.
**hosts** - файл с настройками сетевых устройств для быстрого доступа к ним из playbook.
**main.yml** - основной файл Ansible playbook для установки и настройки сетевых устройств стенда.
Директория **/templates** содержит файлы для конфигурирования утилиты маршрутизации FRR.

Для проверки работоспособности ассиметричнго роутинга в файле main.yml необходимо раскоментировать соответствующий блок и в 
