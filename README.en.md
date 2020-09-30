<p align="right">
  <a href="README.en.md">🇺🇸</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.md">🇧🇷</a>&nbsp;&nbsp;&nbsp;
</p>

<img alt="GoStack" src=./src/assets/header-bootcamp.png />

<h3 align="center">
  First project in Node.js
</h3>

<p align="center">
  <a href="#rocket-about-the-application">About the application</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cd-installed-packages">Installed packages</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

<img alt="Insomnia" src=./src/assets/screen-insomnia.gif />

## :rocket: About the application

The first project in Node.js with TypeScript, using the concept of models, repositories and services!

This is an application where you can create and list appointments.

### Application Routes

The application has the following routes:

- ** `POST / appointments` **: The route must receive `provider` and `date` within the body of the request, with `date` equal to `Timestamp => ISO-8601`. When registering a new appointment, it must be stored inside an object with the following format:

```json
{
  "id": "uuid",
  "provider": "Bruno",
  "date": "2020-09-30T10:00:00.000Z"
}
```

- ** `GET / appointments` **: This route should return a list with all the appointments you have registered so far. This route must return an object with the following format:

```json
[
	{
		"id": "uuid",
		"provider": "Bruno",
		"date": "2020-09-30T13:00:00.000Z"
	},
	{
		"id": "uuid",
		"provider": "Diego",
		"date": "2020-09-30T14:00:00.000Z"
	},
	{
		"id": "uuid",
		"provider": "Bruno",
		"date": "2020-09-30T15:00:00.000Z"
	}
]
```

## :cd: Installed packages

The following is a list of installed packages:

- [express](https://www.npmjs.com/package/express)
- [typescript](https://www.typescriptlang.org/)
- [ts-node-dev](https://github.com/whitecolor/ts-node-dev#readme)
- [uuid](https://www.npmjs.com/package/uuid)
- [date-fns](https://github.com/date-fns/date-fns#readme)

	Opcional
- [eslint](https://eslint.org/)
- [prettier](https://prettier.io/)
- [eslint-import-resolver-typescript](https://github.com/alexgorbatchev/eslint-import-resolver-typescript#readme)

## :memo: Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.
