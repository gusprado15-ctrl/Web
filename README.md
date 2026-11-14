# Portfólio Pessoal — Gustavo Henrique Dias Prado

## Descrição
Este projeto é um portfólio pessoal desenvolvido como atividade de Desenvolvimento de Sistemas. O site apresenta o perfil do aluno, projetos de estudo, habilidades e formas de contato.

## Tecnologias utilizadas
- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.3

## Estrutura do projeto
- `index.html`: página principal, com todo o conteúdo, estilos e scripts.

## Funcionamento
O menu superior permite navegar pelas seções Perfil, Projetos, Habilidades e Contato. O layout utiliza o sistema de grid e componentes responsivos do Bootstrap para se adaptar a celulares e computadores. Os cartões apresentam projetos e tecnologias estudadas. Os links externos abrem em uma nova aba.

## Recurso novo adicionado
Foi adicionada uma animação de entrada dos elementos durante a rolagem da página. Os títulos, cartões e caixas aparecem suavemente quando entram na área visível da tela. Também foram incluídos efeitos de hover nos cartões de projetos e no botão principal.

## Como o recurso foi implementado
A animação de entrada foi feita com JavaScript usando a API `IntersectionObserver`. O script observa os elementos que possuem a classe `reveal` e, quando eles aparecem na tela, adiciona a classe `visible`. No CSS, as classes controlam a opacidade e o deslocamento vertical com `transition`. Assim, o conteúdo surge de forma suave durante a navegação. Os efeitos de hover foram implementados com `:hover` e `transition` no CSS.

## Publicação no GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie o arquivo `index.html` e este `README.md` para a raiz do repositório.
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
6. Aguarde a publicação. O GitHub mostrará o endereço do site na área **Settings > Pages**.

## Links de entrega
- Repositório GitHub: `(https://github.com/gusprado15-ctrl/Web.git)`
- Site publicado (GitHub Pages): `COLE_AQUI_O_LINK_DO_SITE`

## Personalização antes da entrega
- Atualize a descrição do perfil para refletir suas informações.
- Substitua os projetos de exemplo pelos seus trabalhos reais, se desejar.
- Troque o link genérico do GitHub pelo endereço do seu perfil.
- Adicione seu e-mail na seção Contato.
- Depois de publicar, substitua os dois campos de links de entrega acima pelos endereços reais.
