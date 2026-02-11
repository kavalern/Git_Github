**Команда `git config` керує налаштуваннями Git на рівні системи, користувача або даного репозиторія**

### **Команди**

```bash

# встановлення глобального користувача Git (для всіх проектів)
git config --global user.name "Carl"

# встановлення глобального email користувача Git (для всіх проектів)
git config --global user.email "Carl@gmail.com"

# ввімкненя кольорового виводу інформації (в деяких випадках за замовчуванням)
git config --global color.ui true

# виведення списку налаштувань
git config --list

# виведення імʼя користувача/email з налаштувань
git config user.name
git config user.email

# встановлення локальних параметрів Git (для конкретного репозиторію)
git config user.name "Mike"
git config user.email "Mike@gmail.com"
```
