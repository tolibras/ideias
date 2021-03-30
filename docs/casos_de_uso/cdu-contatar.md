# Contatar - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 25/03/2021 |  1.0   | Primeira versão do documento. |  All  |

## **1 - Resumo**

   Permite contatar os Criadores do TOLibras, enviando uma mensagem.

## **2 - Atores**
   - _Usuário_ e _Administrador_.

## **3 - Pré-Condições
    - _Administrador_  e _Usuário_ identificados no aplicativo.  

## **4 - Pós-condições**
   - Função disponível somente para o _Administrador_ e _Usuário_.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o Ator está em alguma página.
   2. **[OUT]** O aplicativo apresenta a tela de identificação.
   3. **[IN]** O _Ator_ digita login e senha e clica em identificar-se.
   4. O aplicativo verifica se o login e senha estão corretos.
   5. **[OUT]** O aplicativo abre a tela inicial do toLibras. 

### **5.2 - Fluxo exceção**

#### **5.2.1 - Fluxo exceção caso esteja na página de atividades**
  
   1. **[OUT]** O aplicativo não mostra a tela no qual há a comunicação.
   2. O aplicativo não disponibilizará o contatar, somente, durante a realização de uma atividade.

### **6 - Protótipo(s) de interface do casos de uso**

1. contatar
