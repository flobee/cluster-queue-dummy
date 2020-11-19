cluster-queue - Dummy Projekt
============================================================

Projekt bezogene 'dummy' Quellen zur Verwendung als Vorlage für ein eigenes Project.

Programm Beschreibung siehe 'cluster-queue - core' [README](vendor/cluster-queue/core/README.md)



Installation
------------------------------------------------------------

Um das Programm nutzen zu können müssen Abhängigkeiten installiert werden.

    cd ./

    php7.3 /path/to/composer.phar install

    php7.3 /path/to/composer.phar run post-install-cmd

    # Falls nicht ausführbar:
    chmod +x php-cluster-queue

    # Starten:
    # ./php-cluster-queue

Composer (composer.phar)? "A Dependency Manager for PHP" [Homepage](https://getcomposer.org),
[Download](https://getcomposer.org/download).


### Anforderungen

Anforderungen an dieses Programm:

    php >= 7.3, 7.4, 8.0 ...
    php-cli
    ssh
    scp
