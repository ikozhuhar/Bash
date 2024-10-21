### Bash

#### <a name='toc'>Содержание</a>

1. [&&&&&&&&&](#initialization_system)
2. [&&&&&&&&&](#managing_services)
3. [&&&&&&&&&&]() 
4. [Дополнительные источники](#recommended_sources)


#### 1. [[⬆]](#toc) <a name=''>&&&&&&&&&&&&&&&&&&&</a>

**grep** - Слово «грепать» входит в топ самых популярных терминов, используемых разработчиками. Оно происходит от одноименной консольной утилиты grep (сокращение от `global regular expression print`). Эта утилита выполняет поиск определенного текста по файлу или файлам.

**sed** - это потоковый редактор текста (от stream editor), c помощью которого можно выполнять с файлами множество операций вроде поиска и замены, вставки или удаления. При этом чаще всего он используется именно для поиска и замены.

**awk** - это скриптовый язык, который полезен при работе в командной строке и широко применяется для обработки текста. При использовании awk вы можете выбирать данные – один или более отдельных фрагментов текста – на основе заданного критерия. Например, с помощью awk можно выполнять поиск конкретного слова или шаблона во фрагменте текста, а также выбирать определённую строку/столбец в файле.

##### Принцип работы

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

##### Конфигурационные файлы systemd
&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

| Путь | Описание |
| ------- | ----------- |
| `/etc/systemd/system` | юниты/модули, которые создаёт администратор системы. Обладают самым высоким приоритетом.|
| `/run/systemd/system` | юниты/модули, которые создаются в процессе работы системы. Приоритет этого каталога ниже, чем каталога /etc/systemd/system/, но выше, чем у /usr/lib/systemd/system |
| `/usr/lib/systemd/system` | юниты/модули сервисов, установленных с помощью менеджера пакетов. Самый простой пример — веб-серверы: Apache или Nginx. |



#### 4. [[⬆]](#toc) <a name='recommended_sources'>Дополнительные источники</a>

1. [Bash - Википедия](https://ru.wikipedia.org/wiki/Bash)
2. [????????????????](https://www.alexgur.ru/articles/2275/)
3. [????????????????](https://losst.pro/nastrojka-zagruzchika-grub)
4. Весь Linux Для тех, кто хочет стать профессионалом, стр.681
