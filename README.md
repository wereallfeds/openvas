# openvas

OpenVAS is a framework of several services and tools offering a comprehensive and powerful vulnerability scanning and vulnerability management solution.

Installation
----
        sudo add-apt-repository ppa:mrazavi/openvas
        sudo apt-get update
        sudo apt-get install openvas sqlite3
        sudo openvas-nvt-sync
        sudo openvas-scapdata-sync
        sudo openvas-certdata-sync
        sudo service openvas-scanner restart
        sudo service openvas-manager restart
        sudo openvasmd --rebuild --progress

Usage
----
Login into https://localhost:443 with "admin" as username and password.
