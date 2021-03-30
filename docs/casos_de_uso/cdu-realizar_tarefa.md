# RealizarTarefa Descrição do casos de uso

|   Data   |   Versão    |   Descrição   |    Autor    |
|:-------------:|:-------------:|:-------------:|:-------------:|
|   25/02/2021    |   1.0   |   Iniciação do documento.    |   Danilo Rafael   |

### **1 - Resumo**

   Permite ao _Ator_, após o Login ou o Cadastro, o acesso ao Baralho(Revisão), Atividade, Acesso ao Perfil/Editar Perfil e, caso haja algum empecilho, Contatar.

### **2 - Atores**
   - _Usuário_ e _Administrador_.
   
### **3 - Pre-condições**
   - _Administrador_ e _Usuário_ identificados no aplicativo. 

### **4 - Pós-condições**
   Caso haja interação em alguma página, dentre todas, será atualizado no banco de dados da determinada página.

### **5 - Fluxo de eventos**

#### **5.1 - Fluxo básico**
   1. [IN] O caso de uso começa quando o _Ator_ acessa a página e entra na sua conta.
   2. [IN] O _Ator_ poderá escolher uma página, seja o acesso do perfil/editar perfil, as atividades, baralho(revisão) ou a contatação dos administradores.
      
      2.1. [OUT] Se o _Ator_ interagir com alguma página, o banco de dados da página atualizará.
   3. [OUT] Caso a opção "Manter-se logado" não esteja habilitada, o _Ator_ sairá da sua conta após fechá-la.

### **6 - Protótipo(s) de interface do casos de uso**

