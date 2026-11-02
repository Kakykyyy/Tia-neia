# Tia-neia — Site institucional

Protótipo de site institucional com páginas informativas do Instituto John Heliton, desenvolvido em HTML e CSS. Há páginas de início, notícias, sobre, contatos, cadastro e login.

## Execução local

Não há dependências npm nem backend no repositório. Para servir os arquivos por HTTP, use um servidor estático, por exemplo:

```sh
git clone https://github.com/Kakykyyy/Tia-neia.git
cd Tia-neia
python -m http.server 8000
```

Abra http://localhost:8000/projet%C3%A3o/home.html. Python é apenas uma opção de servidor local. É possível abrir `projetão/home.html` diretamente no navegador.

## Estrutura e navegação

| Caminho | Conteúdo |
|---|---|
| `projetão/home.html` | Página inicial |
| `projetão/front-end/sobre.html` | Apresentação institucional |
| `projetão/front-end/Notícias.html` | Notícias |
| `projetão/front-end/contatos.html` | Contatos |
| `projetão/front-end/cadastro.html` | Formulário visual de cadastro |
| `projetão/front-end/login.html` | Formulário visual de login |
| `projetão/styles/` | Folhas de estilo |

Preserve maiúsculas e acentos, especialmente `Notícias.html` e `projetão`, pois hospedagens podem diferenciar esses nomes.

## Funcionalidades e limites

As páginas apresentam conteúdo e navegação institucional. Os formulários de cadastro e login analisados não possuem integração de servidor, armazenamento de usuários ou autenticação. Os campos obrigatórios e de email oferecem somente a validação do navegador. Não use dados reais de acesso nesse protótipo.

## Personalização e publicação

Atualize textos e links nos arquivos HTML e estilos na pasta `styles/`. Mantenha os caminhos relativos, como `../styles/`, ao mover páginas.

A hospedagem deve servir arquivos estáticos. Como a entrada está em `projetão/home.html`, configure essa página como início ou disponibilize o endereço completo. O repositório não contém uma entrada `index.html` na raiz analisada.

## Verificação manual

Parta da home e confira cada link, imagens, estilos e adaptação a telas pequenas. Visite as páginas de cadastro e login para conferir apenas a interface. Não há suíte de testes automatizados nem confirmação de funcionamento de serviços externos.

## Licença

Não há arquivo LICENSE na árvore analisada. Confirme os direitos de textos e imagens antes de reutilizá-los.

---
Documentação baseada na leitura da branch principal em 2 de novembro de 2026. Os procedimentos não foram executados nesta revisão documental.
