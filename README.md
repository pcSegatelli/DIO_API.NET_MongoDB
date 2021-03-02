# DIO_API.NET_MongoDB

No appsettings.json da aplicação tem o item connectionstring que realizará a conexão com o banco de dados.
Para inserir seu próprio banco de dados, você obtém o caminho automático que o mongo gerará, não esquecendo de trocar a senha e o nome do seu banco de dados.

Exemplo:
"ConnectionString": "mongodb+srv://api:<password>@cluster0.hqybn.mongodb.net/<nome do banco>?retryWrites=true&w=majority",

Para fazer um teste:

Caminho:

https://localhost:5001/infectado

Modelo de dados a serem passados para o post do endpoint: 
{
	"dataNascimento": "1990-03-01",
	"sexo": "M",
	"latitude": -23.5630994,
	"longitude": -46.6565712
}