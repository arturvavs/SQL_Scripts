Nesta branch está disponibilizado os scripts construídos para a construção de um indicador utilizado pela equipe de Farmacêuticos Clínicos. 
Nele dispões de informações acerca de uma avaliação do paciente realizada pelo farmacêutico clínico.
Esses scripts fazem parte da construção de um indicador no PowerBI, onde nele faço o relacionamento das consultas como tabelas que possuem conexão direta com o banco de dados.
O intuito desse indicador é analisar a conformidade dessas avaliações, verificando se estão conformes ou não conformes, levando em considerações o fluxo interno da instiuição e a periodicidade dessas avaliações. 
Por exemplo:

- A primeira avaliação deve ser realizada em até 48 horas após a admissão do paciente no setor de internação do hospital.
- Após a avaliação de admissão ser realizada, é necessário que seja feita uma nova avaliação a cada 7 dias.
- Caso o paciente tenha uma categoria de Alto Risco ou maior, é necessário que seja realizada uma avaliação diariamente.
- Pacientes de UTI não necessitam da avaliação realizada, pois considera-se que todo paciente em UTI já tem um Alto Risco.
- Caso o paciente saia de um leito da UTI e vá para um leito de internação, será necessário realizar uma nova avaliação.
