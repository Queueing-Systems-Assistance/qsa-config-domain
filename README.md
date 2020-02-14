# Config Domain

Config Domain is the base structure for the configuration framework. It used by the configuration resolver, configuration validator and the config packs. It's fully extendable, you can write your own config pack and import the necessary dependencies which includes:
- Config Domain
- Config Validator (for the config pack)
- Config Resolver (for resolving the configs)

For those who want to help to develop the framework:
- [Git workflow](https://github.com/Queueing-Systems-Assistance/qsa-application/docs/git-workflow.md)
- Use `gradle clean build` to build the project
- If you want to deploy it into your local repository, issue `gradle clean install`
