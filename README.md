# 🎓 DevStream – API Fictícia

Este repositório foi criado como parte do **projeto acadêmico DevStream**, desenvolvido na disciplina **Análise e Projetos de Sistemas**.  
Seu objetivo é **simular uma API** utilizando o serviço [MyJSON Server](https://my-json-server.typicode.com/), permitindo realizar requisições e consumir dados de forma prática durante o desenvolvimento da aplicação.

---


## Sobre o MyJSON Server

O [MyJSON Server](https://my-json-server.typicode.com/) é uma ferramenta gratuita que permite hospedar um arquivo `db.json` diretamente no GitHub, simulando um backend REST sem necessidade de servidor.

**Base URL da API:**
> [https://my-json-server.typicode.com/joaoguiaguiar/videos-API](https://my-json-server.typicode.com/joaoguiaguiar/videos-API)

---

## 📂 Estrutura do Banco (db.json)

O arquivo `db.json` contém os dados fictícios utilizados no DevStream:

```json
{
  "videos": [
    {
      "id": 1,
      "titulo": "Introdução ao React",
      "categoria": "Frontend",
      "descricao": "Conceitos básicos de componentes e JSX.",
      "url": "https://www.youtube.com/watch?v=abcd1234"
    }
  ],
  "categorias": [
    {
      "id": 1,
      "nome": "Frontend"
    }
  ]
}

```

## 🔗 Repositório do Projeto DevStream

Para ver o front-end que consome esta API, acesse o repositório do projeto:

[https://github.com/joaoguiaguiar/devs-stream](https://github.com/joaoguiaguiar/devs-stream)


