# LOGIN - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 18/03/2021 |  1.0   | Primeira versão do documento. |  All  |

## **1 - Resumo**

   Permite o _Ator_ se identificar no aplicativo.

## **2 - Atores**
   - _Usuário_ e _Administrador_

## **4 - Pós-condições**
   - _Usuário_ e _Administrador_ identificados no aplicativo.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o _Ator_ acessa a página de login.
   2. **[OUT]** O aplicativo apresenta a tela de identificação.
   3. **[IN]** O _Ator_ digita login e senha e clica em identificar-se.
   4. O aplicativo verifica se o login e senha estão corretos.
   5. **[OUT]** O aplicativo abre a tela inicial do toLibras. 

### **5.2 - Fluxo alternativos**

#### **5.2.1 - Fluxo alternativo Ator não cadastrado**
   Fluxo alternativo para **passo 3** do Fluxo Principal.
   1. Executar o casos de uso _Cadastrar-se_.
   
#### **5.2.2 - Fluxo alternativo Ator esqueceu login ou senha**
   Fluxo alternativo para **passo 3** do Fluxo Principal:
   1. **[IN]** O _Ator_ clica em _esqueci longin e/ou senha_.
   2. **[OUT]** O aplicativo abre uma tela de esqueci login/senha.
   3. **[IN]** O _Ator_ digita seu email.
   4. **[OUT]** O aplicativo envia um código para o email do _Ator_
   5. **[OUT]** O aplicativo informa que foi enviado email para o _Ator_

### **5.3 - Fluxo exceção**

#### **5.3.1 - Fluxo exceção login e/ou senha errados**
   Fluxo alternativo para **passo 4** do Fluxo Principal.
   1. **[OUT]** O aplicativo informa que login e/ou senha estão errados
   2. O aplicativo incrementa o número de tentativas de identificação
   3. Caso número menor ou igual a 3, retorna para o _passo 2_ do Fluxo Principal
   4. Caso número maior que 3, 
      1. O aplicativo bloqueia o _Ator_ é bloqueado.
      2. **[OUT]** aplicativo envia email para o _Ator_ com código para modificar senha.
      3. **[OUT]** O aplicativo informa que o _Ator_ esta bloqueado.

### **6 - Protótipo(s) de interface do casos de uso**

1. login
2. esqueci login/senha
