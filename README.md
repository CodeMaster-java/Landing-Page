# Projetos Landing Pages 📚
Coleção de landing pages responsivas desenvolvidas para praticar UI, UX e organização de código front-end. Cada projeto incorpora boas práticas de acessibilidade, tipografia consistente e hierarquia visual clara.

## Índice
- [Visão Geral](#visão-geral)
- [Destaques do Design](#destaques-do-design)
- [Pré-visualizações](#pré-visualizações)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Guia Rápido](#guia-rápido)
- [Boas Práticas](#boas-práticas)
- [Contribuindo](#contribuindo)
  - [Contribuições Registradas](#contribuições-registradas)
- [Licença](#licença)

## Visão Geral
O repositório reúne diferentes estudos de landing pages com foco em experiências completas de autenticação, marketing e educação. A proposta é manter um código limpo, reutilizável e fácil de evoluir.

## Destaques do Design
- Componentes reutilizáveis com tokens de cor, tipografia e espaçamento definidos por variáveis CSS.
- Layouts modulados por grid flexível, otimizados para telas pequenas e grandes.
- Tratamento de estados de foco e redução de movimento para garantir acessibilidade.
- Conteúdo orientado à narrativa, com seções que favorecem conversões e clareza.

## Pré-visualizações
| Projeto | Descrição | Demonstração |
| --- | --- | --- |
| Autenticação Modular | Formulários de login e cadastro com copy refinada e microinterações consistentes. | [Acessar](https://gustx21.github.io/Landing-Page/projeto01/cubo01.html) |
| Cafeteria | Storytelling focado na jornada do cliente, cardápio e call-to-action para newsletter. | [Acessar](https://gustx21.github.io/Landing-Page/projeto02/cafe.html) |
| Plataforma Educacional | Apresentação institucional com métricas, depoimentos e FAQs interativos. | [Acessar](https://gustx21.github.io/Landing-Page/projeto03/umbrella.html) |

## Estrutura do Repositório
```
Landing-Page/
├── projeto01/
│   ├── assets/
│   │   ├── css/main.css
│   │   ├── fonts/
│   │   └── imagens/
│   ├── cubo01.html
│   └── cubo02.html
├── projeto02/
│   ├── assets/
│   │   ├── css/main.css
│   │   ├── imagens/
│   │   └── video/
│   └── cafe.html
├── projeto03/
│   ├── assets/
│   │   ├── css/main.css
│   │   ├── fonts/
│   │   └── imagens/
│   └── umbrella.html
└── README.md
```

## Guia Rápido
1. Clone o repositório: `git clone https://github.com/<usuario>/Landing-Page.git`
2. Acesse a pasta: `cd Landing-Page`
3. Abra qualquer projeto no navegador usando a extensão Live Server ou servindo os arquivos com `python -m http.server`
4. Ajuste as URLs das demonstrações hospedadas conforme necessário para o seu fork.

## Boas Práticas
- Priorize HTML semântico para melhorar SEO, acessibilidade e manutenção.
- Utilize componentes e variáveis existentes antes de criar novos estilos.
- Valide contraste de cores e leiaut em diferentes resoluções.
- Otimize imagens antes de adicioná-las às pastas de assets.

## Contribuindo
Contribuições são bem-vindas! Abra uma issue com a proposta ou envie um pull request seguindo o fluxo:
1. Crie um fork e uma branch dedicada: `git checkout -b feature/seu-recurso`
2. Documente alterações relevantes neste README ou em comentários de commit.
3. Garanta que os assets estejam organizados em `assets/css`, `assets/imagens`, `assets/video` e `assets/fonts` quando aplicável.

### Contribuições Registradas
- [projeto01/cubo01.html](projeto01/cubo01.html) e [projeto01/cubo02.html](projeto01/cubo02.html): reformulação completa da experiência de autenticação com layout responsivo, componentes reutilizáveis e textos acessíveis.
- [projeto01/assets/css/main.css](projeto01/assets/css/main.css): criação de sistema de design baseado em variáveis, tratamento de foco e suporte a prefers-reduced-motion.
- [projeto02/cafe.html](projeto02/cafe.html) e [projeto02/assets/css/main.css](projeto02/assets/css/main.css): novo storytelling para a cafeteria, grids fluidos e formulário de newsletter com reforço de acessibilidade.
- [projeto03/umbrella.html](projeto03/umbrella.html) e [projeto03/assets/css/main.css](projeto03/assets/css/main.css): navegação atualizada, seções informativas estruturadas e estilos tipográficos refinados.
- Organização dos diretórios de cada projeto em pastas assets dedicadas, com atualização dos caminhos para imagens, fontes e vídeos.

## Colaboradores
- Code Master — [GitHub](https://github.com/CodeMaster-java)

## Licença
Este projeto está sob a [Licença MIT](LICENSE). Sinta-se à vontade para usar, adaptar e compartilhar, desde que atribua os créditos apropriados.
