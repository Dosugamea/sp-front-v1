# Sonolus uploader (frontend for sonolus uploader)

Frontend for first public [Sonolus](https://sonolus.com/) server api, named [sonolus-uploader-core](https://github.com/PurplePalette/sonolus-uploader-core).

## Running Requirements
- Firebase Storage
  - This api uses it for upload contents.
- Firebase Authorization
  - This api depends it to verify the user.
- Backend(required)
  - This api don't access firestore directly.
  - You can use [sonolus-uploader-core](https://github.com/PurplePalette/sonolus-uploader-core) or make your own backend.

## Building requirements
- Node.js
- npm

## Objectives
Some sonolus community uses static files to deliver their sonolus contents.
It has risk to break whole db by conflict or typo when changing, and also hard to add new contents.
With this frontend and backend, they don't need to care to make breaking change anymore.

## License
GPL

## Powered by OpenAPI
`potato` is typescript-axios client was generated by the [openapi-generator](https://openapi-generator.tech) project.
By using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate another client stub. To see how to make this your own, look these: [README](https://openapi-generator.tech) / [ServerSpec](https://github.com/PurplePalette/sonolus-uploader-core/blob/main/api/openapi.yaml)
- API version: 1.0
- Build date: 2021-05-19T23:54:50.576+09:00[Asia/Tokyo]
- For more information, please visit [https://discord.gg/KEfVkfC6Q9](https://discord.gg/KEfVkfC6Q9)

## For more information
Please see [wiki sections](https://github.com/PurplePalette/sonolus-uploader/wiki) of sonolus-uploader-core.
