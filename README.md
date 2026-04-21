# Software Architecture - 20/21 (FCTUC)

## Propósito
O objetivo deste Software Requirements Specification (SRS) é definir e detalhar os requisitos associados ao sistema Flip Framework. Com este documento pretendemos clarificar quais as funcionalidades associadas ao sistema e os requisitos associados, de acordo com as necessidades do potencial cliente e utilizadores. Sendo este documento criado no contexto da unidade curricular de Engenharia de Requisitos, o público alvo deste documento são os docentes da cadeira, Mário Rela e Bruno Cabral que irão avaliar o desempenho do grupo. A Universidade de Coimbra também é considerada como público alvo, já que é o potencial cliente do sistema.

## Âmbito do Projeto
A Flip Framework será uma aplicação web que irá auxiliar a aprendizagem no ensino à distância. Com esta aplicação pretende-se englobar num único sistema, a partilha de conteúdos programáticos (áudio, vídeo, texto, imagens, código, entre outros essenciais). Por outro lado, oferece à comunidade um espaço destinado a preencher lacunas de outras aplicações/serviços, tais como esclarecimento de dúvidas, auxílio ao trabalho em grupo e comunicação entre alunos e docentes.

Neste caso, o âmbito do problema está limitado ao contexto universitário na Universidade de Coimbra.

Em termos do alcance da plataforma, não temos intenção de criar funcionalidades de comunicação com os serviços académicos em si. Ou seja, a aplicação está destinada à relação docente-aluno, não tendo uma vertente relacionada com assuntos financeiros, candidaturas, inscrições e derivados.

Em contexto de pandemia, uma aplicação de software deste género é essencial ao funcionamento próprio de atividades porque providencia o ensino à distância e, no processo, evita contactos presenciais.

Seguem-se alguns exemplos de cenários em que a nossa plataforma pretende contribuir:

• Vídeo-Aula - Com o sistema desenvolvido será possível fazer streaming e gravação de aulas para garantir a passagem de conteúdos aos alunos.

• Partilha de materiais - Também irá permitir a partilha de documentos e outros materiais de ensino.

• Colocar e Tirar Dúvidas - Será possível aos alunos esclarecerem as suas dúvidas de forma direta. Por outro lado, os docentes conseguem responder sem quaisquer constrangimentos, de forma ordenada.

• Trabalho em grupo - O Flip Framework servirá para a criação, gestão e comumicação de grupos de trabalho. Permitirá assim o bom funcionamento de trabalhos desta natureza.

## Perspectiva do Produto

No momento de pandemia actual, muitas universidades portuguesas, especificamente a Universidade de Coimbra, têm sentido dificuldades relativamente ao ensino à distância, sobretudo no que concerne à partilha de conteúdos, tanto pelos alunos como pelos docentes. Estes problemas provocam mau aproveitamento escolar, frustrações por parte da comunidade e perdas de tempo à procura de soluções.

As aplicações já existentes no mercado não estão a responder com a qualidade esperada, apresentando diversas lacunas nos seus serviços. Por exemplo, muitas delas têm problemas de organização e não possuem ferramentas para expor dúvidas por parte dos alunos.

A nossa aplicação pretende integrar-se num espaço de elevada relevância dado o contexto apresentado. As necessidades envolvidas neste ainda não foram resolvidas pelas soluções atuais e daí querermos apresentar a nossa proposta que a visa a resolver as problemas atualmente em aberto. Os motivos que nos levaram a criar esta plataforma são:

• Centralização de serviços - A plataforma pretende centralizar vários serviços essenciais já existentes (vídeo-aula, partilha de materiais e trabalhos, formação de grupos, entre outros) de forma a minimizar a utilização multi-plataforma atualmente imposta (uso simultâneo de plataformas como Zoom, UCStudent, Inforestudante, Slack, etc) e facilitar a gestão académica para ambos os perfis de utilizador, estudante e docente.

• Resolução de novos desafios - A plataforma também pretende resolver problemas que surgiram com o contexto de pandemia atual como o esclarecimento de dúvidas, auxílio ao trabalho em grupo e facilitar a comunicação em geral entre estudante-docente - problemas que ainda não foram adequadamente resolvidos pelas soluções atuais. Pretendemos, neste sentido, dinamizar a interação dos utilizadores à distância através da possibilidade de formação de grupos com docentes e/ou alunos sob a forma de um chat e também conter uma secção específica na plataforma para colocamento de dúvidas a um docente, sem estar em aula e sem ter de marcar uma reunião.

## Funções do Produto

As funcionalidades definidas foram criadas em função dos utilizadores identificados: estudante e docente. Devido à natureza de ambos terá de existir funcionalidades tanto exclusivas, como mútuas entre estes.

A plataforma pretende providenciar a ambos os utilizadores a capacidade de criar e gerir grupos de trabalho. Estes podem ser criados e constituídos por alunos e/ou docentes. Após a formação de um grupo os utilizadores poderão interagir via chat e partilhar materiais. Outra funcionalidade em comum será uma agenda, onde os utilizadores poderão visualizar e adicionar compromissos à mesma. A plataforma também terá um sistema onde ambos os utilizadores poderão receber notificações.

Relativamente ao aluno, a plataforma permitirá a este colocar dúvidas, foras da aula, a um docente através de um espaço designado para o efeito. Neste poderá associar docentes, descrever a sua dúvida e anexar ficheiros se necessário. O aluno também terá de ser capaz de visualizar materiais e trabalhos submetidos pelos docentes. A última funcionalidade identificada é um serviço vídeo-aulas onde o aluno poderá juntar-se a aulas actualmente em curso e interagir com colegas e docente.

As funcionalidades identificadas para o docente foram o esclarecimento de dúvidas de alunos fora da aula em um espaço designado onde poderá, opcionalmente, marcar uma reunião remota com o aluno em causa. O docente também poderá iniciar uma vídeo-aula, associar participantes à mesma e gerir a assiduidade. O docente poderá adicionar materiais, trabalhos e sumários em espaços designados. Por último, a plataforma também permitirá ao docente gerir trabalhos - disponibilização e controlo de submissões.

## Características dos Utilizadores e Stakeholders

Como a equipa Flip Framework está a desenvolver um sistema de forma autónoma sem um cliente registado, o foco serão os nossos utilizadores finais (estudantes e docentes) e interesses dos stakeholders, para podermos oferecer o nosso sistema ao nosso potencial cliente, a Universidade de Coimbra.

Identificação e descrição dos Stakeholders

Alunos – Os alunos são um dos stakeholders mais importantes do sistema Flip Framework. Estes terão acesso a métodos de esclarecimento de dúvidas mais eficazes e a ferramentas de auxílio no trabalho de grupo. Para além disso, irão ganhar acesso a materiais fornecidos pelos docentes, estando estes organizados de forma clara.

Docentes – Os docentes também estão muito envolvidos no sistema Flip Framework como stakeholders. Isto pois com a sua utilização serão capazes de auxiliar os alunos de forma mais eficiente, e desta forma evitar ser prejudicados pelo tempo despendido a encontrar formas de comunicação com os seus alunos.

Universidade de Coimbra – A Universidade de Coimbra é o potencial cliente do sistema Flip Framework, sendo assim a possível entidade financiadora. Esta entidade quer manter o nível de ensino de anos anteriores e proporcionar à sua comunidade as condições necessárias para que o ano letivo ocorra com normalidade, ultrapassando as condições excecionais da pandemia.

Ministério de Educação – O Ministério de Educação não está diretamente relacionado com o desenvolvimento do sistema, mas beneficia do aumento do nível de qualidade do ensino. É uma entidade que apoia fortemente este tipo de iniciativa por parte das universidades, no sentido de evitar quebras financeiras e promover qualidade e prestígio de ensino.

Governo – O Governo, sendo uma entidade diretamente relacionada com o Ministério de Educação, partilha interesses comuns. Nomeadamente as questões financeiras e de prestígio.

Developers – Os developers têm muita importância no sistema Flip Framework. São a ponte entre o problema e a solução, sendo a sua opinião essencial para o desenvolvimento. Isto implica que os recursos e o esforço sejam geridos para encontrar a melhor solução, de forma a não os prejudicar.
