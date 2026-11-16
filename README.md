# 🌟 Meu Portfólio Profissional

## Nome do Aluno
Bianca Simões Sales Costa

## Descrição do Portfólio
Este projeto consiste no desenvolvimento e evolução de um portfólio pessoal interativo e responsivo. O objetivo principal foi criar uma vitrine profissional para expor meus projetos, competências e formas de contato, aplicando conceitos modernos de design e usabilidade.

## Tecnologias Utilizadas
- **HTML5** (Estruturação semântica)
- **CSS3** (Estilizações customizadas e animações)
- **Bootstrap 5** (Framework para layout responsivo, componentes e grid system)
- **JavaScript** (Interatividade e manipulação do DOM)
- **Git e GitHub / GitHub Pages** (Controle de versão e hospedagem)

## Link do Site Publicado
[Acesse o Portfólio no GitHub Pages](https://biassales.github.io/meu-portfolio/)

## Explicação do Funcionamento do Projeto
O site é composto por uma página de navegação fluida em página única (*Single Page Application* estilo *landing page*), contendo:
1. **Menu de Navegação:** Fixo no topo com links internos que direcionam suavemente para cada seção.
2. **Seção de Perfil:** Apresentação pessoal e principal chamada para ação (*call to action*).
3. **Seção de Projetos:** Cards organizados em grid apresentando os trabalhos realizados.
4. **Seção de Habilidades (Recurso Novo):** Exibição em blocos das principais competências técnicas e comportamentais.
5. **Seção de Contato:** Formulário funcional estruturado com inputs estilizados via Bootstrap.

## Descrição do Recurso Novo Adicionado
Foram implementados dois recursos novos principais para elevar a qualidade do projeto base:
1. **Nova Seção de Habilidades:** Um bloco dedicado a destacar competências técnicas e profissionais de forma visualmente limpa.
2. **Efeitos Visuais de Transição (Hover Effects):** Animações suaves em CSS aplicadas nos cards de projetos, fazendo com que eles se elevem sutilmente ao passar o cursor do mouse (`transform: translateY(-8px)`).

## Explicação de Como Esse Recurso Foi Implementado
- **Nova Seção:** Criada utilizando a estrutura de grids do Bootstrap (`row` e `col-md-4`) combinada com utilitários de espaçamento (`py-5`, `mb-3`) e cartões estilizados com classes de fundo (`bg-white`), bordas arredondadas (`rounded`) e sombras suaves (`shadow-sm`).
- **Animações Hover:** Adicionada uma regra personalizada em CSS (`.project-card`) utilizando a propriedade `transition` combinada com a pseudoclasse `:hover` e a função `translateY`, proporcionando um feedback visual dinâmico e moderno para o usuário.