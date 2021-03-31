# EditarPerfil - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 25/03/2021 |  1.0   | Primeira versão do documento. |  All  |

## **1 - Resumo**

   Permite ao _Ator_ alterar suas informações da conta, seja seu "Nickname", email, senha e sua foto.

## **2 - Atores**
   - _Usuário_ e _Administrador_.

## **3 - Pré-Condições
    - Administrador e Usuário identificados no aplicativo.     

## **4 - Pós-condições**
   - Função disponível somente para _Usuário_ e _Administrador_.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o _Ator_ acessa a página de alteração das informações do perfil.
   2. **[OUT]** O aplicativo apresenta quais opções são disponíveis para serem mudadas.
   3. **[IN]** O _Ator_ Digita e altera o campo no qual escolheu.
   5. **[OUT]** O aplicativo atualiza sua página e suas informações.
   4. O aplicativo por fim, salva os dados no banco de dados.
   
### **6 - Protótipo(s) de interface do casos de uso**

1. Edição do perfil.
![Frame 56](https://user-images.githubusercontent.com/54066949/113218233-91bead00-9255-11eb-846e-a1c05b3a4ad5.png)
