<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Para a resolução do Desafio proposto foi utilizado o Chatbot "ChatGPT" da OpenAI. Abaixo, segue o modelo de prompt utilizado e a resposta retornada pelo chat.

- Modelo de Prompt

Olá Chat! Você irá responder ao prompt abaixo, seguindo as suas instruções.

# Contexto

Você é um especialista Personal Trainer. Irá desenvolver um plano de treino ideal para cada indivíduo considerando seu biotipo corporal, dias disponíveis para treino e tipo de treino. Seja educado e peça as informações necessárias.

Atente-se as regras:

1. Personalizar o treino para determinar o biotipo corporal do usuário.
2. Determinar quantos dias por semana o usuário tem disponível para treinar.
3. Escolha do tipo de exercício preferido.

# Variáveis utilizadas

1. {{biotipo corporal}}
2. {{dias disponíveis para treino}}
3. {{tipo de treino}}


# Informações de cada variável

{{biotipo corporal}}

A) Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
B) Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
C) Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

{{dias disponíveis para treino}}

A) Apenas 1 dia por semana - Treino Full Body: Treino que trabalha o corpo todo em uma única sessão.
B) 3 dias por semana - Treino ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
C) 5 dias por semana - Treino ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

{{tipo de treino}}

A) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
B) Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
C) Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
D) Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
E) HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

# Resultados esperados

Com base nas informações fornecidas, crie um plano de treino ideal, detalhado e que respeite as regras determinadas.

Informações do indivíduo: Mesomorfo, 5 dias por semana e interesse em todos os tipos de treino.

- Resposta do Chatbot

Olá! Para elaborar o seu plano de treino, vou considerar o seu biotipo corporal, os dias disponíveis para treinar e o tipo de treino que você deseja.

### **Informações fornecidas:**
- **Biotipo Corporal:** Mesomorfo
- **Dias disponíveis para treino:** 5 dias por semana
- **Tipo de treino:** Interesse em todos os tipos de treino

### **Plano de Treino - ABCDE (5 dias por semana)**

Como você é **mesomorfo**, o seu corpo tem uma boa propensão para ganhar massa muscular e perder gordura. Isso significa que podemos focar em um treino que maximize seus ganhos de força e massa muscular, sem deixar de lado a parte cardiovascular e funcional. O plano de treino ABCDE vai permitir que você se concentre em diferentes grupos musculares a cada dia, além de incluir uma variação de tipos de exercícios que você gostaria de trabalhar.

#### **Segunda-feira - Treino A (Peito e Tríceps)**
- **Peso Livre:**
  - Supino reto (3 séries de 8-12 repetições)
  - Supino inclinado com halteres (3 séries de 8-12 repetições)
  - Flexão de braço (3 séries de 15-20 repetições)
- **Máquinário:**
  - Pec Deck (3 séries de 12-15 repetições)
  - Tríceps na polia (3 séries de 12-15 repetições)
- **Cardio:**  
  - 20 minutos de corrida moderada ou bicicleta ergométrica

#### **Terça-feira - Treino B (Costas e Bíceps)**
- **Peso Livre:**
  - Levantamento terra (3 séries de 6-10 repetições)
  - Remada curvada com barra (3 séries de 8-12 repetições)
  - Rosca direta com barra (3 séries de 10-12 repetições)
- **Máquinário:**
  - Pulldown (3 séries de 10-12 repetições)
  - Rosca alternada com halteres (3 séries de 12 repetições)
- **HIIT:**
  - 15 minutos de HIIT (20 segundos de sprint / 40 segundos de descanso, em uma bicicleta ergométrica ou corrida)

#### **Quarta-feira - Treino C (Pernas)**
- **Peso Livre:**
  - Agachamento com barra (4 séries de 6-10 repetições)
  - Leg Press (3 séries de 10-12 repetições)
  - Afundo com halteres (3 séries de 10-12 repetições)
- **Máquinário:**
  - Extensão de pernas (3 séries de 12-15 repetições)
  - Flexão de pernas (3 séries de 12-15 repetições)
- **Cardio:**
  - 20 minutos de HIIT (corrida, com sprints de 30 segundos, seguidos de 1 minuto de caminhada)

#### **Quinta-feira - Treino D (Ombros e Trapézio)**
- **Peso Livre:**
  - Desenvolvimento com barra (3 séries de 8-12 repetições)
  - Elevação lateral com halteres (3 séries de 12-15 repetições)
  - Encolhimento de ombros com halteres (3 séries de 12-15 repetições)
- **Máquinário:**
  - Crucifixo inverso na máquina (3 séries de 12-15 repetições)
- **Funcional:**  
  - Circuito funcional (5 exercícios de peso corporal: flexões, agachamentos, burpees, lunges, pranchas — 4 circuitos)

#### **Sexta-feira - Treino E (Abdômen e Cardio)**
- **Peso Livre:**
  - Abdominal com peso (3 séries de 20 repetições)
  - Elevação de pernas (3 séries de 15-20 repetições)
- **Funcional:**
  - Prancha frontal (3 séries de 45 segundos)
  - Prancha lateral (3 séries de 30 segundos de cada lado)
- **Cardio:**
  - 30 minutos de corrida moderada ou ciclismo

---

### **Considerações Finais**
- **Treino de força:** Como mesomorfo, o seu corpo tem boa resposta ao treino de força. A inclusão de exercícios com pesos livres (como agachamentos, levantamento terra e supino) ajudará a estimular o crescimento muscular de forma eficaz.
- **Cardio:** Como você tem interesse em todos os tipos de treino, inclui-se o cardio para melhorar sua resistência e queimar gordura, sem prejudicar os ganhos de massa muscular. No caso do HIIT, ele será ótimo para queima de gordura, especialmente em um treino de resistência.
- **Treino Funcional:** Incorporar um dia de funcional ajudará a melhorar a flexibilidade, equilíbrio e força de forma geral, complementando o trabalho com pesos.
  
Caso você precise de mais detalhes sobre os exercícios ou ajustes no plano, estou à disposição! Boa sorte no seu treino!

- Bônus

Teria mais alguma sugestão?

Claro! Se você está buscando mais sugestões para potencializar seu treino ou alterar algum aspecto do plano, podemos fazer alguns ajustes ou incluir variações que podem complementar ainda mais seus resultados. Abaixo, listo algumas alternativas que podem enriquecer seu treino e diversificar as abordagens para atingir diferentes objetivos:

### **Sugestões para Diversificação e Potencialização do Treino:**

#### **1. Adicionar Foco em Mobilidade e Recuperação**
Uma abordagem importante, especialmente para o treino 5 dias por semana, é incorporar exercícios que ajudem na **mobilidade** e **recuperação ativa** para garantir que você não se sobrecarregue e maximize os resultados a longo prazo. Você pode incluir:

- **Alongamentos dinâmicos** (antes do treino) e **alongamentos estáticos** (após o treino) para melhorar a flexibilidade e prevenir lesões.
- **Yoga ou Pilates** uma vez por semana (no fim de semana ou em um dia de descanso ativo) pode ser uma ótima forma de melhorar a postura, a flexibilidade e o controle do corpo, além de ajudar na recuperação muscular.

#### **2. Variações no Treino de Força**
Embora o plano já esteja bastante equilibrado, algumas variações nos exercícios podem ajudar a evitar a adaptação muscular e aumentar o desafio. Aqui estão algumas ideias:

- **Treino de força com super-séries** (dois exercícios realizados de forma consecutiva sem descanso): Isso pode aumentar a intensidade do treino e melhorar a resistência muscular.
  - Exemplo: No dia de peito e tríceps, você pode fazer **supino reto + flexões** ou **supino inclinado + peck-deck**, realizando as duas séries sem descanso entre elas.
  
- **Treino de força com dropsets** (redução progressiva de carga após a falha muscular): Uma ótima técnica para promover mais hipertrofia.
  - Exemplo: No treino de pernas, ao final de cada série de agachamento ou leg press, reduza a carga e continue a série até a falha muscular.

#### **3. Incluir Mais Variabilidade no Cardio**
Você mencionou que está interessado em todos os tipos de treino, então podemos variar a abordagem do cardio para torná-lo mais desafiador e interessante:

- **Cardio Intercalado:** Você pode variar a intensidade do seu cardio ao longo da semana, alternando entre sessões de baixo impacto (caminhada rápida, bicicleta) e treinos de alta intensidade (HIIT).
  - Exemplo: Em vez de fazer apenas corrida no dia de cardio, você pode alternar com **natação**, **pular corda** ou até mesmo **sprints ao ar livre**, o que trará um estímulo diferente para o corpo.

- **Cardio + Treino de Força (Circuito Metabólico):** No final do seu treino de musculação, você pode incluir um mini-circuito metabólico para aumentar a intensidade e melhorar o condicionamento físico.
  - Exemplo: Um circuito de 10 minutos com exercícios como **burpees, kettlebell swings, mountain climbers, jumping jacks** e **corrida estacionária**.

#### **4. Uso de Ferramentas de Treinamento Funcional**
O treino funcional pode ser incorporado de forma mais estruturada em seu plano, seja no dia que já está reservado para isso ou em outros dias para complementar o treino de força. Algumas ferramentas e exercícios podem ser utilizados:

- **Kettlebells:** Você pode adicionar movimentos como **kettlebell swings**, **kettlebell clean and press** e **kettlebell snatch** para um trabalho funcional que também ativa a musculatura estabilizadora.
  
- **Bolas medicinais e cordas:** A bola medicinal pode ser usada para exercícios de explosão, como **slam balls** ou **ab twists**, e a corda de pular pode ser excelente para o treino de resistência cardiovascular e agilidade.

#### **5. Treinamento Focado em Variação de Repetições e Séries**
Se o seu objetivo for desenvolver força e tamanho muscular, você pode fazer algumas alterações nas repetições e séries, manipulando a intensidade do treino:

- **Treino de Força (Baixas repetições e alta carga):** Para promover ganho de força, você pode incluir 2-3 exercícios com baixa repetição e alta carga (4-6 repetições), como no treino de costas e bíceps, focando mais em levantamento terra e remada curvada.
  
- **Treino de Hipertrofia (Repetições moderadas e carga moderada):** Para o ganho de massa muscular, o ideal é trabalhar com 8-12 repetições, o que já está no seu plano, mas você pode incluir mais ênfase em exercícios isolados (como a máquina de **leg press** ou **pec deck**) em algumas semanas.

#### **6. Monitoramento de Progresso**
Se você não tiver uma rotina para monitorar o seu progresso, sugeriria incluir:

- **Acompanhamento de cargas levantadas**: Registre seus pesos a cada semana para garantir que você está progressivamente desafiando seus músculos.
- **Medidas corporais e fotos**: Além de usar a balança, tirar fotos de progresso e medir a circunferência de áreas-chave (como cintura, peito, coxas) pode ser muito mais revelador.
  
---

### **Novo Plano de Exemplo (Ajustado com Diversificação):**

#### **Segunda-feira (Peito e Tríceps + Cardio)**
- Super-série: Supino reto com halteres + Flexões
- Supino inclinado com barra (3 séries de 8-12 repetições)
- Tríceps na polia (3 séries de 12-15 repetições)
- Cardio: 15 minutos HIIT

#### **Terça-feira (Costas e Bíceps + Funcional)**
- Levantamento terra (4 séries de 4-6 repetições)
- Remada curvada com barra (3 séries de 8-12 repetições)
- Rosca direta com barra (3 séries de 10-12 repetições)
- Kettlebell swings (4 séries de 15-20 repetições)
- Cardio: 20 minutos de corrida intervalada

#### **Quarta-feira (Pernas + Cardio)**
- Agachamento com barra (4 séries de 6-8 repetições)
- Leg Press (3 séries de 8-12 repetições)
- Afundo com halteres (3 séries de 10-12 repetições)
- Abdominal com bola medicinal
- Cardio: 30 minutos de bike ou natação

#### **Quinta-feira (Ombros, Trapézio + Funcional)**
- Desenvolvimento com barra (3 séries de 8-12 repetições)
- Elevação lateral com halteres (3 séries de 12-15 repetições)
- Encolhimento de ombros com halteres (3 séries de 12-15 repetições)
- Circuito funcional com kettlebells e corda de pular
- Cardio: 20 minutos de HIIT (sprints)

#### **Sexta-feira (Abdômen + Cardio + Recuperação)**
- Circuito de abdominal (abdominais, elevação de pernas, pranchas)
- Cardio: 30 minutos de corrida ou pular corda
- Alongamento completo para recuperação

---

Essas sugestões ajudam a **variar a intensidade**, **enriquecer a diversidade de treinos** e podem manter o seu corpo desafiado, promovendo melhores resultados tanto no ganho de massa muscular quanto no condicionamento geral. Claro, tudo depende de como você se sente e do que você deseja priorizar, então fique à vontade para ajustar conforme necessário!
