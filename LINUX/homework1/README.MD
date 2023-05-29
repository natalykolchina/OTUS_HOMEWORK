## название выполняемого задания
Обновить ядро в базовой системе

## текст задания
```
Выполните действия, описанные в методичке.
Полученный в ходе выполнения ДЗ Vagrantfile залейте в ваш git-репозиторий.
```

## описание команд и их вывод
```
packer build centos.json
vagrant box add centos8-kernel5 centos-8-kernel-5-x86_64-Minimal.box
vagrant box list
vagrant up
vagrant destroy
vagrant cloud publish --release kolchinanatalia/centos8-kernel6 1.0 virtualbox centos-8-kernel-5-x86_64-Minimal.box
```

## особенности проектирования и реализации решения

## заметки
