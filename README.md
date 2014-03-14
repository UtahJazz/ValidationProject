ValidationProject
=================
Программа представляет собой сайт, валидирующий данные введеные в формы со стороны клиента и на серверной стороне. (Проверить проще всего отключив JS)

Для деплоя под Linux необходимо установить следующее ПО:
1)MonoDevelop: 
sudo apt-get install mono-xsp
2)XSP (это облегченный Web-сервер): sudo apt-get install mono-xsp
Либо Apache и специальный плагин:
apt-get install libapache2-mod-mono mono-apache-server2
apt-get install mono-devel
После установки перезапустить Apache
a2enmod mod_mono_auto
/etc/init.d/apache2 restart

Для запуска можно открыть проект в оконном режиме monoDevelop и нажать Run
Более подробное описание по ссылке: http://www.ibm.com/developerworks/ru/library/l-Mono_10/


Для деплоя в windows нужно иметь следующее программного обеспечение:
IIS (Express),
SQL Server (Express),
Web Matrix,
Visual Studio (Express) 2012 for Web.

Данное программного обеспечение проще всего установить через Microsoft Web Platform Installer.

Для запуска открыть .sln файл проекта и нажать f5 для сборки.

