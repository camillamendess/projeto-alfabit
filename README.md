## Projeto Design System com Next.js e TailwindCSS

Este projeto utiliza Next.js, Tailwind CSS e Storybook para a criação de uma biblioteca de componentes reutilizáveis e escaláveis. A estrutura de design é baseada em design tokens, que ajudam a manter um design system consistente em toda a aplicação.

### Objetivos do Projeto

Implementar os princípios do Atomic Design.
Utilizar design tokens para manter consistência no design system.
Agilizar o desenvolvimento e estilização com Tailwind CSS.
Criar componentes reutilizáveis com visualização e testes no Storybook.

### Principais Conceitos

#### Atomic Design

É uma metodologia para criar sistemas de design modulares e escaláveis. Ele organiza a interface em cinco níveis:

- Átomos: os elementos básicos e indivisíveis (ex: botões, inputs).
- Moléculas: combinações de átomos que formam blocos funcionais (ex: campos de formulário).
- Organismos: grupos de moléculas formando áreas mais complexas da UI (ex: cabeçalhos, rodapés).
- Templates: layouts que estruturam a interface e oferecem um guia para a aplicação dos componentes.
- Páginas: instâncias dos templates com conteúdo real.

#### Design Tokens

Design Tokens são as variáveis que definem o design system, como cores, fontes, espaçamentos e tamanhos. São configurados para garantir que todas as partes da aplicação sigam os mesmos padrões de design, aumentando a consistência visual.

#### Tailwind CSS

Utilizamos Tailwind CSS para agilizar a estilização dos componentes. Com sua abordagem de utility-first, é possível adicionar classes diretamente nos componentes para aplicar estilos de maneira rápida e consistente, seguindo o design system definido.

#### Storybook

Storybook permite visualizar e testar os componentes de forma isolada. Cada componente pode ter diferentes variações, o que facilita a documentação e o teste visual dos componentes antes de serem integrados na aplicação.
