<div align="center">

# Tia-neia

**Presença digital para um projeto institucional**

![HTML](https://img.shields.io/badge/HTML-20232a?style=flat-square) ![CSS](https://img.shields.io/badge/CSS-20232a?style=flat-square)

[Sobre](#sobre) · [Como executar](#como-executar) · [Documentação](DOCUMENTACAO.md)

</div>

---

## Sobre

Protótipo de site institucional do Instituto John Heliton. O projeto organiza informações, notícias e contatos em páginas próprias, com uma identidade visual compartilhada.

## Destaques

- Página inicial de apresentação.
- Páginas de notícias, sobre e contatos.
- Interfaces visuais de cadastro e login.
- Estilos organizados por página.

## Como executar

Clone o repositório:

```sh
git clone https://github.com/Kakykyyy/Tia-neia.git
cd Tia-neia
```

Também é possível abrir `projetão/home.html` diretamente. Cadastro e login são interfaces de demonstração; não possuem autenticação ou persistência de usuários.

```sh
python -m http.server 8000
```

Acesse [a aplicação local](http://localhost:8000/projet%C3%A3o/home.html).

## Organização

```text
projetão/
├── home.html   # Entrada do site
├── front-end/  # Notícias, sobre, contatos e formulários
└── styles/     # Folhas de estilo
```

## Personalização

Edite o conteúdo nas páginas HTML e a aparência em `projetão/styles/`. Preserve os caminhos relativos, os acentos e as maiúsculas nos nomes dos arquivos, especialmente `Notícias.html`.

## Publicação

O projeto pode ser servido como site estático. Configure a entrada para `projetão/home.html` ou use o endereço completo dessa página.

## Documentação técnica

O [guia técnico](DOCUMENTACAO.md) reúne configuração, comportamento dos dados, limitações conhecidas e verificações manuais. As instruções foram elaboradas a partir da leitura do código; a execução dos projetos não foi validada nesta revisão.

## Autor

Desenvolvido por [Kayky Erick · @Kakykyyy](https://github.com/Kakykyyy).
