# DisponibilizarAtiv - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 27/03/2021 |  1.0   | Primeira versão do documento. |  All  |

## **1 - Resumo**

   Permite ao _Administrador_ disponibilizar uma atividade para o grupo de _Usuários_.

## **2 - Atores**
   - _Administrador_

## **3 - Pré-Condições
    - Administrador identificado no aplicativo.     

## **4 - Pós-condições**
   - Função disponível somente para o _Administrador_.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o _Administrador_ acessa a página de definir uma atividade.
   2. **[OUT]** O aplicativo apresenta umas informações para serem preenchidas.
   3. O aplicativo cria a atividade.
   4. **[OUT]** O aplicativo fornece a opção de disponibilizar a atividade.

### **5.2 - Fluxo alternativos**

#### **5.2.1 - Fluxo alternativo usuário não cadastrado**
   Fluxo alternativo para **passo 4** do Fluxo Principal.
   1. Executar o casos de uso _AlterarAtividade_.
   2. Executar o casos de  uso _RemoverAtividade_.

#### **5.3.1 - Fluxo alternativo Opções da atividade em grupo do _Administrador_**
   Fluxo alternativo para **passo 4** do Fluxo Principal:
   1. **[IN]** O _Administrador_ observa 2 opções além a de alterar a atividade, elas são: Alterar Atividade e Disponibilizar atividade.
   2. **[OUT]** Caso o _Administrador_ selecione o botão "Alterar Atividade", a atividade será automaticamente direcionada para a tela de edição..
   3. **[OUT]** Caso o _Administrador_ selecione o botão "Remover Atividade", a atividade será automaticamente removida.

### **6 - Protótipo(s) de interface do casos de uso**

1. opções dos botões da atividade do _Administrador_.