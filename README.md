<p align="center">
  <img src="https://github.com/user-attachments/assets/84743a21-b19e-42f0-ac32-3614f539d35a">


# GDD Chase Fugitive

Este repositório contém um template completo para um Documento de Design de Jogo (GDD) em português, estruturado pela equipe de TCC, Chase Fugitive, visando a demonstrar passo a passo do jogo. 


# Sumário

1. [Informações Gerais](#1-informações-gerais)<br>
    1.1. [Título do Jogo](#11-título-do-jogo)  
    1.2. [Plataforma](#12-plataforma)  
    1.3. [Gênero](#13-gênero)  
    1.4. [Público-Alvo](#14-público-alvo)  
    1.5. [Visão Geral do Jogo](#15-visão-geral-do-jogo)  

2. [Mecânicas de Jogo](#2-mecânicas-de-jogo)<br>
    2.1. [Regras Básicas](#21-regras-básicas)  
    2.2. [Controles](#22-controles)  
    2.3. [Objetivos e Metas](#23-objetivos-e-metas)  
    2.5. [Mecânicas de Interação](#25-mecânicas-de-interação)  
    2.6. [Sistemas de Progressão e Recompensas](#26-sistemas-de-progressão-e-recompensas)  
    2.7. [Inteligência Artificial (IA)](#27-inteligência-artificial-ia)  
    2.8. [Dinâmicas de Jogo](#28-dinâmicas-de-jogo)  
    2.9. [Economia do Jogo](#29-economia-do-jogo)  

3. [Narrativa](#3-narrativa)<br>
    3.1. [História Principal](#31-história-principal)  
    3.2. [Personagens](#32-personagens)  
    3.3. [Cenários](#33-cenários)  
    3.4. [Missões e Quests](#34-missões-e-quests)  
    3.5. [Roteiro e Diálogos](#35-roteiro-e-diálogos)  

4. [Design de Níveis](#4-design-de-níveis)<br>
    4.1. [Estrutura dos Níveis](#41-estrutura-dos-níveis)  
    4.2. [Mapas e Layouts](#42-mapas-e-layouts)  
    4.3. [Desafios e Puzzles](#43-desafios-e-puzzles)  
    4.4. [Fluxo dos Níveis](#44-fluxo-dos-níveis)  
    4.5. [Balanceamento de Dificuldade](#45-balanceamento-de-dificuldade)  

5. [Arte e Estilo Visual](#5-arte-e-estilo-visual)<br>
    5.1. [Estilo Artístico](#51-estilo-artístico)  
    5.2. [Personagens e Animações](#52-personagens-e-animações)  
    5.3. [Cenários e Ambientes](#53-cenários-e-ambientes)  
    5.4. [Interface do Usuário (UI)](#54-interface-do-usuário-ui)  
    5.5. [Paleta de Cores](#55-paleta-de-cores)  

6. [Áudio](#6-áudio)<br>
    6.1. [Trilha Sonora](#61-trilha-sonora)  
    6.2. [Efeitos Sonoros](#62-efeitos-sonoros)  
    6.4. [Ambiente Sonoro](#64-ambiente-sonoro)  

7. [Progresso e Salvamento](#7-progresso-e-salvamento)<br>
    7.1. [Sistema de Progressão](#71-sistema-de-progressão)  
    7.2. [Sistema de Salvamento](#72-sistema-de-salvamento)  

9. [Testes e Qualidade](#9-testes-e-qualidade)<br>
    9.1. [Testes de Jogo](#91-testes-de-jogo)  
    9.2. [Feedback dos Jogadores](#92-feedback-dos-jogadores)  

10. [Conclusão](#10-conclusão)<br>
    10.1. [Sumário](#101-sumário)  
    10.2. [Próximos Passos](#102-próximos-passos)  

## 1. Informações Gerais

### 1.1. Título do Jogo
**Chase Fugitive** 

### 1.2. Plataforma
*Disponivel no PC*

### 1.3. Gênero
*Jump 'n' Run e Aventura*

### 1.4. Público-Alvo
*Todos os publicos Crianças, Jovens,Adultos e Terceira Idade*

### 1.5. Visão Geral do Jogo
 *O jogador assume o papel de um agente de segurança, encarregado de proteger o museu mais prestigiado da cidade. Um ladrão de arte, invade o museu e rouba uma relíquia valiosa. Sua missão é persegui-lo por todo o museu, evitar armadilhas e obstáculos, e recuperar a relíquia roubada antes que seja tarde demais. O museu é repleto de salas temáticas, cada uma com seus próprios desafios e armadilhas únicas, como evitar obstáculos como seguranças patrulhando, câmeras de segurança, e até mesmo animais de estimação exóticos, além disso, eles também devem coletar itens especiais ao longo do caminho, como chaves para abrir portas trancadas ou dispositivos de rastreamento para localizar o ladrão. Pode ter um modo de desafio no qual os jogadores competem para completar níveis específicos o mais rápido possível. Também seria interessante incluir um modo multiplayer, no qual os jogadores podem enfrentar uns aos outros em corridas de obstáculos dentro do museu.*

## 2. Mecânicas de Jogo

### 2.1. Regras Básicas
*Terminar a primeira fase no tempo limite e coletar todas as chaves espalhadas pelo labirinto para que assim consiga abrir as portas das galerias de arte.*

*Desviar das estatuas concluir a segunda fase*

*Impedir o ladrão de fugir com o diamante e desviar dos lasers*

### 2.2. Controles
  *Os movimentos para andar são Tecla Right para movimentar a direita, Left para esquerda, Up para prossseguir e Down para trás*
  *Para pular aperte Space*
  *Movimentação da camera é com o Mouse*
  
### 2.3. Objetivos e Metas
*Seu objetivo é pegar o ladrão, chegar ao fim impedindo ele de fugir com o diamante do museu.*
*Suas metas são cumprir as devidas missões, assim conhecendo cada ambiente, para capturar o fugitivo com facilidade.*

### 2.5. Mecânicas de Interação
*Ao passar das fases você vai entrar no elevador, que ira te dar um checkpoint.
A fase 1 terá um tempo limite para concluia-la, caso não termine, o player ira voltar do inicio.
A seguir passará as estatuas que caso, elas te peguem, você volta ao checkpoint
Por fim terá a mesma mecanica da fase anterior, porém com lasers. Caso perca irá aparecer uma cutscene de derrota, onde o fugitivo escapará com o que pegou, ao concluir aparecerá o mesmo sendo levado pelo segurança, ou seja, a cutscene de vitoria*


### 2.7. Inteligência Artificial (IA)
*A estatuas dda segunda f

### 2.8. Dinâmicas de Jogo
*[Dica: Detalhe as dinâmicas de jogo que emergem das mecânicas. Isso inclui como diferentes mecânicas interagem para criar experiências de jogo. Por exemplo, "O sistema de combate interage com o sistema de progressão, permitindo que os jogadores usem habilidades adquiridas em níveis anteriores para derrotar inimigos mais difíceis."]*
- **Dinâmicas:**

### 2.9. Economia do Jogo
*[Dica: Explique como a economia do jogo funciona, incluindo moedas, recursos, e sistema de comércio. Por exemplo, "Os jogadores ganham ouro ao derrotar inimigos e completar missões. O ouro pode ser usado para comprar armas, armaduras e poções em lojas espalhadas pelo mundo do jogo."]*
- **Economia:**

## 3. Narrativa

### 3.1. História Principal
*Em uma noite no museu, um ladrão invade na intenção de roubar a joia da atlanticâ, uma joia famosa e cara que se encontra no local, então para não perder o nosso emprego, devemos pega-lo*
 
### 3.2. Personagens
1t. Agente
   - Ele trabalha como guarda noturno no museu, a visão do jogador será nele. O fazendo protagonista desse jogo
   
   <img src="https://github.com/user-attachments/assets/57c2dd7c-fccc-4be7-82ef-761b5e8226f5">
  o 
2. Ladrão
  - Ele será o nosso alvo e objetivo principal, ele ira fugir de nós ao decorrer das fases

 ![Capturar](https://github.com/user-attachments/assets/88d0fabe-6061-430a-9a1f-b4dad629e78f)

3. Estatuas
  - Estarão presentes na segunda fase, elas irão andar para atrapalhar o jogador do seu objetivo
    
![estatuasketch](https://github.com/user-attachments/assets/c1a469d9-7394-427b-a328-c691d3142763)



### 3.3. Cenários
**Museu**
1.Labirinto

2.Exposição Das Estatuas

3.Cofre das Joias 


### 3.4. Missões e Quests

### 3.5. Roteiro e Diálogos
*[Dica: Inclua trechos de diálogos importantes e o roteiro geral do jogo. Destaque as conversas chave que avançam a história e desenvolvem os personagens.]* Por exemplo:<br>

**Hderói:** <br>— Não posso deixar o feiticeiro destruir tudo o que amamos. Eu preciso encontrar o artefato.<br>
**Mentor:** <br>— Lembre-se, jovem herói, o poder verdadeiro vem de dentro. Use sua coragem e sabedoria para superar os desafios.<br>
**Feiticeiro:** <br>— Vocês nunca poderão me deter! Meu poder é absoluto e o mundo será meu! <br>

Descreva também a estrutura geral do roteiro, incluindo cenas cinematográficas e eventos importantes.

- **Diálogos:**

## 4. Design de Níveis

### 4.1. Estrutura dos Níveis
*[Dica: Explique a estrutura e progressão dos níveis. Descreva como os níveis são organizados e como o jogador avança de um nível para o outro. Por exemplo, "O jogo é dividido em 10 níveis principais, cada um com uma série de sub-níveis ou áreas. O jogador deve completar objetivos específicos em cada nível para desbloquear o próximo. O nível final culmina em uma batalha contra o chefe principal."]*
- **Estrutura:**

### 4.2. Mapas e Layouts
*[Dica: Inclua esboços ou descrições dos mapas e layouts dos níveis. Forneça detalhes sobre a disposição dos elementos no nível, como áreas exploráveis, inimigos, itens e obstáculos. Por exemplo, "O layout do primeiro nível inclui uma área inicial segura, seguida por uma série de plataformas sobre um abismo, com inimigos posicionados em pontos estratégicos e itens escondidos em áreas de difícil acesso."]*
- **Mapas:**

### 4.3. Desafios e Puzzles
*[Dica: Detalhe os principais desafios e puzzles que o jogador encontrará. Explique como esses elementos afetam a jogabilidade e como os jogadores devem superá-los. Por exemplo, "Os jogadores encontrarão portas trancadas que requerem chaves escondidas em áreas secretas. Também haverá puzzles de lógica onde o jogador deve ativar interruptores na ordem correta para abrir passagens."]*
- **oDesafios:**

### 4.4. Fluxo dos Níveis
*[Dica: Descreva o fluxo e ritmo dos níveis, como os jogadores avançam de um nível para outro. Inclua informações sobre checkpoints, pontos de salvamento e transições entre níveis. Por exemplo, "Cada nível possui dois checkpoints onde o progresso do jogador é salvo automaticamente. Ao final de cada nível, uma cena de transição revela a história e prepara o jogador para o próximo desafio."]*
- **Fluxo:**

### 4.5. Balanceamento de Dificuldade
*[Dica: Explique como a dificuldade dos níveis será balanceada. Discuta o aumento gradual da dificuldade e como isso é implementado para manter o jogo desafiador mas justo. Por exemplo, "A dificuldade aumenta gradualmente com mais inimigos e puzzles mais complexos à medida que o jogador progride. O primeiro nível é projetado para ser introdutório, enquanto os níveis finais apresentam desafios que exigem domínio completo das mecânicas do jogo."]*
- **Dificuldade:**


## 5. Arte e Estilo Visual

### 5.1. Estilo Artístico
*[Dica: Descreva o estilo artístico geral do jogo. Explique como a estética do jogo se alinha com a temática e o gênero. Por exemplo, "O estilo artístico do jogo é baseado em pixel art, com uma paleta de cores vibrantes que lembra jogos retro dos anos 90. Isso ajuda a criar uma sensação de nostalgia enquanto mantém o visual moderno e polido."]*
- **Estilo:**

### 5.2. Personagens e Animações
*[Dica: Inclua detalhes sobre a arte e animações dos personagens. Descreva o design visual, trajes, expressões faciais e movimentos. Por exemplo, "Os personagens principais são desenhados em um estilo cartunesco com traços exagerados para expressar emoções de forma clara. As animações incluem movimentos de corrida, salto, ataque e ações especiais, todas fluídas e responsivas para melhorar a experiência de jogo."]*
- **Arte dos Personagens:**

### 5.3. Cenários e Ambientes
*[Dica: Descreva a arte dos cenários e ambientes. Inclua detalhes sobre os elementos visuais, iluminação e atmosfera. Por exemplo, "Os cenários são detalhados com camadas de fundo para criar profundidade. Cada ambiente, como florestas, cavernas e castelos, tem uma estética única com iluminação dinâmica para realçar a atmosfera mágica e misteriosa do jogo."]*
- **Arte dos Cenários:**

### 5.4. Interface do Usuário (UI)
*[Dica: Detalhe o design da interface do usuário, incluindo menus e HUD. Explique como a interface é intuitiva e fácil de navegar. Por exemplo, "A interface do usuário apresenta um design limpo com ícones grandes e texto legível. O HUD inclui barra de vida, mana, e um mini-mapa, todos posicionados de forma a não obstruir a visão do jogador. Os menus são simples, com opções claras para facilitar a navegação."]*
- **Interface:**

### 5.5. Paleta de Cores
*[Dica: Especifique a paleta de cores a ser usada no jogo. Explique como as cores escolhidas influenciam a atmosfera e a experiência do jogador. Por exemplo, "A paleta de cores do jogo inclui tons vibrantes de verde e azul para ambientes exteriores, e tons mais escuros e misteriosos de roxo e preto para áreas perigosas, criando um contraste visual que ajuda a orientar o jogador e a definir o tom de cada nível."]*
- **Paleta de Cores:**


## 6. Áudio

### 6.1. Trilha Sonora
*[Dica: Descreva o estilo e os principais temas da trilha sonora. Explique como a música contribui para a atmosfera do jogo e destaca momentos importantes. Por exemplo, "A trilha sonora é composta por músicas orquestrais épicas que variam de temas calmos e misteriosos para momentos de exploração, a composições intensas e enérgicas durante batalhas. Cada área do jogo tem um tema musical único que reflete seu ambiente e importância na história."]*
- **Trilha Sonora:**

### 6.2. Efeitos Sonoros
*[Dica: Liste os principais efeitos sonoros e seu propósito no jogo. Explique como cada som melhora a jogabilidade e a imersão. Por exemplo, "Os efeitos sonoros incluem o som de passos variados dependendo do terreno, sons de combate como espadas colidindo e feitiços sendo lançados, e efeitos ambientais como vento soprando e água corrente. Esses sons ajudam a criar uma experiência mais realista e envolvente."]*
- **Efeitos Sonoros:**


### 6.4. Ambiente Sonoro
*[Dica: Explique como o som ambiente será utilizado para criar imersão. Descreva os tipos de sons ambientais presentes e como eles contribuem para a atmosfera do jogo. Por exemplo, "O som ambiente inclui ruídos de fundo como canto de pássaros em florestas, ecos misteriosos em cavernas e murmúrios de multidões em cidades. Esses sons ajudam a criar uma sensação de lugar e imersão no mundo do jogo, fazendo o jogador sentir que está realmente lá."]*
- **Som Ambiente:**

## 7. Progresso e Salvamento

### 7.1. Sistema de Progressão
*[Dica: Explique como o jogador progride no jogo. Isso pode incluir ganho de níveis, habilidades desbloqueáveis, aquisição de equipamentos e avanço na história. Por exemplo, "O jogador ganha pontos de experiência ao derrotar inimigos e completar missões. Esses pontos de experiência permitem que o jogador suba de nível, aumentando atributos como força e agilidade. Novas habilidades e feitiços são desbloqueados a cada nível, oferecendo mais opções estratégicas em combate. Equipamentos e armas melhores podem ser encontrados ou comprados ao longo do jogo, melhorando ainda mais o desempenho do personagem."]*
- **Progressão:**
### 7.2. Sistema de Salvamento
*[Dica: Descreva como e quando o jogo salva o progresso do jogador. Explique os tipos de salvamento disponíveis, como salvamento automático, pontos de salvamento e salvamento manual. Por exemplo, "O jogo utiliza um sistema de salvamento automático que grava o progresso do jogador ao completar missões, alcançar checkpoints e entrar em novas áreas. Além disso, o jogador pode salvar manualmente em qualquer momento através do menu de pausa. Pontos de salvamento especiais, como estatuas mágicas, estão espalhados pelos níveis e oferecem uma maneira adicional de garantir que o progresso não seja perdido."]*
- **Salvamento:**



## 9. Testes e Qualidade
### 9.1. Testes de Jogo
*[Dica: Descreva o plano de testes para garantir a qualidade do jogo. Inclua métodos de teste, cronograma, e ferramentas usadas. Por exemplo, "O plano de testes inclui testes alfa e beta, com um grupo seleto de jogadores participando do alfa para encontrar e relatar bugs iniciais. O beta será aberto a um público maior para feedback mais abrangente. Testes automatizados serão usados para verificar a estabilidade do código, enquanto testes manuais garantirão que a jogabilidade esteja de acordo com o design. Sessões de jogo regulares serão realizadas para avaliar o equilíbrio e a diversão do jogo."]*
- **Plano de Testes:**

### 9.2. Feedback dos Jogadores
*[Dica: Explique como o feedback dos jogadores será coletado e usado. Inclua métodos de coleta de feedback, como pesquisas, fóruns, e análises de jogabilidade. Por exemplo, "O feedback dos jogadores será coletado através de pesquisas in-game e em nossa comunidade online, onde os jogadores podem compartilhar suas opiniões e sugestões. Análises de jogabilidade serão realizadas para entender o comportamento dos jogadores e identificar áreas de melhoria. Todo o feedback será revisado pela equipe de desenvolvimento para priorizar atualizações e correções que melhorem a experiência do jogador."]*
- **Feedback:**

## 10. Conclusão

### 10.1. Sumário
*[Dica: Resuma os principais pontos do GDD. Isso deve incluir uma visão geral rápida das mecânicas de jogo, narrativa, design de níveis, arte e estilo visual, áudio, progresso e salvamento, monetização, e testes e qualidade. Por exemplo, "Este GDD detalha um RPG de ação com uma narrativa envolvente sobre um herói que deve salvar seu reino de um feiticeiro maligno. O jogo apresenta mecânicas de combate dinâmico, progressão de personagem através de níveis e habilidades, e uma rica trilha sonora orquestral. A arte em pixel art e os efeitos sonoros imersivos contribuem para uma experiência de jogo memorável."]*
- **Sumário:**

### 10.2. Próximos Passos
*[Dica: Liste as próximas etapas no desenvolvimento do jogo. Inclua marcos importantes e um cronograma aproximado. Por exemplo, "Os próximos passos no desenvolvimento do jogo incluem:]*
1. **Prototipagem:** Criar protótipos jogáveis das principais mecânicas de jogo até o final do mês.
2. **Desenvolvimento Alfa:** Desenvolver a primeira versão completa do jogo com todos os níveis e mecânicas principais até o final do trimestre.
3. **Teste Alfa:** Realizar testes internos e com um grupo seleto de jogadores para identificar e corrigir bugs.
4. **Desenvolvimento Beta:** Refinar o jogo com base no feedback dos testes alfa e adicionar conteúdo adicional até o final do segundo trimestre.
5. **Teste Beta:** Abrir o jogo para testes beta públicos e coletar feedback abrangente.
6. **Lançamento:** Preparar e lançar a versão final do jogo, incluindo campanhas de marketing e distribuição, até o final do ano."
- **Próximos Passos:**

 
