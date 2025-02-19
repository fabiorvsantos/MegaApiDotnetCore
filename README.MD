<h1 align="center">
  <br />
  <img
    src="./_docs/assets/icon.png"
    alt="API Robos Mega Man"
    width="150"
  />
  <br />
  <b>API Robos Mega Man</b>
  <br />
  <sub
    ><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml"
  >
    <img
      src="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg"
      alt=""
    />
  </a>
  <a href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/felipeAguiarCode/MegaApiDotnetCore"
      alt="Latest Release"
    />
  </a>
</h1>

## Sobre

<p align="center">
  Esta API desenvolvida em .NET Core foi criada para fornecer dados no formato JSON sobre os chefes da série Mega Man. 
Trata-se de um serviço backend baseado no .NET Core 3.1, utilizando tecnologias modernas para gerenciamento de dados e manipulação de respostas da API.
  <br />
</p>

<p align="center">
  Construída com Entity Framework Core e outras tecnologias .NET, este projeto busca oferecer uma API robusta para acessar informações sobre os robôs do universo Mega Man.
  <br />
</p>

<p align="center">
  <br />
  <img src="./_docs/assets/carbon.png" />
</p>

## Endpoints da API

<table align="center">
  <tr>
    <th>Método</th>
    <th>Endpoint</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots</td>
    <td>Retorna uma lista com todos os robôs</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/v1/robots/{id}</td>
    <td>Retorna detalhes de um robô específico pelo ID</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/v1/robots</td>
    <td>Cria um novo registro de robô</td>
  </tr>
</table>

## Tecnologias Utilizadas

<p align="center">
  - <b>Entity Framework Core:</b> ORM para gerenciamento de dados.<br />
  - <b>Arquitetura RESTful:</b> Design de API para comunicação clara e eficiente.<br />
  - <b>Injeção de Dependência:</b> Facilita o desacoplamento e melhora a testabilidade do código.<br />
</p>

## Dependências

<table align="center">
  <tr>
    <th>Pacote</th>
    <th>Versão</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td>
      <a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8">NuGet</a>
    </td>
  </tr>

  <tr>
    <td>Biblioteca principal do Entity Framework Core (EF Core), usada para acessar bancos de dados de forma orientada a objetos.</td>
  </tr>

  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td>
      <a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8">NuGet</a>
    </td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td>
      <a href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8">NuGet</a>
    </td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td>
      <a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a>
    </td>
  </tr>
</table>

## 📂 Estrutura do Projeto

```
🌐
src
├── 📂 Controllers      [Rotas da API]
├── 📂 Models           [Modelos de dados]
├── 📂 Services         [Regras de negócio]
├── 📂 Middlewares      [Funções intermediárias entre a requisição HTTP e a resposta final]
├── 📂 Database         [Estruturas relacionadas ao banco de dados]
│   ├── 📂 DTOs             [Mdelos de Entrada e View Models (Data Transfer Objects)]
│   ├── 📂 EntityFramework  [Aquivos do ORM Entity Framework]
│   │     ├── 📂 Context         [Cnfigurações do contexto do banco de dados]
│   │     ├── 📂 Migrations      [Migrações para atualizações do banco]
│   ├── 📂 Repositories     [Padrão de repositório]
```

## 📜 Licença
Este software é licenciado sob os termos da [MIT License](LICENSE).<br />
⌨️ FelipeAguiar - [Github](https://github.com/felipeAguiarCode)<br />
👨 Traduzido e adaptado por FabioRVSantos - [Github](https://github.com/fabiorvsantos/MegaApiDotnetCore)
