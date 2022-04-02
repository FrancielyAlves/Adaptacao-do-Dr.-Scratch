# Adaptacao-do-Dr.-Scratch
Dr. Scratch é uma ferramenta que avalia 7 conceitos do Pensamento Computacional em projetos produzidos no scratch. O feedback da ferramenta mostra pontuações sobre os conceitos de abstração, raciocínio lógico, sincronização, paralelismo, controle de fluxo, interatividade com usuário e representação de dados. 

A ferramenta ṕode ser acessada em: http://drscratch.org

Para utilizar a ferramenta Dr. Scratch adaptada para funcionar localmente acoplada a um banco de dados MySQL, utilize o sistema operacional linux e siga os passos:

1 - Faça o download do Dr. Scratch em https://github.com/AngelaVargas/drscratchv3
2 - E adicione o file aqui disponivel.
3- Utilize os comandos: 
mkdir log
cd./log
touch log.File.txt
cd
sudo docker-compose up

4- Para acoplar a um banco de dados, utilize o hostname: 172.18.0.2
5- Para acessar os conteiners docker, utilize:
$ docker run -d -p 3306:3306 --name a(dicione um nome) -e MYSQL_ROOT_PASSWORD= (crie uma senha) mysql  

6- Para ter uma visualização gráfica do banco de dados, será utilizado o MySQL com Docker, acessado pelo mysql workbench.
