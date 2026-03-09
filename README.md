Análise da tela de criação de conta

Contas cadastradas de forma indevida:
Ao clicar no botão "Criar conta" e clicar novamente em "Criar conta", mesmo sem preencher nenhum dos campos da tela, 
o sistema emite a mensagem "Conta criada com sucesso". 
Todos os campos desta tela precisam ser de preenchimento obrigatório. 
Severidade: Crítico / Alta prioridade

Confirmação de senha: 
O sistema está permitindo a criação de conta com dados divergentes nos campos "Senha" e "Confirmar senha".
É preciso que estes campos sejam comparados e que ocorra uma validação no momento da criação da conta.
Severidade: Crítico / Alta prioridade

Campo preenchido com valores inválidos:
O campo "Telefone" não possui nenhum tipo de validação. 
O sistema já exibe corretamente o modelo com a quantidade certa de numerais a ser digitado. 
É preciso criticar e informar ao usuário que a quantidade preenchida está incorreta.
Severidade: Médio / Média prioridade

Campo preenchido com valores inválidos:
O campo "E-mail" não possui nenhum tipo de validação. 
O sistema já exibe corretamente o modelo com o preenchimento ideal do campo. 
É preciso criticar e informar ao usuário que o campo não foi preenchido com um e-mail válido.
Severidade: Médio / Média prioridade

Campo preenchido sem os requisitos necessários:
A página informa a seguinte mensagem: "A senha precisa ter no mínimo 8 caracteres e 1 caractere especial". 
Atualmente os campos "Senha" e "Confirmar senha" permitem senhas sem a quantidade mínima indicada na mensagem e sem o caractere especial. 
Ambos precisam de uma validação de acordo com esta regra.
Severidade: Médio / Média prioridade

Ajuste visual:
Identifiquei que os campos "Telefone" e "Confimar senha" estão com seus quadros desalinhados.
Precisam ser alinhados de acordo com o quadro principal da tela.
Severidade: Baixo / Baixa prioridade


Análise da tela de Login

Login efetuado de forma indevida:
O sistema está permitindo a criação de conta com todos os campos em branco, como foi mencionado na listagem anterior. 
Quando isso ocorre, ao acessar a tela de login e clicar em "Entrar", a página informa que o "Login foi realizado com sucesso", 
mesmo com os campos de e-mail e senha em branco.
Ambos os campos precisam ser de preenchimento obrigatório.
Severidade: Crítico / Alta prioridade

Mensagem incorreta exibida ao usuário: 
O sistema exibe a seguinte mensagem quando informamos um e-mail cadastrado corretamente e digitamos a senha incorreta: 
"Conta não encontrada. Crie uma conta primeiro"
A mensagem a ser exibida deve ser: "Senha incorreta. Tente novamente".
Severidade: Médio / Média prioridade

Bug na conclusão do login:
Ao realizar o login com e-mail e senha preenchidos corretamente o sistema informa que o Login foi efetuado com sucesso, 
mas no canto inferior direito da tela é exibida a mensagem "Erro inesperado" em vermelho. 
É preciso retirar esta mensagem da tela após a conclusão do login.
Severidade: Médio / Baixa prioridade (Considerando que a mensagem de fato não impede o login e a possível sequência do processo)

Os erros críticos de alta prioridade precisam ser corrigidos imediatamente. A criação de contas com campos não preenchidos gera cadastros incompletos e por tanto ineficazes. A realização do login sem o preenchimento dos campos é uma falha grave de segurança, bem como cadastros efetuados com diferentes senhas. 
