# LOGIN - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 25/03/2021 |  1.0   | Primeira versão do documento. |  Todos  |

## **1 - Resumo**

   Permite ao Usuário criar sua conta no aplicativo.

## **2 - Atores**
   - _Usuário_

## **4 - Pós-condições**
   - _Usuário_ deverá preencher as informações requisitadas para ser identificado no aplicativo. 

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o Usuário acessa a página inicial.
   2. **[OUT]** O aplicativo apresenta sua proposta e o usuário deve selecionar o botão "Começar".
   3. **[IN]** O _Usuário_ digita suas informações para efetuar seu registro no aplicativo.
   5. **[OUT]** O aplicativo exige o código enviado para o email para concluir o
   6. O aplicativo registrará a conta do usuário e o enviará para a tela inicial do TOLibras.

### **5.2 - Fluxo exceção**

#### **5.2.1 - Fluxo exceção limite de senha e email e nickname usados**
   1. **[OUT]** O aplicativo informa que o email ou o nickname estão sendo usados, ou há um limite de senha do qual foi ultrapassada.
   2. O aplicativo mostra uma mensagem alertando ao _Usuário_ do empecilho.
   3. Caso a senha esteja sendo ultrapassada, o aplicativo alertará na tela de cadastro.
   4. Caso o email esteja sendo utilizado, o aplicativo alertará na tela de cadastro.
   5. Caso o nickname esteja sendo utilizado, o aplicativo alertará na tela de cadastro.
### **6 - Protótipo(s) de interface do casos de uso**

1. Cadastro
