# pas2
#Introdução
O IPConnect é uma aplicação criada para simplificar a vida académica.
Nasceu da necessidade de centralizar informação e serviços do campus numa única plataforma intuitiva, reduzindo burocracias e a dispersão entre vários sistemas.
O nosso objetivo é aproximar estudantes e instituições através da tecnologia, devolvendo tempo para o que realmente importa: aprender, crescer e viver a experiência académica ao máximo.


#Funcionalidades
A IPConnect foi desenvolvida para centralizar tudo o que o estudante precisa no dia a dia académico, de forma simples e eficiente:
Horários atualizados: Consulta rápida e sempre sincronizada com o plano académico
Notas académicas: Acesso fácil ao desempenho em cada unidade curricular
Chat integrado: Comunicação direta entre estudantes, professores e serviços académicos
Alertas importantes — Notificações sobre prazos, faltas e informações relevantes
Tudo num só lugar, para uma experiência de campus mais organizada e sem complicações.


#Tecnologias utilizadas 
O IPConnect foi desenvolvido com:
HTML
PHP 
Kotlin 


#RoadMap
O Roadmap começa com a necessidade de criar uma ponte entre a administração de uma escola e os alunos através de uma aplicação móvel. 
No início, focamos nos na estrutura da base de dados onde definimos como seriam guardados os utilizadores, os cursos e os horários de cada turma. 
Depois de garantirmos que os dados estavam bem organizados no MySQL, avançamos para o motor do sistema em PHP, criando um login inteligente que serve tanto para o site como para a aplicação Android, respondendo com ficheiros JSON quando necessário.
Na seguinte fase, o foco passou para a interface do administrador. Começamos com algo muito básico e fomos evoluindo para um design de alta qualidade que utiliza uma barra lateral fixa para facilitar a navegação. Implementamos cartões que mostram estatísticas em tempo real e criamos um sistema de janelas flutuantes, chamadas modais, para que o administrador consiga mudar a password de qualquer aluno rapidamente sem ter de saltar de página em página. No final, adicionamos os botões de ação rápida que permitem apagar utilizadores ou horários com apenas um clique e um aviso de confirmação.
Este sistema é seguro porque utiliza sessões protegidas e um script de logout que limpa todos os dados de acesso antes de fechar a conta.
