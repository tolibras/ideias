# CriarConta - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 25/03/2021 |  1.0   | Primeira versão do documento. |  Todos  |

## **1 - Resumo**

   Permite criar sua conta no aplicativo.

## **2 - Atores**
   - _Usuário_ e _Administrador_.

## **3 - Pré-Condições
    - Usuário ou Administrador identificado no aplicativo.  

## **4 - Pós-condições**
   - Função disponível somente para o _Administrador_ e _Usuário_.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o _Ator_ acessa a página inicial.
   2. **[OUT]** O aplicativo apresenta sua proposta e o _Ator_ deve selecionar o botão "Começar".
   3. **[IN]** O _Ator_ digita suas informações para efetuar seu registro no aplicativo.
   5. **[OUT]** O aplicativo exige o código enviado para o email para concluir o
   6. O aplicativo registrará a conta do _Ator_ e o enviará para a tela inicial do TOLibras.

### **5.2 - Fluxo exceção**

#### **5.2.1 - Fluxo exceção limite de senha e email e nickname usados**
   1. **[OUT]** O aplicativo informa que o email ou o nickname estão sendo usados, ou há um limite de senha do qual foi ultrapassada.
   2. O aplicativo mostra uma mensagem alertando ao _Ator_ do empecilho.
   3. Caso a senha esteja sendo ultrapassada, o aplicativo alertará na tela de cadastro.
   4. Caso o email esteja sendo utilizado, o aplicativo alertará na tela de cadastro.
   5. Caso o nickname esteja sendo utilizado, o aplicativo alertará na tela de cadastro.
   
### **6 - Protótipo(s) de interface do casos de uso**

1. Cadastro
