Funcionalidade  - Preencher formulário 1 e enviar
Como um usuário do sistema
Quero preencher o formulário
Para a exibir uma mensagem de envio em um modal

Cenário: Enviar formulário com sucesso.
Dado que acessei o sistema;
Quando preencher o nome, sobrenome e telefone no formulário 1;
E clicar em enviar;
Então  deverá ser exibido um modal com a mensagem "Enviado com sucesso".

Cenário: Exibir a mensagem de obrigatoriedade de preenchimento de todos os campos.
Dado que acessei o sistema;
Quando preencher o apenas telefone no formulário 1;
E clicar em enviar;
Então deverá ser exibida mensagem "Campos obrigatórios não foram preenchidos".

Cenário: Exibir a mensagem de preenchimento do campo telefone inválido.
Dado que acessei o sistema;
Quando preencher o nome, sobrenome  no formulário 1;
E preencher o telefone com formato inválido;
E clicar em enviar;
Então  deverá ser exibida a mensagem "Formato do telefone inválido", abaixo do campo telefone

Cenário: Exibir a mensagem de preenchimento do campo nome inválido.
Dado que acessei o sistema;
Quando preencher o nome com 2 caracteres, sobrenome e telefone  no formulário 1;
E clicar em enviar;
Então  deverá ser exibida a mensagem "Campo nome deve ter mais de 2 caracteres", abaixo do campo nome.

Cenário: Fechar o modal.
Dado que acessei o sistema;
Quando preencher o nome, sobrenome e telefone  no formulário 1;
E clicar em enviar;
E clicar no botão fechar no modal exibido;
Então  o modal de verá ser fechado.

Funcionalidade  - Alterar a cor de fundo do formulário 2
Como um usuário do sistema
Quero selecionar uma cor
Para que a cor de fundo seja alterada.

Cenário: Alterar a cor do formulário 2 para Azul.
"Dado que acessei o sistema;
Quando clicar no combobox no formulário 2;
E clicar na opção Azul;
Então  a cor do formulário 2 deve ser alterada para Azul."

Cenário: Alterar a cor do formulário 2 para Amarelo.
"Dado que acessei o sistema;
Quando clicar no combobox no formulário 2;
E clicar na opção Amarelo;
Então  a cor do formulário 2 deve ser alterada para Amarelo."

Cenário: Alterar a cor do formulário 2 para Vermelho.
"Dado que acessei o sistema;
Quando clicar no combobox no formulário 2;
E clicar na opção Vermelho;
Então  a cor do formulário 2 deve ser alterada para Vermelho."

Cenário: Alterar a cor do formulário 2 para Branco.
"Dado que acessei o sistema;
Quando clicar no combobox no formulário 2;
E clicar na opção Selecione um item;
Então  a cor do formulário 2 deve ser alterada para Branco."

Funcionalidade  - Exibir saudação no formulário 3
Como um usuário do sistema
Quero clicar em saudação
Para que a saudação seja exibida.

Cenário: Exibir uma saudação de "Bom dia"
Dado que acessei o sistema;
Quando clicar no botão Saudação no formulário 3 entre os horários 0:00 hs e 11:59hs;
Então  deve ser exibido um modal com a mensagem de Bom dia

Cenário: Exibir uma saudação de "Boa tarde"
Dado que acessei o sistema;
Quando clicar no botão Saudação no formulário 3 entre os horários 12:00 hs e 17:59hs;
Então  deve ser exibido um modal com a mensagem de Boa tarde.

Cenário: Exibir uma saudação de "Boa noite"
Dado que acessei o sistema;
Quando clicar no botão Saudação no formulário 3 entre os horários 18:00 hs e 23:59hs;
Então  deve ser exibido um modal com a mensagem de Boa noite.
