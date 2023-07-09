# MVP - GESTÃO ÁGIL DE PROJETOS E PRODUTOS

Este projeto destina-se à entrega do MVP para avaliação do segundo trimestre do curso de pós graduação em engenharia de
software da PUC-RIO 2023.

O escopo deste projeto é a criação de um MVP demostrando a utilização de técnicas ágeis de gestão de projetos e
produtos.

O projeto consiste em um aplicativo mobile android para acompanhamento de bem-estar, alimentação e atividades físicas.

## Ferramentas Utilizadas

- Miro: desenvolvimento de uma lean inception para ideação e delimitação do escopo do MVP
- Figma: desenvolvimento de protótipos de baixa fidelidade
- Jira: gestão do backlog do produto e do projeto

## Equipe

- Bruno - PO e Scrum Master
- Jairo - Tech Lead e DevOps
- André - Desenvolvedor
- Giuly - Desing e UX

- Convidados:
    - Larissa: profissional de educacão física
    - Paloma: nutricionista

Lean Inception
==============

#### Visão

- PARA pessoas
- QUE estejam buscando melhorar e monitorar consistentemente seu estilo de vida e bem-estar
- O Bem Me Quero
- É aplicativo mobile de rastreamento de saúde e bem-estar
- QUE fornece uma maneira eficiente e integrada de acompanhar e gerenciar atividades relacionadas à saúde, como
  exercícios, nutrição, sono e bem-estar mental
- DIFERENTE DO WebDiet, Calorie Counter, FitnessView, MyFitnessPal e outros aplicativos de fitness e bem-estar que
  rastreiam apenas aspectos individuais da saúde
- NOSSO PRODUTO oferece uma solução integrada e holística, proporcionando um panorama completo do bem-estar do usuário.

#### É - Não é; Faz - Não Faz

- É:
    - Um recurso integrado para monitorar atividades de saúde, nutrição, sono e bem-estar mental.
    - Um aplicativo mobile para rastreamento de bem-estar e saúde
    - Uma plataforma que fornece insights personalizados e incentivo para o bem-estar.
    - Uma comunidade digital de apoio à saúde e ao bem-estar.
- Não é:
    - Um substituto para um profissional de saúde ou conselho médico.
    - Um personal trainer ou nutricionista pessoal.
    - Um aplicativo de diagnóstico médico.
    - Um aplicativo de meditação ou atenção plena.
- Faz:
    - Rastreia e registra atividades de saúde e bem-estar.
    - Fornece feedback personalizado com base nos dados do usuário.
    - Fornece dicas e sugestões para um estilo de vida saudável.
    - Facilita o estabelecimento e acompanhamento de metas de saúde e bem-estar.
    - Cria uma rede de suporte comunitário para incentivar e motivar os usuários.
- Não faz:
    - Não fornece diagnóstico médico ou tratamento para condições de saúde.
    - Não substitui a necessidade de um profissional de saúde.
    - Não faz aconselhamento psicológico ou terapia.
    - Não fornece planos de treino personalizados ou dietas detalhadas.

#### Objetivos

- Impacto positivo na vida dos usuários
    - Promover o bem-estar físico e mental dos usuários através do acompanhamento consistente de hábitos saudáveis.
    - Incentivar os usuários a estabelecer e atingir metas de bem-estar pessoal.
    - Fornecer informações e insights que ajudem os usuários a tomar decisões informadas sobre sua saúde e bem-estar.
    - Criar uma atmosfera de apoio e motivação, onde os usuários se sentem encorajados a compartilhar suas jornadas de
      bem-estar e aprender uns com os outros.
- Experiência do Usuário
    - Fornecer aos usuários uma experiência de uso agradável, tanto em termos de design quanto de facilidade de uso.
    - Garantir que o aplicativo seja intuitivo e fácil de usar para todos os públicos-alvo.
    - Implementar um design atraente que seja acessível e agradável para os usuários.
    - Assegurar que o aplicativo seja seguro e proteja a privacidade dos usuários.
- Crescimento e Parcerias
    - Tornar-se uma plataforma de referência no mercado para rastreamento de saúde e bem-estar.
    - Estabelecer parcerias com profissionais de saúde e bem-estar (como nutricionistas e educadores físicos) para
      enriquecer o conteúdo e os recursos do aplicativo.
    - Expandir a base de usuários através de estratégias de marketing eficazes e boca a boca.
    - Explorar oportunidades de monetização sem comprometer a experiência do usuário.

#### Personas

- João, "o atleta amador"
    - 28 anos; engenheiro de software; solteiro; adora esportes e atividades ao ar livre.
    - Precisa monitorar seu desempenho em várias atividades, acompanhar sua nutrição e garantir um sono adequado para
      manter o máximo desempenho.
    - Treina regularmente e compete em maratonas e triatlos. É muito autodisciplinado e sempre procura maneiras de
      melhorar seu desempenho.

- Ana, "a multitarefas"
    - 35 anos; advogada; mãe de dois filhos pequenos; luta para equilibrar o trabalho, a vida familiar e o tempo para si
      mesma.
    - Raramente tem tempo para ir à academia ou cozinhar refeições saudáveis. Fica estressada e muitas vezes sacrifica o
      sono para cumprir todas as suas tarefas.
    - Precisa de maneiras simples e eficientes de cuidar de sua saúde e bem-estar, que se encaixem em sua agenda
      ocupada.

- Carlos, "o vovô garoto"
    - 65 anos; aposentado; gosta de viajar e passar tempo com seus netos; Tem algumas questões de saúde que precisa
      monitorar.
    - Precisa de um aplicativo simples e intuitivo que o ajude a acompanhar suas atividades diárias, nutrição, sono e
      bem-estar mental.
    - Não é muito tecnologicamente experiente, mas está disposto a aprender se isso ajudar a monitorar sua saúde.

- Cláudia, "a determinada"
    - 42 anos; divorciada; gerente de projetos; se sente cansada e desmotivada; determinada a mudar seus hábitos de
      vida.
    - Tem dificuldade em manter uma dieta saudável e uma rotina de exercícios, mas está disposta a mudar isso.
    - Precisa de uma visão holística de sua saúde, que a ajude a se manter motivada e acompanhe sua jornada de mudança.

#### Jornadas de usuário

- João, "o atleta amador"
    - João acorda cedo e prepara um café da manhã saudável rico em proteínas para energizar seu treino matinal.
    - Ele corre no parque próximo à sua casa, se esforçando para bater seu recorde pessoal.
    - Depois do treino, João vai para casa e se prepara para o trabalho.
    - Durante o almoço, ele decide que quer monitorar melhor sua nutrição para melhorar seu desempenho. Ele pesquisa
      sobre aplicativos de bem-estar e encontra o "Bem Me Quero".
    - João baixa o aplicativo, cria um perfil e insere suas metas de saúde e fitness.
    - Depois do trabalho, ele vai para a academia e usa o aplicativo para registrar seu treino.
    - Em casa, João prepara uma refeição saudável e a registra no aplicativo.
    - Antes de dormir, João verifica o aplicativo para ver um resumo de seu dia.

- Ana, "a multitarefas"
    - Ana acorda, prepara o café da manhã para os filhos e os leva para a escola.
    - Ela vai para o trabalho e tem um dia ocupado com várias reuniões e tarefas.
    - Durante uma pausa para o café, ela decide que precisa encontrar uma maneira de cuidar melhor de sua saúde e
      bem-estar. Ana pesquisa sobre aplicativos de bem-estar e encontra o "Bem Me Quero".
    - Ana baixa o aplicativo e cria um perfil durante o almoço.
    - Ela usa o aplicativo para planejar refeições saudáveis para a próxima semana.
    - Ana pega as crianças na escola e vai para casa preparar o jantar.
    - Depois do jantar, ela registra sua refeição no aplicativo.
    - Antes de dormir, Ana usa o aplicativo para registrar seu nível de estresse e ler algumas dicas de gerenciamento de
      estresse.

- Carlos, "o vovô garoto"
    - Carlos acorda cedo, toma um café da manhã nutritivo e sai para uma caminhada matinal.
    - Ele volta para casa, descansa um pouco e decide verificar sua pressão arterial e batimentos cardíacos.
    - Carlos pega seu smartphone e pesquisa um aplicativo que possa ajudá-lo a acompanhar sua saúde. Ele encontra o "Bem
      Me Quero".
    - Ele baixa o aplicativo e cria um perfil, inserindo suas informações de saúde.
    - Carlos registra suas informações de saúde no aplicativo
    - Ele passa o resto do dia cuidando de seus hobbies e brincando com seus netos.-

- Cláudia, "a determinada"
    - Cláudia acorda se sentindo cansada e desmotivada. Ela decide que precisa fazer algumas mudanças em sua rotina para
      melhorar seu bem-estar.
    - No caminho para o trabalho, ela pesquisa sobre aplicativos de bem-estar e descobre o "Bem Me Quero".
    - Ela baixa o aplicativo e cria um perfil, inserindo suas metas de saúde.
    - Durante o almoço, Cláudia verifica o aplicativo e explora os diferentes recursos.
    - Cláudia configura uma meta de saúde no aplicativo e começa a registrar suas refeições.
    - Depois do trabalho, ela vai para a academia e registra seu treino no aplicativo.
    - Em casa, Cláudia prepara uma refeição saudável e a registra no aplicativo.
    - Antes de dormir, Cláudia usa o aplicativo para se conectar com outros usuários que também estão na jornada para
      uma vida mais saudável.  

#### Brainstorming
- Configurar lembretes  
  - Configurar lembretes de atividade física.
  - Definir lembretes para beber água.
  - Configurar lembretes para práticas de gerenciamento de estresse.
  - Agendar lembretes para exames de saúde.
- Adicionar alimentos consumidos ao diário alimentar.  
- Registrar horas de sono.  
- Postar na comunidade do aplicativo.  
- Iniciar uma rotina de treino personalizada.
- Ver sugestões personalizadas de bem-estar.  
- Aceitar um desafio de bem-estar.  
- Solicitar uma consulta com um profissional de saúde.  
- Atualizar o peso registrado.
- Adicionar um plano de refeições à agenda.  
- Definir uma meta de bem-estar.  
- Ver o resumo diário de bem-estar.  
- Registrar emoções ou sentimentos.  
- Ler um artigo educacional de saúde.  
- Solicitar uma sessão de coaching de vida.  
- Acompanhar o progresso dos objetivos de bem-estar.    
- Registrar refeições através de fotos.  
- Sugestão de refeições personalizadas via integração IOT  
- Conectar com dispositivos smart para sincronizar atividades.  

#### Revisão Técnica, de Negócio e de Usabilidade
![image](https://github.com/BrunoBasstos/mvp-gap/assets/5402439/41f890ac-a9b6-447e-8e54-a36493aaf182)

#### Sequenciador
![image](https://github.com/BrunoBasstos/mvp-gap/assets/5402439/33ce7a0c-cad0-4948-af07-2a5874796ea6)

#### MVP Canvas
![image](https://github.com/BrunoBasstos/mvp-gap/assets/5402439/e0e89078-a19a-45a1-a5a8-63c1c6b3ed35)

# UI/UX Design
#### Protótipo de baixa fidelidade
- Figma Screenshot
![image](https://github.com/BrunoBasstos/mvp-gap/assets/5402439/98b1cef0-f8f7-4385-9b20-3f299bd22c3d)

# Backlog do Produto
#### Jira Screenshot
![image](https://github.com/BrunoBasstos/mvp-gap/assets/5402439/8059fed1-a219-4a8e-8273-6f61d03d3007)
