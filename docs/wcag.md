# Diretrizes WCAG 2.2 e Heurísticas de Nielsen

Como usar a WCAG e as Heurísticas de Nielsen no desenvolvimento de um projeto.

## Acessibilidade e Usabilidade Web

A WCAG (Web Content Accessibility Guidelines) é um conjunto de diretrizes criado para tornar a web mais acessível para todas as pessoas, incluindo aquelas com deficiências. Essas diretrizes ajudam desenvolvedores e designers a criar sites e aplicativos que podem ser usados por pessoas com dificuldades visuais, auditivas, motoras ou cognitivas.

Seguir a WCAG melhora a experiência do usuário, garantindo que o conteúdo seja perceptível, operável, compreensível e robusto. Isso significa, por exemplo, usar descrições alternativas para imagens, permitir navegação por teclado e oferecer legendas para vídeos. Além de ser essencial para inclusão digital, a acessibilidade também beneficia empresas e instituições ao ampliar seu alcance e cumprir legislações sobre acessibilidade.

Adotar a WCAG não é apenas uma boa prática, mas um passo fundamental para tornar a web mais justa e acessível para todos.

- [WCAG 2.2 em português](https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/)

## Níveis WCAG

A WCAG estabelece três níveis de conformidade para garantir a acessibilidade de sites e conteúdos digitais: A, AA e AAA. Cada nível abrange um conjunto de critérios a serem atendidos, permitindo que o conteúdo seja acessível a um público mais amplo, independentemente de suas necessidades.

### Nível A (Essencial) – Acessibilidade Mínima

O nível A representa os requisitos fundamentais para tornar um site acessível. Embora seja a base mínima para garantir acessibilidade, ele não assegura a melhor experiência de uso. Exemplos de critérios do nível A incluem:

- **Texto Alternativo:** Todas as imagens devem ter uma descrição (atributo alt) para leitores de tela.
- **Navegação por Teclado:** O site deve ser totalmente navegável sem o uso do mouse.
- **Evitar Conteúdo Piscante:** Elementos que piscam não devem ultrapassar 3 flashes por segundo para evitar crises epilépticas.

### Nível AA (Recomendado) – Acessibilidade Refinada

O nível AA amplia os critérios do nível A, assegurando uma experiência mais acessível e ajustada às necessidades dos usuários. Este nível é frequentemente exigido por regulamentações de acessibilidade em vários países. Exemplos incluem:

- **Contraste Adequado:** O contraste entre o texto e o fundo deve ser de pelo menos 4.5:1, facilitando a leitura.
- **Legendas em Vídeos:** Todo conteúdo em vídeo deve possuir legendas para usuários surdos ou com deficiência auditiva.
- **Conteúdo Reajustável:** O site deve ser responsivo, permitindo ajustes sem comprometer a funcionalidade.

### Nível AAA (Avançado) – Acessibilidade Completa

O nível AAA é o mais rigoroso, focando em melhorias adicionais para garantir a máxima acessibilidade. Embora não seja obrigatório na maioria dos casos, é altamente recomendado para sites que buscam oferecer uma experiência inclusiva para todos. Exemplos incluem:

- **Contraste Maior:** O contraste entre texto e fundo deve ser de pelo menos 7:1.
- **Audiodescrição Detalhada:** Vídeos devem incluir descrições narradas para pessoas cegas.
- **Sem Limite de Tempo:** O site deve permitir interação sem imposição de restrições de tempo.

### Escolhendo o Nível de Acessibilidade

Existem diferentes opções para implementar os níveis de conformidade da WCAG:

- **Nível A:** Essencial, mas pode não garantir acessibilidade completa.
- **Nível AA:** O mais recomendado, sendo exigido por muitas legislações de acessibilidade.
- **Nível AAA:** Ideal para máxima inclusão, embora seja desafiador de implementar por completo.

O objetivo principal é garantir pelo menos o nível AA, visando uma experiência mais inclusiva para o maior número de usuários possível. 🌍

## Princípios WCAG

A WCAG divide os temas em quatro princípios, cada um cobre uma área de conteúdo ao desenvolvimento.

### Princípio 1: Perceptível

Todos os usuários devem conseguir perceber o conteúdo, independente de suas limitações:

- Forneça alternativas em texto para conteúdo não textual (imagens, vídeos)
- Permita que o conteúdo seja apresentado de diferentes formas
- Torne fácil para os usuários ver e ouvir o conteúdo

### Princípio 2: Operável

A interface deve ser navegável e utilizável por todos:

- Torne todas as funcionalidades acessíveis via teclado
- Dê tempo suficiente para leitura e uso
- Ajude os usuários a navegar e encontrar conteúdo

### Princípio 3: Compreensível

O conteúdo e operação devem ser fáceis de entender:

- Use linguagem clara e simples
- Faça as páginas funcionarem de maneira previsível
- Ajude os usuários a evitar e corrigir erros

### Princípio 4: Robusto

O conteúdo deve funcionar bem em diferentes tecnologias:

- Seja compatível com tecnologias assistivas
- Mantenha o código limpo e bem estruturado

## Heurísticas de Nielsen

As **Heurísticas de Nielsen** são princípios essenciais para avaliar a usabilidade de interfaces digitais. Criadas por **Jakob Nielsen**, essas heurísticas ajudam designers e desenvolvedores a identificar problemas de usabilidade e melhorar a experiência do usuário. A seguir, veremos exemplos práticos de como essas heurísticas se aplicam no design de interfaces.

### As 10 Heurísticas de Usabilidade de Nielsen com Exemplos

Abaixo estão as 10 heurísticas de Nielsen com exemplos para ilustrar como elas funcionam na prática:

1. **Visibilidade do estado do sistema:** Exemplo: Quando você clica em um botão de "carregar mais" em uma página web, um indicador de carregamento aparece, mostrando ao usuário que a ação está sendo processada.
2. **Correspondência entre o sistema e o mundo real:** Exemplo: Um aplicativo de finanças usa ícones como "carteira" ou "fatura" para representar conceitos conhecidos, como a ideia de dinheiro ou contas a pagar, facilitando a compreensão do usuário.
3. **Controle e liberdade do usuário:** Exemplo: Em um formulário de cadastro, o usuário pode corrigir qualquer erro antes de finalizar, como editar um campo de email incorreto, sem ter que recomeçar o processo do início.
4. **Consistência e padrões:** Exemplo: Em um site de e-commerce, o botão "adicionar ao carrinho" sempre tem a mesma cor e posição em todas as páginas de produtos, criando uma experiência previsível e consistente para o usuário.
5. **Prevenção de erros:** Exemplo: Em um sistema de upload de arquivos, o aplicativo só permite que arquivos de tipos suportados sejam selecionados, evitando o erro de tentar fazer upload de um arquivo incompatível.
6. **Reconhecimento ao invés de recordação:** Exemplo: Um aplicativo de mensagens oferece sugestões de palavras enquanto o usuário digita, em vez de exigir que ele se lembre de palavras ou frases inteiras, tornando a experiência mais fluida e intuitiva.
7. **Flexibilidade e eficiência de uso:** Exemplo: Um editor de texto oferece atalhos de teclado para usuários experientes, permitindo que eles editem documentos mais rapidamente, enquanto ainda mantém uma interface simples e acessível para novatos.
8. **Estética e design minimalista:** Exemplo: Um site de receitas mantém uma interface limpa, sem excesso de informações, destacando apenas as receitas e seus ingredientes, o que facilita a navegação e evita sobrecarga de informações.
9. **Ajudar os usuários a reconhecer, diagnosticar e recuperar de erros:** Exemplo: Quando um usuário tenta fazer login com uma senha errada, o sistema mostra uma mensagem clara, como "Senha incorreta. Tente novamente", em vez de uma mensagem genérica de erro.
10. **Ajuda e documentação:** Exemplo: Um aplicativo de edição de fotos oferece um tutorial interativo na primeira vez que o usuário o abre, explicando os principais recursos e como usá-los, além de um centro de ajuda acessível sempre que necessário.

### Importância das Heurísticas de Nielsen

As heurísticas de Nielsen são fundamentais para garantir que uma interface seja fácil de usar e eficiente. Elas ajudam a identificar e corrigir problemas de usabilidade antes que eles afetem a experiência do usuário. Por exemplo, se um site não tiver feedback claro de carregamento ao clicar em um botão, os usuários podem ficar confusos e pensar que o site não está funcionando.

Essas heurísticas também evitam que o design se torne confuso ou sobrecarregado. Por exemplo, um site de e-commerce com muitos pop-ups e banners pode distrair os usuários e dificultar a navegação, mas ao seguir a heurística de "estética e design minimalista", o site pode ser mais agradável e focado no que realmente importa.

### Aplicação Prática

As heurísticas de Nielsen são aplicadas em auditorias de usabilidade, onde os especialistas revisam interfaces de acordo com esses princípios. Por exemplo, ao avaliar um aplicativo de mensagens, um especialista pode identificar problemas de "visibilidade do estado do sistema", como a falta de um indicador de envio de mensagem, e sugerir a adição de um ícone de carregamento para informar o usuário de que a mensagem está sendo enviada.

Em resumo, as heurísticas de Nielsen ajudam a criar interfaces digitais mais eficazes e agradáveis de usar. Elas fornecem uma base sólida para melhorar a usabilidade, garantir que o sistema seja intuitivo e prevenir erros que possam frustrar os usuários.