The structure of project
-database: Folder containing data
-server: Folder containing file setup webserver with CentOS 7, PHP 7.4, Composer, Git
-src: Folder containing source code

Step by step  to run
	Create new folder database and src
    Copy or create the project to the src folder
    Open git bash or cmder
        docker-compose build && docker-compose up -d
    * If you are using windows cmd or powershell, you have to run these two commands separately
