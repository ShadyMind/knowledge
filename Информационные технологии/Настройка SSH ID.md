
**#Генерация закрытого и открытого ключа в #unix системах: **

```bash
% ssh-keygen
```

----

**Настройка #SSH**

Файл #настройки лежит в `~/.ssh/config` по умолчанию.
Пример файла настройки:

```config
Host github.com
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa_weak.pub

Host *
	User jhondoe
	IdentityFile ~/.ssh/id_rsa_protected.pub
```

