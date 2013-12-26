# PHP Web-development

### 02. Работа със сесии и файлове - описание

**Да се създаде система за качване на файлове от уеб-страница. Домашната трябва да съдържа следната минимална функционалност:**

* Системата да е достъпна само след вход чрез формата за вход.
* Потребителя да може да качва произволни файлове.
* Да има екран, в който се показват всичките му файлове.
* Системата трябва да работи със сесии.
* Всички файлове трябва да се записват в една папка, която е видима от web server.
* Името и паролата на валидния потребител са записани в текстов файл или в PHP променлива. С цел улесняване на тестването, нека името да е **_user_**, а паролата **_qwerty_**.

**Описание на страницата "index.php":**
* В тази страница трябва да има форма за въвеждане на име и парола.
* При въвеждане на грешни такива, потребителят трябва да вижда съобщение за грешка.
* Ако потребителят, който вече е влезъл в системата (има валидна сесия) влезе в тази страница, трябва да бъде пренасочен към страницата със списъка на файловете.

**Описание на страницата "files.php":**
* В този екран трябва да има списък с всички файлове, които са качени от потребителя.
* Всеки файл трябва да се визуализира със своето име и трябва да бъде линк.
* Когато бъде натиснат линка, файла трябва да може да бъде свалян.

**Описание на страницата "upload.php":**
* В този екран трябва да има форма, която да позволява на потребителя да качи нов файл.

**Допълнителни задачи:**
* Показване на размера на файла, заедно с неговото име.
* Добавяне на възможност на повече от един потребител да качва файлове, като всеки потребител има своя папка, така че файловете да не се смесват, и единият да няма достъп до файловете на другия.

**Критерии за оценка:**
* Валидност на HTML/CSS НЕ трябва да участват в оценката. Оценява се PHP кода, не външният вид или валидността на HTML/CSS. Визуалната реализация не е от значение.
* Изпълнението или неизпълнението на допълнителните задачи НЕ дават влияние на оценката. Те са дадени за хората желаещи да разширят задачата.
* Работи ли системата за вход? Дава ли грешка при невалидно име/парола.
* Когато потребител със сесия влезе в страницата за вход дали се пренасочва правилно.
* Качват ли се правилно файловете.
* Списъкът показва ли правилно всички файлове.