# Fórmula 1 API

Este projeto é uma API desenvolvida com Fastify e TypeScript, que fornece informações sobre equipes e pilotos de Fórmula 1. A API é capaz de listar todos os times e pilotos, bem como detalhes específicos sobre cada piloto.

## Funcionalidades

- **Listagem de equipes**: Retorna informações sobre as equipes de Fórmula 1, incluindo nome e localização.
- **Listagem de pilotos**: Fornece uma lista de pilotos e suas respectivas equipes.
- **Consulta individual de pilotos**: Permite buscar informações detalhadas de um piloto específico através de seu ID.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **Fastify**: Framework web de alta performance.
- **TypeScript**: Superconjunto de JavaScript que adiciona tipagem estática.
- **CORS**: Configuração de segurança para permitir acessos de diferentes origens.

## Instalação

Para instalar e rodar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-formula1.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd projeto-formula1
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Inicie o servidor em modo de desenvolvimento:
   ```bash
   npm run start:dev
   ```

## Uso

Após iniciar o servidor, você pode acessar as rotas disponíveis:

- `GET /teams` - Lista todas as equipes de Fórmula 1.
- `GET /drivers` - Lista todos os pilotos de Fórmula 1.
- `GET /drivers/:id` - Retorna informações detalhadas de um piloto específico pelo ID.

## Estrutura do Projeto

```plaintext
├── src
│   ├── server.ts        # Arquivo principal do servidor
│   └── (outros arquivos .ts e .env)
├── .env                 # Variáveis de ambiente
├── package.json         # Dependências e scripts do projeto
└── tsconfig.json        # Configurações do TypeScript
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a licença ISC. Consulte o arquivo LICENSE para mais detalhes.

## Contato

Para mais informações, entre em contato com:
<br />
Email: [Leonardo Bernardo](mailto:leonardo.bernardo2658@gmail.com).
LinkedIn: [Leonardobern](https://www.linkedin.com/in/leonardo-bern/).
