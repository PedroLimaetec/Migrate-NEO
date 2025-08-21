# Atividade PW - Migration com Primary Key e Foreign Key
## Criação do Projeto
Primeiro foi necessário executar o seguinte comando para a instalação do Laravel/criação do projeto
![](prints-processo/print%201.png)

### Importante! É preciso iniciar o Apache e o MySQL no Xampp
![](prints-processo/print%202.png)

## Migrations
Primeiro conecte o banco de dados através do arquivo .env (lembre-se de criar o banco de dados no phpMyAdmin)
![](prints-processo/print%203.png)

Após isso, execute o seguinte comando no terminal
![](prints-processo/print%204.png)

Com isso um arquivo com o mesmo nome declarado foi criado na pasta migrations. Altere a função "up()" desse arquivo.
![](prints-processo/print%205.png)

Repita o processo para a tabela estoque
![](prints-processo/print%206.png)

Agora altere a tabela cadastro executando o seguinte comando
![](prints-processo/print%207.png)

![](prints-processo/print%208.png)

E faça a mesma alteração do arquivo "up()" que você fez anteriormente
![](prints-processo/print%209.png)

Por fim, execute as migrations
![](prints-processo/print%2010.png)

E verifique se tudo ocorreu de forma correta no phpMyAdmin
![](prints-processo/print%2011.png)

![](prints-processo/print%2012.png)

![](prints-processo/print%2013.png)

