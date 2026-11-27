# Guia de Contribuição — OpenDigital

Agradecemos o interesse em contribuir com os repositórios da **OpenDigital**.

## Antes de começar

1. Leia o `README.md` e, quando presente, o `AGENTS.md` ou `CONTRIBUTING.md` específico do repositório — regras locais do repositório prevalecem sobre este guia geral.
2. Verifique issues e pull requests abertos para evitar trabalho duplicado.
3. Para mudanças estruturais ou novas funcionalidades, abra primeiro uma issue descrevendo problema, proposta e critérios de aceite.

## Padrões de desenvolvimento

- **Conventional Commits:** utilize mensagens claras seguindo o padrão [Conventional Commits](https://www.conventionalcommits.org/) (ex.: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`).
- **Commits assinados:** recomendamos fortemente assinar seus commits via GPG ou SSH.
- **Mudanças focadas:** mantenha cada Pull Request pequeno, coeso e com escopo bem definido.
- **Qualidade verificável:** execute os testes, linter e verificação de tipos previstos no repositório antes de abrir o PR e informe o resultado na descrição.
- **Segurança e privacidade:** nunca inclua credenciais, tokens, chaves privadas ou dados pessoais reais em código, commits, fixtures ou prints. Use sempre dados fictícios em exemplos e testes.

## Fluxo de Pull Request

1. Crie uma branch descritiva a partir da branch principal do repositório.
2. Implemente a mudança acompanhada de testes e documentação atualizada quando aplicável.
3. Preencha o modelo de Pull Request explicando o contexto, o que foi validado e eventuais riscos.

## Conduta e Segurança

- Todas as interações seguem o nosso [Código de Conduta](CODE_OF_CONDUCT.md).
- Falhas de segurança devem ser reportadas de forma privada conforme a [Política de Segurança](SECURITY.md).
