Russian RAPIRA language pack and manual for SuiteCRM
=========================================

+ Здесь находится самая актуальная версия языковых файлов для [SuiteCRM][suitecrm] (форка безвременно почившего [SugarCRM CE][sugar]), с учётом последних дополнений и исправлений
+ Обновление языковых файлов проще всего сделать через установку языкового пакета ([ссылка на последний актуальный перевод для SuiteCRM 7.11][langpack]); процесс установки/обновления пакета русификации SuiteCRM описан ниже
+ Перевод Руководства пользователя и администратора SuiteCRM осуществляется [здесь][man-adoc]
+ Обсуждение русификации интерфейса и перевода документации по SuiteCRM доступно на [официальном форуме][forum]

------------------------------------------------

**Обратите внимание: в версии 7.10.10 и последующих используется значительно обновлённый языковой пакет. 
Если вы используете предыдущие версии SuiteCRM - загружайте [соответствующие](https://github.com/likhobory/SuiteCRM7RU/releases) языковые пакеты.**

------------------------------------------------

<b>Что нового в SuiteCRM 7.11</b>    (полная история изменений содержится в файле [HISTORY.TXT][history])

Добавлена возможность синхронизации Встреч с календарём Google.  
Расширены возможности поиска данных в системе за счёт интеграции с Elasticsearch версии 5.6.   
Изменения в модуле ПРОЦЕССЫ:  
	- Добавлен новый функционал в действия: копирование электронных адресов из контролируемого модуля  
Добавлена возможность отображать функционал указанной субпанели в виде отдельных кнопок.

Ссылки на описание нововведений доступны на [официальном форуме](https://suitecrm.com/suitecrm/forum/suitecrm-forum-russian-general-discussion/17973-suitecrm#60692).

------------------------------------------------

<b>Русский язык в SuiteCRM: установка языкового пакета</b>

Все действия по установке дополнительных пакетов (не только языковых) производятся через панель администратора.

1. Входим в систему с правами администратора.
2. В правом верхнем меню выбираем пункт <b>Администрирование</b> (Admin) для входа в раздел администратора системы.
3. В разделе администратора выбираем <b>Загрузчик модулей</b> (Module Loader).
4. Если в SuiteCRM уже был установлен пакет русификации, то его рекомендуется удалить (кнопка  <b>Деинсталлировать</b>).
5. Загружаем архив с языковым пакетом и далее следуем шагам, описанным в мастере.
6. После того как мастер сообщит об успешной установке пакета, рекомендуется выполнить быстрое восстановление: Администрирование->Восстановление->Быстрое восстановление (Admin->Repair->Quick Repair and Rebuild).
7. Выходим из системы (Logout) и на странице ввода логина/пароля выбираем необходимый язык интерфейса системы.
8. Вновь входим в систему.

Установленный язык можно указать в качестве языка по умолчанию. Для этого в панели администрирования в подразделе <b>Региональные настройки</b> выберите соответствующий языковой пакет (Admin->Locale Settings->Default Language).

------------------------------------------------

<b>Документация к SuiteCRM</b>

Детальная информация по установке, настройке и использованию системы описана в русскоязычной [документации к SuiteCRM][man-ru].

Пользователям, не знакомым с SuiteCRM, в первую очередь рекомендуются к прочтению раздел [Начало работы][getting-started], описывающий основные технические требования, необходимые для работы в системе, и раздел  
[Описание пользовательского интерфейса][ui], знакомящий с основными настройками системы. В описании присутствует масса перекрёстных ссылок, позволяющих быстро перейти к подробному описанию рассматриваемого функционала.

            
[langpack]: https://github.com/likhobory/SuiteCRM7RU/blob/ver.7.11/rapira-suite_pack_russian-7.11.zip?raw=true
[man-adoc]: https://github.com/likhobory/SuiteDocs/blob/master/README.ru.adoc
[man-ru]: https://docs.suitecrm.com/ru
[getting-started]: https://docs.suitecrm.com/ru/user/introduction/getting-started
[ui]: https://docs.suitecrm.com/ru/user/introduction/user-interface

[suitecrm]: https://github.com/salesagility/SuiteCRM
[forum]: https://suitecrm.com/suitecrm/forum/suitecrm-forum-russian-general-discussion
[sugar]: https://ru.wikipedia.org/wiki/SugarCRM
[history]: https://github.com/likhobory/SuiteCRM7RU/blob/master/HISTORY.TXT

