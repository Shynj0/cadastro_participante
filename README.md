# cadastro_participante

# Cadastro de Participante
 
Aplicativo Flutter com formulário de cadastro e validação de dados, desenvolvido como exercício da **Aula 5 – Formulários e validação** da disciplina de Programação para Dispositivos Móveis (Fatec).
 
## Sobre o projeto
 
O app possui duas telas:
 
- **Cadastro:** formulário com e-mail, nome, telefone e CPF, com validação de cada campo.
- **Resumo:** exibe os dados informados e permite voltar ao formulário para editá-los.
## Funcionalidades
 
- Formulário com `Form` e `TextFormField`
- Leitura e limpeza dos campos com `TextEditingController`
- Validação com mensagens de erro abaixo de cada campo
- Teclado adequado para cada tipo de dado (`keyboardType`)
- Avanço entre campos pela ação do teclado (`textInputAction`)
- Envio dos dados validados para a segunda tela
- Descarte dos controladores com `dispose()`
## Regras de validação
 
| Campo    | Regra                                                          |
|----------|----------------------------------------------------------------|
| E-mail   | Obrigatório e com estrutura básica válida (ex.: `ana@email.com`) |
| Nome     | Obrigatório, com pelo menos 3 caracteres (sem contar espaços das pontas) |
| Telefone | Obrigatório, no formato `DD-DDDDD-DDDD`                        |
| CPF      | Obrigatório, com exatamente 11 dígitos, sem pontos ou traço    |
 