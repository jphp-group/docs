Сборка
------

Чтобы собрать JPHP вам необходимо:

#. Установить JDK (OpenJDK или Oracle) для вашей ОС:
  
    .. note::
      * Для Windows: `<http://www.oracle.com/technetwork/java/javase/downloads/index.html>`_
      * Для Linux: `<http://openjdk.java.net/install/index.html>`_
 
#. Установить систему сборки Gradle `<http://gradle.org/>`_

    .. note::
      Не забудьте добавить путь к bin папки gradle в вашу PATH переменную

#. Взять все исходники проекта из нашего `репозитария <https://github.com/jphp-compiler/jphp.git>`_ ::

    git clone https://github.com/jphp-compiler/jphp.git
    cd jphp

#. Собрать jar файлы через Gradle::

    gradle jar

Теперь вы сможете найти выполняемый jar файл в ``jphp-cli/build/libs`` директории. Чтобы проверить, что все работает -
используйте следующую команду::

    cd jphp-cli/build/libs
    chmod +x jphp # for linux
    ./jphp -v # show version