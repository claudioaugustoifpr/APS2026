
# Refinamento do Levantamento de Requisitos - Entrevista Presencial

## Observações da Lu
- A Lu comentou que estamos perguntando sem considerar um histórico anterior, porém já temos informações dos outros questionários online realizados, inclusive foram realizadas duas versões de levantamento de requisitos via questionário.
- Foram realizadas duas perguntas para a Júlia, que encaminhou para a Rosa, que também não soube responder. Para otimizar, a pergunta foi direcionada à Ana.

---

## Perguntas e Respostas

### Perguntas para Ana

1. **Qual o limite de renovação para os usuários?**  
   **Resposta:** Renovação é permitida **uma única vez** por empréstimo e fica bloqueada se houver atraso.

2. **Sobre o prazo de 3 dias da reserva: se vencer em domingo ou feriado, o prazo é estendido ou o livro retorna?**  
   **Resposta:** O prazo é de **2 dias úteis**, então domingo e feriado não contam. O prazo se estende automaticamente para o próximo dia útil.

3. **Quais tipos de notificação devem existir no novo sistema? A partir de quando o sistema começará a realizar as notificações?**  
   **Resposta:** Isso não é definido por mim; é uma decisão a ser tomada no levantamento de requisitos. O que posso afirmar é que o sistema precisa notificar sobre:
   - Vencimento de prazo de empréstimo.  
   - Disponibilidade de reserva.

---

### Perguntas para Júlia

1. **Existe algum procedimento especial quando um usuário não retira o livro reservado dentro do prazo?**  
   **Resposta:**  
   - Quando um usuário faz uma reserva, o livro fica separado para ele.  
   - O prazo exato para retirada não foi confirmado (possivelmente 3 ou 5 dias).  
   - Se o usuário não retira dentro do prazo, a reserva é **cancelada automaticamente** e o livro volta para a fila de espera.  
   - Júlia tem certeza apenas sobre o controle após o empréstimo: 7 dias de prazo e multa de R$1,00 por dia de atraso.  
   - Para informações precisas sobre prazos de reserva, recomenda-se perguntar para **Ana** ou **Rosa**, que lidam diretamente com essas regras do sistema.

2. **Qual é o limite máximo de reservas simultâneas por usuário?**  
   **Resposta:**  
   - Não há certeza de um limite específico; possivelmente cada usuário pode reservar quantos livros quiser.  
   - Pode haver variação de acordo com o tipo de usuário (aluno, professor, etc.).  
   - Ana ou Rosa teriam informações precisas, pois cuidam das configurações do sistema.  
   - Para registrar uma reserva, o livro precisa estar indisponível; o número máximo de reservas simultâneas por usuário ainda não é confirmado.

---

### Perguntas para Rosa

1. **Qual é o limite máximo de reservas simultâneas por usuário?**  
   **Resposta:** Não lembro ao certo. No dia a dia gerenciamos, mas os números específicos de limite de reserva devem ser confirmados com a **Ana**, que cuida da política de reservas.

2. **Quais são os principais problemas ou situações críticas que ocorrem no atendimento da biblioteca?**  
   **Resposta:**  
   - Atrasos na devolução de livros, gerando multas.  
   - Livros fora de circulação por danos, prejudicando outros usuários.  
   - Controle manual pesado e trabalhoso.  
   - Para detalhar melhor como isso afeta o sistema novo, é recomendado conversar com **Ana**, que acompanha tudo mais de perto.
