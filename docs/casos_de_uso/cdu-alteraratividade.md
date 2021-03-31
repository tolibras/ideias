# AlterarAtividade - Descrição do casos de uso

|    Data    | Versão |           Descrição           | Autor |
| :--------: | :----: | :---------------------------: | :---: |
| 27/03/2021 |  1.0   | Primeira versão do documento. |  All  |
| 31/03/2021 |  1.1   | Revisado Pré, Pós e Fluxo básico | Minora |

## **1 - Resumo**

   Permite ao _Administrador_ alterar as informações de uma atividade.

## **2 - Atores**
   - _Administrador_.

## **3 - Pré-Condições
    - Administrador identificado no aplicativo. CDU Login.
    - Administrador deve ter selecionado uma Atividade. CDU ListarAtividade ou FiltrarAtividade.

## **4 - Pós-condições**
   - Atividade modificada com sucesso.

## **5 - Fluxo de eventos**

### **5.1 - Fluxo básico**
   1. **[IN]** O caso de uso começa quando o _Administrador_ seleciona uma atividade para editar.
   2. **[OUT]** O aplicativo apresenta as informações da atividade.
   3. **[IN]** O _Administrador_ modificará as informações da atividade.
   4. **[OUT]** O aplicativo registra a modificação das informações da atividade.
   5. **[OUT]** O aplicativo informa ao Administrador que foi registrado as modificações da atividade.

### **5.2 - Fluxo alternativos**

#### **5.2.1 - Fluxo alternativo usuário não cadastrado**
   Fluxo alternativo para **passo 4** do Fluxo Principal.
   1. Executar o casos de uso _RemoverAtividade_.
   2. Executar o casos de uso _DisponibilizarAtividade_.

#### **5.3.1 - Fluxo alternativo Opções da atividade em grupo do _Administrador_**
   Fluxo alternativo para **passo 4** do Fluxo Principal:
   1. **[IN]** O _Administrador_ observa 2 opções além a de alterar a atividade, elas são: Remover Atividade e Disponibilizar atividade.
   2. **[OUT]** Caso o _Administrador_ selecione o botão "Remover Atividade", a atividade será automaticamente removida.
   3. **[OUT]** Caso o _Administrador_ selecione o botão "Disponibilizar Atividade", a atividade será automaticamente disponibilizada para o grupo de _Usuários_.

### **6 - Protótipo(s) de interface do casos de uso**

1. opções dos botões da atividade do _Administrador_.
