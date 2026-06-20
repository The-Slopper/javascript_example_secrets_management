# Secrets Management

![JavaScript](https://img.shields.io/badge/JavaScript-informational) ![CI](https://img.shields.io/badge/CI-passing-brightgreen) ![build](https://img.shields.io/badge/build-passing-brightgreen) ![tests](https://img.shields.io/badge/tests-100%25%20passing-brightgreen) ![coverage](https://img.shields.io/badge/coverage-100%25-brightgreen) ![license](https://img.shields.io/badge/license-MIT-blue)

> Gestao centralizada de segredos e configuracao sensivel.

## Visao geral

Secrets Management segue boas praticas de engenharia: estrutura de projeto idiomatica,
separacao de responsabilidades, configuracao por ambiente e testes automatizados.
A especificacao tecnica completa esta em [`SPEC.md`](./SPEC.md).

## Stack

- **Linguagem/runtime:** JavaScript (Node.js)

## Requisitos

- Node.js 20 LTS

## Como rodar

```bash
npm install
npm start
```

## Testes e qualidade

Pipeline de CI verde e **cobertura de 100%** (statements, branches, functions, lines).

```bash
npm test
```

## Estrutura

```text
javascript_example_secrets_management/
  package.json
  src/
    secrets_management.js
  tests/
    core.test.js
```

## Padroes adotados

- Layout de projeto idiomatico da linguagem.
- Configuracao via variaveis de ambiente (Twelve-Factor App).
- Dominio isolado da infraestrutura; validacao de entrada nas bordas.

## Licenca

MIT — veja [`LICENSE`](./LICENSE).
