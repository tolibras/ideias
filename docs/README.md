# Documentos
* [Mapa do site](#mapa-do-site)
* [Casos de uso](#casos-de-uso)
* [Descrição de Casos de uso](#descrição-do-casos-de-uso)
* [Documento de visão](#documento-de-visão)
* [Documento de requisitos](#documento-de-requisitos)
# Mapa do site

![Mapa_site](mapa_do_site_tolibras.jpeg)

# Casos de uso

![Casos de uso](casos_de_uso.jpeg)

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

#### **5.2 - <Nome do fluxo alternativo 1>**
   Não há fluxos alternativos.
   
#### **5.3 - <Nome do fluxo de exceção 1>**
   Não há fluxos de exceções.

### **6 - Protótipo(s) de interface do casos de uso**

Acessar perfil/editar perfil
Atividade
Atividades
Contatar
Cadastro

# Documento de visão

* **Descrição do problema:**

|         |            | 
| ------------- |:-------------:|
| **O problema da**      | Falta de investimento na política de inclusão aos surdos e deficientes auditivos no meio acadêmico. | 
| **Afeta**      | Pessoas ouvintes, deficientes auditivos e surdos.     |
| **Cujo impacto é** | A dificuldade no processo de ensino-aprendizagem.      |
| **Uma boa solução seria** | Criação de um site, como o ToLIBRAS, que ensine, de forma lúdica, alguém que não tenha domínio da linguagem.      |

*  **Descrição dos usuários:**

|   Nome      |   Descrição    |   Responsabilidade   | 
| ------------- |:-------------:|:-------------:|
| Aluno      | Usuário que poderá acessar o conteúdo de aprendizagem do ToLIBRAS, para que o mesmo estude LIBRAS.  |   O Aluno será, em suma, o usuário principal do site, visto que a criação do mesmo visa em ajudar alunos que têm interesse em aprender LIBRAS.    |

* **Descrição do ambiente dos usuários:**

    Pela razão do ToLIBRAS ser um site, o ambiente de usuário é amplo e pode ser qualquer e todo lugar, desde que haja acesso à
internet e a um navegador.

* **Principais necessidades dos usuários:**

    A imprescindibilidade de aprender LIBRAS para os ajudar na comunicação com deficientes auditivos, seja em ambiente escolar, de
trabalho ou acadêmico. Outra necessidade que o usuário possuirá, ainda, será um site que ensine de forma eficaz, rápida e gratuita, a linguagem
de sinais.

* **Alternativas concorrentes:**

    Atualmente, há o site InLIBRAS (inLIBRAS.com.br). Esse site foi desenvolvido por alunos do curso de ciência da computação e foca
suas funções em torno do público infantil surdo e público ouvinte (com ajuda para aprender LIBRAS). Além disso, é apresentado ao usuário
diversas informações a respeito da Língua Brasileira de Sinais. É um site com muito foco em informar o usuário, auxiliando tanto surdos quanto
ouvintes na informação quanto à surdez ou deficiência auditiva. Entretanto, o InLIBRAS é limitado na questão de ensinar aos ouvintes sobre
LIBRAS, tendo apenas dois ambientes apresentados (parque e cozinha).
    
    Outros que também ideias semelhantes seriam o StorySign, que ensina uma criança com problema auditivo a ler histórias infantis,
o VLIBRAS, que traduz, por meio de um avatar, um texto selecionado de português para LIBRAS, e, por último, o Hand Talker, que auxilia pessoas
que não sabem LIBRAS através de videoaulas sobre um assunto especifico. 

* **Visão geral do produto:**

     O ToLIBRAS é uma plataforma online e gratuita que tem como principal função ensinar o usuário a aprender LIBRAS, por meio de
atividades (separadas por categorias) referentes a temas essenciais no aprendizado de um novo idioma.
     
     A metodologia utilizada pelo site seria a Gamificação, utilizando mecanismos e características de jogos, tendo como recompensas
por concluir tarefas e punições por errá-las, para motivar e facilitar o aprendizado aos usuários. 

# Documento de requisitos

   **1) Visão geral de produto:**

   O ToLIBRAS é uma plataforma online e gratuita que tem como principal
   função ensinar o usuário a aprender LIBRAS, por meio de atividades (separadas por categorias)
   referentes a temas essenciais no aprendizado de um novo idioma. A metodologia utilizada pelo site
   seria a Gamificação, utilizando mecanismos e características de jogos, tendo como recompensas
   por concluir tarefas e punições por errá-las, para motivar e facilitar o aprendizado aos usuários.

   **2) Requisitos funcionais**

   |     Código    |     Nome       |     Descrição      |     Categoria (Evidente/Oculto)       |
   |:-------------:|:-------------:|:-------------:|:-------------:|
   | RF1 | Editar perfil. |    Editar informações pessoais do perfil.    |  Evidente   |
   | RF2 | Fazer login/cadastro.   |    Realizar cadastro/acessar perfil logado.    |  Evidente   |
   | RF3 | Adicionar amigos.    |   Adicionar amigos para acompanhar seus progressos.   |  Evidente   |
   | RF4 | Realizar os exercícios.      |    Realizar os exercícios disponibilizados pelo ToLIBRAS.    |  Evidente   |
   
   **3) Requisitos não-funcionais**
   
   |     Código    |     Nome       |     Descrição      |     Categoria      |     Classificação      |
   |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
   | RNF1 | Protocolo HTTPS. |    Protocolo seguido nas páginas web.    |  Segurança   |  Obrigatório   |
   | RNF2 | Animações Javascript.   |    Animações para dinamizar o ambiente da plataforma.    |  Desenvolvimento   |  Desejável   |
   | RNF3 | Criptografar informações pessoais.    |   Proteger informações pessoais.   |  Segurança   |  Obrigatório   |
   | RNF4 | Linguagem ASP.NET   |    Todo o sistema deve ser feito com a linguagem ASP.   |  Implementação   |  Obrigatório   |
   | RNF5 | Somente para navegadores   |    O site deve funcionar, preferencialmente, em um navegador.   |  Portabilidade   |  Obrigatório   |
   | RNF6 | Backup do sistema   |    O sistema deverá gerar um backup a cada 24 horas.   |  Segurança   |  Desejável   |
   | RNF7 | Model, View, Controller   |    O site terá como padrão o modelo MVC em suas páginas.   |  Padrão   |  Obrigatório   |
   | RNF8 | Design responsivo   |    O site se adaptará em qualquer dispositivo como PC, Celular, Tablet.   |  Usabilidade   |  Obrigatório   |
   
   **4) Tabela de referência de requisitos FUNCIONAIS x requisitos NÃO FUNCIONAIS**
   
   |     /    |     RNF1     |     RNF2      |     RNF3     |     RNF4     |     RNF5     |     RNF6     |     RNF7     |     RNF8     |
   |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
   | RF1 | X | X | X | X | X | X | X | X |
   | RF2 | X |  | X | X | X |  | X | X |
   | RF3 | X | X |  | X | X | X | X | X |
   | RF4 | X | X |  | X | X | X | X | X |
