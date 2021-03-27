# Descrição do casos de uso

|   Data   |   Versão    |   Descrição   |    Autor    |
|:-------------:|:-------------:|:-------------:|:-------------:|
|   25/02/2021    |   1.0   |   Iniciação do documento.    |   Danilo Rafael   |

### **1 - Resumo**

   Permite ao Usuário, após o Login ou o Cadastro, o acesso ao Baralho(Revisão), Atividade, Acesso ao Perfil/Editar Perfil e, caso haja algum empecilho, Contatar.

### **2 - Atores**
   - Usuário
### **3 - Pre-condições**

   O Usuário deverá estar logado.

### **4 - Pós-condições**
   Caso haja interação em alguma página, dentre todas, será atualizado no banco de dados da determinada página.

### **5 - Fluxo de eventos**

#### **5.1 - Fluxo básico**
   1. [IN] O caso de uso começa quando o Usuário acessa a página e entra na sua conta.
   2. [IN] O Usuário poderá escolher uma página, seja o acesso do perfil/editar perfil, as atividades, baralho(revisão) ou a contatação dos administradores.
      
      2.1. [OUT] Se o Usuário interagir com alguma página, o banco de dados da página atualizará.
   3. [OUT] Caso a opção "Manter-se logado" não esteja habilitada, o Usuário sairá da sua conta após fechá-la.

### **6 - Protótipo(s) de interface do casos de uso**

