## v0.4.2
- Support ./bin/* files (#48)

## v0.4.1
- Add some dependencies

## v0.4.0
- Use aws-sdk-promise

## v0.3.6
- Escape input in request template (#33)
- Support memorySize option (#34)

## v0.3.4
- Support configuration of AWS region (#31)

## v0.3.3
- Fix missing lib dir in npm package

## v0.3.2
- Support node-config

## v0.3.1
- Fix fluct-deploy bug

## v0.3.0
- Add new command: `fluct open`
- Require accountID and role name
- Only include production dependencies into lambda.zip
- Support other response status code

## v0.2.7
- Include HTTP request data into event object

## v0.2.6
- Support any Content-Type

## v0.2.5
- Fix `fluct deploy` error on uploading new function

## v0.2.4
- Fix function upload bug

## v0.2.3
- Change `fluct generate` command interface

## v0.2.2
- Use common package.json in all actions
- Add `fluct deployments` command

## v0.2.1
- Add missing dependency (#14)
- Fix `fluct deploy` bug

## v0.2.0
- Change action directory structure
- Include node_modules into zip file for Lambda function
- Improve `fluct deploy` logs
- Improve `fluct routes` format

## v0.1.2
- Fix broken `fluct server` command

## v0.1.1
- Add new command: `fluct install`
- Provide command aliases

## v0.1.0
- Use text/html response by default

## v0.0.8
- Add new command: `fluct routes`
- Create deployment at the end of `fluct deploy`

## v0.0.7
- Create restapi only at 1st time
- Improve generated package.json content

## v0.0.6
- Add new command: `fluct deploy`

## v0.0.5
- Make handler reloadable
- Fix missing templates dir

## v0.0.4
- Add new command: `fluct server`
- Fix package.json bin property

## v0.0.3
- Add missing bin dir into fluct npm package

## v0.0.2
- Add new command: `fluct new`
- Add new command: `fluct generate action`

## v0.0.1
- 1st Release
