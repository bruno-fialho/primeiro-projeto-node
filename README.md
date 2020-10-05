<p align="right">
  <a href="README.en.md">🇺🇸</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.md">🇧🇷</a>&nbsp;&nbsp;&nbsp;
</p>

<img alt="GoStack" src=./src/assets/header-bootcamp.png />

<h3 align="center">
  Primeiro projeto Node.js
</h3>

<p align="center">
  <a href="#rocket-sobre-a-aplicação">Sobre a aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cd-pacotes-instalados">Pacotes instalados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<img alt="Insomnia" src=./src/assets/screen-insomnia.gif />

## :rocket: Sobre a aplicação

O primeiro projeto em Node.js junto ao TypeScript, utilizando o conceito de models, repositories e services!

Essa é uma aplicação no onde será possível criar a listar agendamentos.

### Rotas da aplicação

A aplicação tem as seguintes rotas:

- **`POST /appointments`**: A rota deve receber `provider` e `date` dentro do corpo da requisição, sendo `date` igual a `Timestamp => ISO-8601`.  Ao cadastrar um novo agendamento, ele deve ser armazenado dentro de um objeto com o seguinte formato:

```json
{
  "id": "uuid",
  "provider": "Bruno",
  "date": "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
}
```

- **`GET /appointments`**: Essa rota deve retornar uma listagem com todos os agendamentos que você cadastrou até agora. Essa rota deve retornar um objeto com o formato a seguir:

```json
[
	{
		"id": "uuid",
		"provider": "Bruno",
		"date": "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
	},
	{
		"id": "uuid",
		"provider": "Diego",
		"date": "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
	},
	{
		"id": "uuid",
		"provider": "Bruno",
		"date": "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
	}
]
```

## :cd: Pacotes instalados

A seguir segue uma lista dos pacotes instalados:

- [express](https://www.npmjs.com/package/express)
- [typescript](https://www.typescriptlang.org/)
- [ts-node-dev](https://github.com/whitecolor/ts-node-dev#readme)
- [uuid](https://www.npmjs.com/package/uuid)
- [date-fns](https://github.com/date-fns/date-fns#readme)

	Opcional
- [eslint](https://eslint.org/)
- [prettier](https://prettier.io/)
- [eslint-import-resolver-typescript](https://github.com/alexgorbatchev/eslint-import-resolver-typescript#readme)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
