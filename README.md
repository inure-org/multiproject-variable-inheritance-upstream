# herança de variáveis ​​de multiprojeto

nesse exemplo, está sendo demonstrado uma passagem de variáveis para uma pipeline downstream utilizando uma [herança de variável dotenv](https://docs.gitlab.com/ee/ci/variables/README.html#pass-an-environment-variable-to-another-job) e [downloads de artefato de um projeto cross](https://docs.gitlab.com/ee/ci/yaml/README.html#cross-project-artifact-downloads-with-needs)

**lembrete**: não há um arquivo `credentials.env` existindo em ambos os repositórios dos projetos. isso é passado dinamicamente como artefatos de trabalho apenas.

## links de documentação

leia mais sobre:

1. [herança de variável dotenv](https://docs.gitlab.com/ee/ci/variables/README.html#pass-an-environment-variable-to-another-job)
2. [downloads de artefato de projeto cross](https://docs.gitlab.com/ee/ci/yaml/README.html#cross-project-artifact-downloads-with-needs)
3. [passar variáveis para uma pipeline downstream com uma herança de variável dotenv e downloads de artefato de projeto cross](https://docs.gitlab.com/ee/ci/multi_project_pipelines.html#with-variable-inheritance)
