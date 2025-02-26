
## 1. Organização e navegação compreensíveis

Organize os elementos da tela de forma que suas relações sejam compreensíveis tanto visualmente quanto por meio de tecnologias assistivas, garantindo que a sequência lógica do conteúdo seja mantida em todos os tamanhos de tela. Além disso, assegure que os elementos focáveis sigam uma ordem coerente, respeitando a hierarquia do conteúdo e proporcionando uma navegação previsível e acessível.

### Informações e relações  

Cada elemento deve estar organizado de forma clara, tanto na aparência quanto no código, para que a relação entre eles seja fácil de entender. Isso facilita a navegação para quem usa tecnologias assistivas, para quem navega apenas com o teclado e para quem acessa o site em dispositivos de diferentes tamanhos de tela.

### Critérios de Sucesso

Os elementos da interface devem ser organizados de maneira hierárquica, lógica e coerente, tanto para quem vê quanto para quem ouve. A navegação mantém a sequência lógica em diferentes tamanhos de tela, sendo responsiva e funcional para se movimentar por teclado.

### Objetivo

Assegurar que todas as pessoas usuárias, independentemente do dispositivo ou da tecnologia utilizada, consigam acessar, compreender e navegar pelo conteúdo de forma eficiente, intuitiva e sequencial.

### O que fazer

Organize os elementos de forma hierárquica, utilizando tags apropriadas no html; certifique-se de que todos os elementos focáveis sigam uma sequência previsível e intuitiva, respeitando a estrutura e o fluxo do conteúdo; realize testes com tecnologias assistivas e diferentes dispositivos para garantir a qualidade.

-   [Conheça a diretriz WCAG 2.2 - Informações e relações (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships)
-   [Conheça a diretriz WCAG 2.2 - Sequência com significado (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/meaningful-sequence)
-   [Conheça a diretriz WCAG 2.2 - Ordem do foco (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/focus-order)
-   [Conheça a diretriz WCAG 2.2 - Em foco (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/on-focus)

---
## 2. Título

Certifique-se de que cada página tenha um título claro e descritivo que indique sua finalidade.
### Título coerente

Cada página deve ter um título único e relevante que ajude os usuários a identificarem rapidamente seu conteúdo ou função. Isso é especialmente importante para quem utiliza tecnologias assistivas, pois facilita a navegação e a compreensão da página sem depender da análise de seu conteúdo visual.

### Critérios de Sucesso

As páginas web têm títulos que descrevem o tópico ou a finalidade.

### Objetivo

Garantir que cada página tenha um título informativo, que comunique claramente seu propósito, facilitando a navegação para todos os usuários, inclusive aqueles que utilizam tecnologias assistivas.

### O que fazer

Garanta que cada página tenha um título único que reflete seu conteúdo de forma precisa e objetiva. O título deve ser curto e direto, informando o propósito da página sem ambiguidade. Além disso, é importante evitar termos genéricos ou irrelevantes, garantindo que os usuários, inclusive aqueles que utilizam tecnologias assistivas, possam identificar rapidamente a função da página e navegar com facilidade.

-   [Conheça a diretriz WCAG 2.2 - Página com título (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/page-titled)

---
## 3. Não sensorial

Forneça instruções claras, que não dependam apenas de características sensoriais, como formato, cor ou posição dos elementos na interface – por exemplo, ''clique no botão inscreva-se” em vez de ''clique no botão abaixo''.

### Instruções não sensoriais

“Instruções Baseadas em Ações”, “Identificação por Nome” e “Contexto e Função” são instruções diretas e focam na ação a ser tomada, permitindo que todos os usuários, independentemente de suas habilidades sensoriais, compreendam o que devem fazer.

### Critérios de Sucesso

Quando a sequência em que o conteúdo é apresentado afeta o seu significado, é possível determinar programaticamente uma sequência de leitura correta. Assim as instruções fornecidas para a compreensão e utilização de conteúdos não devem se basear apenas nas caraterísticas sensoriais dos componentes, como a forma, a cor, o tamanho, a localização visual, a orientação ou o som.

### Objetivo

Garantir a acessibilidade e a usabilidade da interface para todos os usuários, independentemente de suas habilidades sensoriais.

### O que fazer

Utilize instruções claras e específicas para que qualquer usuário consiga entender, independentemente de cor ou posição.

-   [Conheça a diretriz WCAG 2.2 - Sequência com Significado (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/meaningful-sequence)
-   [Conheça a diretriz WCAG 2.2 - Características Sensoriais (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/sensory-characteristics)
-   [Conheça a diretriz WCAG 2.2 - Uso de Cores (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color)

---
## 4. Conteúdo visual

Forneça descrições textuais adequadas (atributos ALT) para todas as imagens, ícones e CAPTCHAs relevantes, explicando suas funções e seu conteúdo de forma clara e precisa. Certifique-se de que essas descrições sejam lidas pelas tecnologias assistivas, evitando informações irrelevantes ou redundantes.

### Alternativas em texto  

Conteúdos não textuais relevantes, como imagens, ícones e CAPTCHAs, devem possuir uma descrição.

### Critérios de Sucesso

Todos os elementos não textuais relevantes possuem descrição que explica o que eles são, o que comunicam, e se possuem interação. Por exemplo, um leitor de tela seleciona um botão e lê “Botão: Gerar relatório. Clique duas vezes para ativar”. As descrições devem ser lidas corretamente pelos leitores de tela, independente do sistema operacional e do navegador utilizado.

### Objetivo

Disponibilizar as informações não textuais para mais pessoas.

### O que fazer

Criar uma alternativa de texto para o conteúdo visual e auditivo.

   - [Conheça a diretriz WCAG 2.2 - Conteúdo não textual (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/non-text-content)
   
---
## 5. Consistência na interação

Garanta que a interação do usuário com campos e cabeçalhos não altere o contexto sem confirmação, mantendo consistência e previsibilidade. Use rótulos claros e forneça instruções, se necessário, para facilitar o preenchimento de formulários.
### Interação consistente

A interface deve manter um comportamento previsível em todas as ações, sem mudanças inesperadas de contexto. Rótulos claros e instruções devem ser usados para guiar o usuário, garantindo uma experiência de navegação estável e acessível, especialmente para aqueles que utilizam tecnologias assistivas.

### Critérios de Sucesso

Alterar a definição de um componente de interface de usuário não provoca automaticamente uma mudança de contexto, a menos que o usuário tenha sido avisado sobre esse comportamento antes de utilizar o componente.  Os cabeçalhos e os rótulos descrevem o tópico ou a finalidade.

### Objetivo

Garantir uma experiência previsível ao interagir com o site, evitando confusão ou frustração. Isso é especialmente importante para pessoas com deficiência ou usuárias de tecnologias assistivas, pois a consistência e a clareza nas interações facilitam a navegação e o preenchimento de formulários, além de reduzir erros.

### O que fazer

Não deixe os elementos do site mudarem de lugar ou aparecerem sozinhas quando o usuário estiver preenchendo campos ou formulários, por exemplo. Use palavras simples e claras nos botões e campos e, se necessário, inclua uma explicação. Mantenha as ações em todas as partes do site. Teste com usuários reais, especialmente aquelas que precisam de tecnologias assistivas ou algum recurso extra para navegar.

-   [Conheça a diretriz WCAG 2.2- Em Entrada (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/on-input)
-   [Conheça a diretriz WCAG 2.2- Rótulos e instruções (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/labels-or-instructions)
-   [Conheça a diretriz WCAG 2.2 - Cabeçalhos e Rótulos (Nível AA)](https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels)

---
## 6. Minimização de redundância

Evite solicitar informações repetidas em formulários de várias etapas, a menos que seja absolutamente necessário (por exemplo, para a confirmação de senha).

### Alternativas de preenchimento automático  

Informações já fornecidas em processos de múltiplas etapas devem ser preenchidas automaticamente ou disponibilizadas para o usuário selecionar, evitando a necessidade de reinserção.

### Critérios de Sucesso

As informações previamente inseridas ou fornecidas pelo usuário, que precisam ser inseridas novamente no mesmo processo, devem ser preenchidas automaticamente ou disponibilizadas para o usuário selecionar. Porém, há exceções quando é essencial incluir as informações novamente, como para garantir a segurança do conteúdo ou quando as informações anteriores não são mais válidas.

### Objetivo

Facilitar a conclusão de processos de múltiplas etapas, reduzindo a fadiga cognitiva.

### O que fazer

Evite pedir informações que o usuário já forneceu durante o mesmo processo.

-   [Conheça a diretriz WCAG 2.2 - Entrada Reduntante (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry)

---
## 7. Clareza na exposição de erros

Certifique-se de que os erros sejam comunicados de forma clara, utilizando múltiplos recursos, como mudança de cor, alteração de formato, alerta sonoro ou mensagem de texto. Além disso, destaque onde o erro ocorreu e forneça um exemplo prático de como ele pode ser corrigido.

### Identificação e sugestão de erros  

Quando ocorre um erro, é importante deixar claro o que está errado e como o problema pode ser resolvido. Isso é importante para todos os usuários, em especial para quem possui deficiência visual e cognitiva, pois facilita a compreensão do erro e sua resolução.

### Critérios de Sucesso

Se um erro for detectado automaticamente, o item com problema será identificado e explicado em texto para o usuário. Se houver sugestões para corrigir o erro, elas deverão aparecer para o usuário, a menos que isso afete a segurança ou o objetivo do conteúdo.

### Objetivo

Garantir que o usuário saiba que existe um erro e o que está errado, e que, além disso, receba sugestões de resolução.

### O que fazer

Forneça avisos claros de erro e sugira maneiras de corrigi-los. Para garantir a clareza, aplique recursos como mudança de cor, alteração de formato, alerta sonoro ou mensagem de texto.

-   [Conheça a diretriz WCAG 2.2 - Identificação de Erro (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/error-identification)
-   [Conheça a diretriz WCAG 2.2 - Sugestão de erro (Nível AA)](https://www.w3.org/WAI/WCAG22/Understanding/error-suggestion)

---
## 8. Descrição de links

Cada link deve ter um texto que descreva sua função ou estar em um contexto que explique sua finalidade.
### Links bem descritos  

Deve-se deixar claro para o usuário o que vai acontecer quando ele clicar em um link. Em vez de textos vagos, como “clique aqui”, use palavras que expliquem o destino ou a ação que o link vai realizar, como “baixe o relatório”, “veja mais sobre nosso time” ou “acesse a página de contato”.

### Critérios de Sucesso

Cada link deve mostrar claramente para onde leva, sozinho ou com o texto em volta, exceto quando o propósito do link for ambíguo para os usuários em geral.

### Objetivo

Garantir que os usuários compreendam o que acontecerá ao clicar em um link, melhorando tanto a usabilidade quanto a acessibilidade de um site. Com uma descrição clara, os usuários conseguem navegar de forma mais fluida e previsível, sem surpresas ou confusões sobre o destino ou a função do link.

### O que fazer

Use links que digam exatamente o que vai acontecer, como “veja nossos serviços”. Se o link for curto, explique ao redor o que ele faz. Teste o site com leitores de tela para garantir que esteja compreensível e certifique-se de que os links sejam simples e claros para qualquer pessoa.

-   [Conheça a diretriz WCAG 2.2 - Finalidade do Link (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-in-context.html)

---
## 9. Controle flexível de gestos e alternativas de interação

Garanta que os usuários possam cancelar ou desativar ações acidentais originadas por gestos e ofereça alternativas de controle que não dependam de movimentos do dispositivo. Todas as funções que requerem gestos táteis devem disponibilizar opções adicionais de interação, como teclas de atalho, botões clicáveis ou comandos acionados por um único toque, prevenindo erros e oferecendo flexibilidade no uso.

### Implementação de Mecanismos de Correção  

Para funções que são frequentemente ativadas por engano através de gestos, deve-se fornecer um mecanismo simples de desfazer ou confirmar antes de prosseguir com a ação. Isso é particularmente importante em aplicativos que lidam com dados sensíveis ou operações irreversíveis.

### Critérios de Sucesso

Funcionalidades que requerem gestos complexos devem ser simples de usar com apenas um clique. Movimentos do dispositivo ou do usuário para comandar funções devem ter alternativas fáceis na interface, e deve ser possível desativar essas respostas para evitar erros. Funções ativadas com um clique devem permitir cancelar ou corrigir a ação facilmente, exceto quando o clique imediato for essencial.

### Objetivo

Minimizar frustrações e erros operacionais, garantindo que todas as interações possam ser controladas de forma segura e acessível.

### O que fazer

Implemente confirmações ou opções de desfazer para ações críticas que podem ser acionadas por gestos. Garanta que essas opções sejam comunicadas claramente e fáceis de acessar.

-   [Conheça a diretriz WCAG 2.2 - Gestos de acionamento (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/pointer-gestures)
-   [Conheça a diretriz WCAG 2.2 - Cancelamento de acionamento (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/pointer-cancellation)
-   [Conheça a diretriz WCAG 2.2 - Atuação por movimento (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/motion-actuation)
---
## 10. Navegação via teclado

Garanta que todas as funcionalidades também possam ser usadas por meio do teclado, permitindo navegação simples e contínua por todos os elementos interativos.
### Implementação de Acessibilidade de Navegação por Teclado

Para garantir uma experiência fluida de navegação por teclado, os elementos interativos devem ser acessíveis em uma ordem lógica e intuitiva.

### Critérios de Sucesso

Cada elemento interativo deve ser acessível pelo teclado e funcionar corretamente com teclas como Tab, Enter e Espaço.

### Objetivo

Facilitar a navegação independente pelo site ou aplicativo por usuários que não utilizam mouse. Essas pessoas incluem aquelas com deficiência motora, visual ou cognitiva, que navegam pelo teclado ou por tecnologias assistivas, como leitores de tela e teclados adaptados.

### O que fazer

Certifique-se de que a ordem do foco do teclado siga uma sequência lógica, que corresponda ao fluxo visual da interface. Evite que componentes como pop-ups ou menus dropdown capturem o foco do teclado fora dessa sequência lógica.

-   [Conheça a diretriz WCAG 2.2 - Teclado (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/keyboard)
-   [Conheça a diretriz WCAG 2.2 - Sem bloqueio de teclado (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/no-keyboard-trap)
-   [Conheça a diretriz WCAG 2.2 - Atalhos de teclado por caractere (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/character-key-shortcuts)

---
## 11. Ignorar repetição

Ofereça uma alternativa para que os usuários de teclado possam pular conteúdos repetidos, como menus de navegação, e acessar o conteúdo principal mais rapidamente.
### Ignorar repetições

Uma prática importante para melhorar a usabilidade do site para usuários de teclado é fornecer a opção de ignorar blocos repetitivos, como menus de navegação, cabeçalhos ou rodapés, permitindo que eles acessem diretamente o conteúdo principal da página. Isso pode ser feito através da implementação, no início da página, de um link oculto que se torna visível ao navegar com a tecla Tab.

### Critérios de Sucesso

O site deve permitir que os usuários de teclado, ao apertarem a tecla Tab, vejam a opção de “Pular para o conteúdo”. Este link deve ser acessível logo nos primeiros passos da navegação, sem a necessidade de percorrer elementos repetidos, e levar diretamente ao conteúdo principal.

### Objetivo

Reduzir o tempo e o esforço necessários para acessar o conteúdo relevante, promovendo uma navegação mais rápida e eficiente, especialmente para usuários que dependem do teclado ou de tecnologias assistivas. Essa funcionalidade melhora a acessibilidade e facilita a navegação para todos, eliminando a frustração de passar por menus ou cabeçalhos repetidos em cada página.

### O que fazer

Desenvolvedores devem implementar um skip link que se torna visível ao receber foco, geralmente no topo da página. Esse link deve ser bem descrito, como “Pular para o conteúdo principal”, e testado em navegadores e leitores de tela para garantir que funcione adequadamente. Além disso, deve-se assegurar que ele seja facilmente acessível logo no início da navegação com o teclado, para não exigir a interação com blocos repetidos.

-  [Conheça a diretriz WCAG 2.2 – Ignorar Blocos Repetidos (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks)

---
## 12. Definição de tempo/movimentos

Permita que os usuários desativem, ajustem ou ampliem qualquer limite de tempo no aplicativo ou site. Também ofereça controle sobre qualquer movimento automático, piscar ou rolar da tela, com a opção de pausar, parar ou ocultar essas ações.
### Atributos acessíveis

Certifique-se de que os componentes interativos, como animações automáticas ou contadores de tempo, incluam controles acessíveis para que os usuários possam pausar, parar ou ajustar essas ações. Para limites de tempo, ofereça a opção de estender ou desativar o tempo. Isso deve ser feito usando atributos e controles que possam ser detectados por tecnologias assistivas e facilmente acionados por pessoas com deficiência.

### Critérios de Sucesso

Elementos que piscam ou se movem automaticamente devem ter controles para pausar ou parar o movimento. Isso facilita a leitura e reduz desconforto para pessoas com deficiência visual ou dificuldades de atenção. Um botão de pausa é essencial para tornar o conteúdo acessível.  
  
Sites com limite de tempo devem permitir desativar, ajustar ou estender o período antes de desconectar o usuário. Isso ajuda quem precisa de mais tempo, como pessoas com deficiência. Um aviso de “Estender Tempo” antes do logout garante continuidade das tarefas.

### Objetivo

Permitir que todos controlem o tempo e os movimentos no site, tornando a navegação mais fácil e confortável para pessoas com diferentes necessidades ou dificuldades, além de melhorar o uso em situações adversas de navegação.

### O que fazer?

Adicione botões visíveis para pausar ou parar movimentos, como em carrosséis ou animações, ajudando os usuários a evitar desconforto.  
Ofereça opções para desativar ou estender o tempo, garantindo que todos possam completar tarefas sem pressa ou frustração.  
Certifique-se de que controles funcionem com leitores de tela e comandos de voz, garantindo acessibilidade para todos os usuários.

-   [Conheça a diretriz WCAG 2.2 - Tempo ajustável (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/timing-adjustable.html)

-  [Conheça a diretriz WCAG 2.2 - Colocar em pausa, parar, ocultar (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide.html)

---
## 13. Nomes e rótulos acessíveis e consistentes

Certifique-se de que todos os componentes da interface do usuário, como formulários, links e elementos gerados por scripts, possuam atributos acessíveis (nome, função e valor) e que o nome dos controles corresponda aos seus rótulos visíveis, facilitando a interpretação por tecnologias assistivas e a interação por voz.

### Atributos acessíveis

Cada componente da interface do usuário, como botões, campos de formulário, links e elementos gerados por scripts, deve conter atributos claros e acessíveis, como nome, função e valor. Isso é essencial para garantir que as tecnologias assistivas, como leitores de tela e sistemas de comando por voz, consigam interpretar e comunicar essas informações corretamente aos usuários. Além disso, os nomes dos controles interativos devem ser idênticos aos rótulos visíveis na interface, evitando confusão na navegação e na ativação de comandos por voz.

### Critérios de Sucesso

Os componentes interativos têm nomes, funções e valores definidos corretamente. O nome que as tecnologias assistivas leem é o mesmo que o rótulo visível, e os elementos da interface funcionam de forma consistente. Assim, os usuários conseguem navegar e usar a interface de forma fácil e previsível, independentemente do dispositivo ou da tecnologia que estão usando.

### Objetivo

Assegurar que todas as pessoas usuárias, incluindo aquelas que utilizam leitores de tela ou navegação por voz, possam interagir com os componentes da interface sem barreiras, garantindo que cada elemento possua os atributos corretos e que a navegação seja intuitiva.

### O que fazer

Configurar corretamente os atributos aria-label, role e aria-valuenow para fornecer informações completas sobre os componentes interativos. Também realize testes com leitores de tela e sistemas de navegação por voz para validar que os controles da interface estejam sendo corretamente identificados e acionados.

-   [Conheça a diretriz WCAG 4.1.2 Nome, função, valor (Nível A)](https://www.w3.org/WAI/WCAG21/Understanding/name-role-value.html)
-   [Conheça a diretriz WCAG 2.5.3 Rótulo no Nome acessível (Nível A)](https://www.w3.org/WAI/WCAG21/Understanding/label-in-name.html)
---
## 14. Transcrições

Forneça transcrições textuais para todo conteúdo de áudio e legendas e/ou audiodescrições para todo conteúdo de vídeo. Descreva o que acontece visualmente no vídeo para que todos os usuários possam entender o conteúdo.
### Transcrições Descritivas

Fornecer alternativas a conteúdos audiovisuais, principalmente de forma descritiva, é de extrema importância para torná-los acessíveis a todas as pessoas.

### Critérios de Sucesso

Para conteúdo em áudio, pode ser disponibilizada uma transcrição completa, permitindo que pessoas com deficiência auditiva leiam todas as informações e acessem o conteúdo de forma equivalente.

Para vídeos sem som, pode-se oferecer uma alternativa em áudio que descreve o que acontece na tela. Imagine um vídeo educativo que mostra apenas imagens de um experimento. Para torná-lo acessível, pode ser adicionada uma faixa de áudio que descreva o experimento e explique cada etapa. Da mesma forma, uma descrição em áudio é incluída em todos os vídeos gravados para explicar o que está acontecendo nas imagens. Por exemplo, um documentário que mostra cenas de natureza sem narração. Para que pessoas com deficiência visual entendam o que aparece na tela, é incluída uma descrição em áudio que explica as ações e cenários do vídeo, como "Um leão caminha lentamente pela savana".

Legendas são sempre incluídas em vídeos com áudio gravado, a menos que o vídeo seja uma versão alternativa de um conteúdo em texto e isso esteja claramente indicado. Pense em uma palestra gravada on-line. Para torná-la acessível, são adicionadas legendas que transcrevem tudo o que é dito, permitindo que pessoas com deficiência auditiva acompanhem o conteúdo. Se esse vídeo for apenas uma versão alternativa de um artigo escrito (já disponível para leitura), e isso estiver claramente indicado, as legendas não são obrigatórias.

### Objetivo

Garantir a compreensão do conteúdo de áudio, vídeo e audiovisual por mais pessoas ao gerar legendas e descrições de áudio.

### O que fazer?

Forneça uma alternativa quando o conteúdo for perceptível com apenas um sentido: texto sincronizado para conteúdo de áudio; descrição do conteúdo visual dos vídeos; e descrição falada sincronizada do conteúdo visual dos vídeos.

-   [Conheça a diretriz WCAG 2.2 - Apenas Áudio e Apenas Vídeo (Pré-gravado) (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/audio-only-and-video-only-prerecorded.html)  
    
-   [Conheça a diretriz WCAG 2.2 - Legendas (Pré-gravadas) (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded.html)
-   [Conheça a diretriz WCAG 2.2 - Audiodescrição ou Mídia Alternativa (Pré-gravada) (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-or-media-alternative-prerecorded.html)
-   [Conheça a diretriz WCAG 2.2 - Audiodescrição (Pré-gravada) (Nível AA)](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-prerecorded.html)
---
## 15. Formatação de ajuda

Garanta que a opção de ajuda tenha o mesmo formato em todas as telas, incluindo alternativas de contato humano e sistemas automatizados.

### Consistência na ajuda  

Para facilitar a navegação, a ajuda deve seguir um padrão em todas as páginas. Por exemplo, se o botão de ajuda fica no canto inferior direito em uma página, deve estar no mesmo lugar em todas as outras páginas do site. Além disso, as instruções e a forma como a ajuda funciona devem ser consistentes. Assim, os usuários sabem exatamente onde encontrar ajuda e como ela funciona, independentemente da página em que estão.

### Critérios de Sucesso

Se uma página da web contiver qualquer um dos seguintes mecanismos de ajuda e esses mecanismos forem repetidos em várias páginas dentro de um conjunto, eles ocorrerão na mesma ordem em relação a outro conteúdo da página, a menos que uma alteração seja iniciada pelo usuário: detalhes de contato humano, mecanismo de contato humano, opção de autoajuda ou um mecanismo de contato totalmente automatizado.

### Objetivo

Garantir que todas as pessoas, independentemente de habilidades ou preferências, possam acessar a ajuda de forma fácil. Isso se aplica especialmente para usuários com deficiência ou limitações cognitivas ou tecnológicas, que precisam de consistência para navegar com mais facilidade.

### O que fazer

Mantenha os elementos de ajuda (links, botões, ícones) consistentes em termos de localização, design e funcionalidade em todas as páginas da interface. Garanta que as opções de ajuda incluam formas automatizadas (como chatbots) e formas de contato humano (como e-mail ou telefone) para cobrir as preferências e necessidades de todos os usuários.

-   [Conheça a diretriz WCAG 2.2 - Ajuda Consistente (Nível A)](https://www.w3.org/WAI/WCAG22/Understanding/consistent-help.html)
## 16. Contraste visual adequado

Garanta que o texto e as imagens sejam legíveis, assegurando contraste adequado com o fundo. O ideal é oferecer opções para personalizar o contraste, permitindo que o fundo e o texto sejam claros ou escuros, conforme a necessidade do usuário.
### Contraste ajustável  

Para que o texto e as imagens sejam fáceis de ler, é importante ajustar o contraste entre eles e o fundo.

### Critérios de Sucesso

O texto e as imagens de texto devem ter uma proporção de contraste mínima de 4.5:1, com exceção para textos grandes (3:1), texto decorativo e logotipos.

### Objetivo

Garantir que o texto seja legível por pessoas com visão moderadamente baixa ou com dificuldades de percepção de contraste, sem o uso de tecnologias assistivas.

### O que fazer

Fornecer contraste suficiente entre o texto e o fundo, garantindo uma proporção de contraste de 4.5:1 para textos normais e 3:1 para textos grandes.

-   [Conheça a diretriz WCAG 1.4.3 Contraste (Mínimo) (Nível AA)](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)