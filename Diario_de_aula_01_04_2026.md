# 📘 Diário de Aula – Refinamento de Requisitos (JAD)

---

## 🎯 Objetivo da Aula

Refinar os requisitos do sistema de biblioteca por meio da técnica **JAD (Joint Application Development)**, utilizando perguntas previamente definidas e registrando as respostas dos stakeholders.

---

## 👥 Participantes

- **Ana** – Responsável pelas regras do sistema  
- **Rosa** – Operacional / uso diário  
- **Julia** – Visão de sistema e processos  

---

## 📋 Perguntas e Respostas

---

### 🔹 1. Prazo para retirada de livros reservados *(Prioridade: Alta)*

**Pergunta:**  
Existe um prazo para retirada do livro após a reserva? Após esse prazo ocorre cancelamento automático?

**Resposta:**  

**Ana:**  
Existe um prazo de **3 dias úteis** para retirada após a notificação de disponibilidade. Após esse período, a reserva é cancelada automaticamente.

**Rosa:**  
O cancelamento evita que livros fiquem parados sem necessidade.

**Julia:**  
A notificação é enviada no momento em que o livro se torna disponível.

---

### 🔹 2. Dados necessários para reserva

**Pergunta:**  
Quais dados do usuário são necessários para realizar uma reserva?

**Resposta:**  

**Ana:**  
- Identificação do usuário (matrícula ou CPF)  
- Identificação do livro/exemplar  
- Data da reserva (gerada automaticamente)

**Rosa:**  
O usuário precisa estar previamente cadastrado.

**Julia:**  
O sistema recupera automaticamente dados como nome e contato.

---

### 🔹 3. Limite de reservas por usuário

**Pergunta:**  
Quantas reservas um usuário pode fazer simultaneamente?

**Resposta:**  

**Ana:**  
- Alunos: até **3 reservas simultâneas**  
- Professores: até **5 reservas simultâneas**

**Rosa:**  
Evita acúmulo e melhora a circulação dos livros.

**Julia:**  
O sistema deve bloquear novas reservas ao atingir o limite.

---

### 🔹 4. Conflito de reservas *(Prioridade: Baixa)*

**Pergunta:**  
O que acontece quando dois usuários tentam reservar o mesmo livro?

**Resposta:**  

**Rosa:**  
O sistema utiliza uma **fila de reservas**.

**Ana:**  
O livro é disponibilizado seguindo a ordem da fila.

**Julia:**  
A ordem cronológica deve ser registrada para garantir transparência.

---

### 🔹 5. Acessibilidade
# 📘 Diário de Aula – Refinamento de Requisitos (JAD)

---

## 🎯 Objetivo da Aula

Refinar os requisitos do sistema de biblioteca por meio da técnica **JAD (Joint Application Development)**, utilizando perguntas previamente definidas e registrando as respostas dos stakeholders.

---

## 👥 Participantes

- **Ana** – Responsável pelas regras do sistema  
- **Rosa** – Operacional / uso diário  
- **Julia** – Visão de sistema e processos  

---

## 📋 Perguntas e Respostas

---

### 🔹 1. Prazo para retirada de livros reservados *(Prioridade: Alta)*

**Pergunta:**  
Existe um prazo para retirada do livro após a reserva? Após esse prazo ocorre cancelamento automático?

**Resposta:**  

**Ana:**  
Existe um prazo de **3 dias úteis** para retirada após a notificação de disponibilidade. Após esse período, a reserva é cancelada automaticamente.

**Rosa:**  
O cancelamento evita que livros fiquem parados sem necessidade.

**Julia:**  
A notificação é enviada no momento em que o livro se torna disponível.

---

### 🔹 2. Dados necessários para reserva

**Pergunta:**  
Quais dados do usuário são necessários para realizar uma reserva?

**Resposta:**  

**Ana:**  
- Identificação do usuário (matrícula ou CPF)  
- Identificação do livro/exemplar  
- Data da reserva (gerada automaticamente)

**Rosa:**  
O usuário precisa estar previamente cadastrado.

**Julia:**  
O sistema recupera automaticamente dados como nome e contato.

---

### 🔹 3. Limite de reservas por usuário

**Pergunta:**  
Quantas reservas um usuário pode fazer simultaneamente?

**Resposta:**  

**Ana:**  
- Alunos: até **3 reservas simultâneas**  
- Professores: até **5 reservas simultâneas**

**Rosa:**  
Evita acúmulo e melhora a circulação dos livros.

**Julia:**  
O sistema deve bloquear novas reservas ao atingir o limite.

---

### 🔹 4. Conflito de reservas *(Prioridade: Baixa)*

**Pergunta:**  
O que acontece quando dois usuários tentam reservar o mesmo livro?

**Resposta:**  

**Rosa:**  
O sistema utiliza uma **fila de reservas**.

**Ana:**  
O livro é disponibilizado seguindo a ordem da fila.

**Julia:**  
A ordem cronológica deve ser registrada para garantir transparência.

---

### 🔹 5. Acessibilidade

**Pergunta:**  
O sistema deve possuir recursos de acessibilidade?

**Resposta:**  

**Ana:**  
Sim, incluindo:
- Ajuste de fonte  
- Alto contraste  
- Compatibilidade com leitores de tela  

**Rosa:**  
Facilita o uso direto pelos usuários.

**Julia:**  
Evita retrabalho futuro e segue boas práticas.

---

### 🔹 6. Regras de multa por atraso

**Pergunta:**  
A multa de R$1,00 por dia inclui fins de semana?

**Resposta:**  

- Valor: **R$1,00 por dia útil**  
- Fins de semana **não são contabilizados**  
- A multa **continua durante recesso**  

---

### 🔹 7. Danos e perda de livros

**Pergunta:**  
Como o sistema deve lidar com livros danificados ou perdidos?

**Resposta:**  

**Ana:**  
- **Danificado:** registrar ocorrência e retirar de circulação  
- **Perdido:** vincular ao usuário e registrar responsabilidade  

**Rosa:**  
O operador registra, mas decisões finais podem exigir outro nível.

**Julia:**  
Usuário com perda fica bloqueado até regularização.

---

### 🔹 8. Pagamento de multas

**Pergunta:**  
O pagamento pode ser feito no sistema ou apenas presencialmente?

**Resposta:**  

**Ana:**  
O sistema deve **registrar o pagamento independentemente do canal**.

**Rosa:**  
Hoje o mais comum é pagamento presencial.

**Julia:**  
Pagamento online exige integração com gateway.

---

### 🔹 9. Cobrança por danos

**Pergunta:**  
Como é definido o valor de cobrança por danos?

**Resposta:**  

**Ana:**  
O valor é **definido manualmente**, conforme avaliação.

**Rosa:**  
Depende do grau do dano.

**Julia:**  
O sistema deve permitir registro detalhado da cobrança.

---

### 🔹 10. Procedimento de pagamento (Pix/cartão)

**Pergunta:**  
Como funciona o pagamento via Pix ou cartão?

**Resposta:**  

**Julia:**  

**Pix:**
- Geração de QR Code  
- Pagamento pelo usuário  
- Confirmação automática ou manual  
- Baixa da multa  

**Cartão:**
- Pagamento presencial ou online  
- Registro da transação  
- Atualização do status  

**Rosa:**  
No balcão, o operador registra manualmente.

**Ana:**  
O sistema deve manter histórico e garantir confirmação.

---

## 🧠 Conclusões da Aula

- O sistema exige forte controle de **reservas e prazos**  
- A **rastreabilidade** é essencial (pagamentos, perdas, danos)  
- Há necessidade de **regras claras de bloqueio de usuários**  
- Integrações externas (pagamentos) são um ponto crítico  
- Acessibilidade deve ser considerada desde o início  

---

✍️ **Observação:**  
A sessão JAD permitiu alinhar regras de negócio com diferentes perspectivas (gestão, operação e sistema), reduzindo ambiguidades e melhorando a definição dos requisitos.

---

## 🤖 Observação sobre o uso de IA

Este documento foi estruturado com o apoio de uma ferramenta de Inteligência Artificial, utilizada para organizar, padronizar e melhorar a clareza textual das informações coletadas durante a sessão JAD.

As perguntas, respostas e regras de negócio foram elaboradas com base na atividade realizada em aula, sendo a IA empregada exclusivamente como suporte na formatação do conteúdo e na revisão da escrita, sem alteração do significado original das informações.

O uso da IA teve como objetivo otimizar a apresentação do material, mantendo a fidelidade às discussões e decisões definidas pelos participantes.
