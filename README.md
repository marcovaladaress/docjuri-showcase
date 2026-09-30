# DocJuri

SaaS de gestão de contratos jurídicos, aditivos e histórico de alterações, em produção com um cliente.

> O código-fonte é privado porque o sistema está em uso por um cliente. Este repositório apresenta o produto, o escopo técnico e as decisões de arquitetura.

## O que o sistema faz

- Cadastro e acompanhamento de contratos e aditivos
- Versionamento com histórico completo de alterações, que permite reconstruir qualquer versão anterior de um contrato
- Validações de regra de negócio no servidor: consistência de datas, vigência e integridade entre contrato e aditivos
- Autenticação e autorização com controle de acesso por perfil de usuário
- Arquitetura multi-tenant, com isolamento de dados por empresa e configurações próprias por cliente

## Escopo

| | |
|---|---|
| Telas | 11 |
| Server Actions | 60 |
| Tabelas no banco | 18 |
| Clientes em produção | 1 |

## Stack

- **Front-end:** Next.js (App Router, Server Components, Client Components), React, TypeScript, Tailwind CSS
- **Back-end:** Server Actions do Next.js, BetterAuth
- **Banco de dados:** PostgreSQL
- **Infraestrutura:** AWS (S3)

## Autor

Desenvolvido sozinho por **Marco Valadares**, como freelance, desde 03/2026.

- LinkedIn: [linkedin.com/in/marcoaureliovaladares](https://www.linkedin.com/in/marcoaureliovaladares)
- Portfólio: [marcovsfernandes.com](https://www.marcovsfernandes.com)
- E-mail: contato@marcovsfernandes.com
# docjuri-showcase
Vitrine do DocJuri, SaaS de gestão de contratos juríicos em produção. Código privado.
