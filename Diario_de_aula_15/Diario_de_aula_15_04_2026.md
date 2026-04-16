# História de Usuário

**Como** aluno,  
**eu gostaria** de receber notificações de livros que tenho interesse quando estiverem disponíveis para empréstimo e de prazo para a devolução dos livros que já peguei emprestado,  
**para que** eu possa acompanhar a disponibilidade e evitar multas por atraso.

---

# Cenários

## Cenário 1: Notificação de disponibilidade de livro

**Dado que** o livro que estava emprestado seja devolvido,  
**Quando** o sistema registrar a devolução,  
**Então** o aluno interessado receberá uma notificação informando que o exemplar já está disponível.

---

## Cenário 2: Notificação de vencimento de prazo

**Dado que** o livro emprestado tenha prazo de 7 dias,  
**Quando** estiver próximo do vencimento,  
**Então** o sistema enviará uma notificação alertando sobre o prazo de devolução e a possibilidade de multa caso ultrapasse o prazo.

---

## Cenário 3: Cancelamento de reserva por inatividade

**Dado que** o aluno foi notificado que o livro está disponível,  
**E** o aluno não realizou a retirada em até 3 dias úteis,  
**Então** o sistema enviará uma notificação informando que a reserva foi cancelada,  
**E** o livro ficará disponível novamente para empréstimo ou nova reserva.

---

## Cenário 4: Renovação de empréstimo por professor

**Dado que** o aluno deseja reservar um livro que está emprestado a um professor,  
**Quando** o professor renovar o empréstimo,  
**Então** o aluno receberá uma notificação informando que o livro continua emprestado,  
**E** será informado o novo prazo de devolução após a renovação.
