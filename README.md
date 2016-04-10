#Installation
FOLLOW THESES EASY STEPS:

        sudo add-apt-repository ppa:mrazavi/openvas
        sudo apt-get update
        sudo apt-get install openvas

You have to update openvas scripts/data after installation with the following commands:

        sudo apt-get install sqlite3
        sudo openvas-nvt-sync
        sudo openvas-scapdata-sync
        sudo openvas-certdata-sync

        sudo service openvas-scanner restart
        sudo service openvas-manager restart
        sudo openvasmd --rebuild --progress

Login into https://localhost:443 with "admin" as username and password.
