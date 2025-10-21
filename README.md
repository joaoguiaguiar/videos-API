# 🎓 DevStream – API Fictícia

Este repositório foi criado como parte do **projeto acadêmico DevStream**, desenvolvido na disciplina **Análise e Projetos de Sistemas**.  
Seu objetivo é **simular uma API** utilizando o serviço [MyJSON Server](https://my-json-server.typicode.com/), permitindo realizar requisições e consumir dados de forma prática durante o desenvolvimento da aplicação.

---

## 🧩 Contexto do Projeto

O DevStream foi um projeto idealizado como estudo de caso para a aplicação dos conceitos vistos em sala, como:

- Levantamento de requisitos funcionais e não funcionais  
- Modelagem UML (casos de uso, atividades, sequência e classes)  
- Planejamento e estruturação de sistemas  
- Simulação de consumo de APIs com **Axios** e **MyJSON Server**

Esta API, portanto, **não é real**, sendo utilizada apenas como apoio didático para o front-end do projeto DevStream, desenvolvido em **React + TypeScript**.

---

## ⚙️ Sobre o MyJSON Server

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

[https://github.com/joaoguiaguiar/devs-stream](h)


