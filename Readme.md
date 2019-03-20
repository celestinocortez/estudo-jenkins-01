# Cria diretório do projeto
```shell
$ cd
$ cd Warehouse/estudo-jenkins-01
```

# Clona repositório
```shell
foo@bar:~$ git clone https://github.com/executeautomation cucumberbasic.git
```

# Maven Configura Variáveis de ambiente
M2 -> ../apache-maven-3.3.9/bin
M2_HOME -> ../apache-maven-3.3.9
M2_REPO -> ../apache-maven-3.3.9/.m2

# Maven clean, compile e package
```
foo@bar:~$ mvn clean
foo@bar:~$ mvn compile 
foo@bar:~$ mvn package
```

# Jenkins Configura idioma en_US
Gerenciar Jenkins > Gerenciar Plugins > Disponíveis > Locale (Instalar)
Gerenciar Jenkins > Configurar Sistema > Locale > en_US (Ignore browser)

# Jenkins Job basic
Localhost:8080/

# Git Novo Repositório
github > new repository > celestinocortez/estudo-jenkins-01 > public
```
foo@bar:~$ git init
foo@bar:~$ git add .
foo@bar:~$ git commit -m "init"
foo@bar:~$ git remote add origin https://github.com/celestinocortez/estudo-jenkins-01.git
foo@bar:~$ git remote -v
foo@bar:~$ git push -u origin master
git add . && git commit -m "issue readme" && git push
```





