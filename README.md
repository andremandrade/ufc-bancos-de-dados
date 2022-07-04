## UFC - Campus de Crateús
# Fundamentos de Bancos de Dados

### Unidade 1
* [Apresentação e conceitos iniciais](https://drive.google.com/open?id=1krhCp9Kb1fOWDtqxMN878f-EiGk4nTSM0DYEjHKD9Rg)
* [Modelo de Entidade e Relacionamento (MER)](https://drive.google.com/open?id=1lUIdja9H6GxY9hwPMgsupfQOa3qOVk9jvoMkC6UMm10)
  * [Lista 1 - MER](https://docs.google.com/document/d/125keCkbNjf0MZM3PXv3u2xqRtyJoMC8fQxcM3u4HoPI/edit?usp=sharing) 
* [Modelo Relacional](https://drive.google.com/open?id=1wBYxGVxglgNVy0D5FSdpzS7LGaYJ1m36S95i-7iFmz4)
  * [Lista 2 - MR](https://docs.google.com/document/d/10G8javKmvfkSv4yb6BOzCH--621pR_fJ10uOWHa80a8/edit?usp=sharing) 
* [Mapeamento MER x MR](https://drive.google.com/open?id=1ue2QW_yUUCSUjLfFp9omQN8sz_qWOrgOciRMIZ_4Kk0)
  * Laboratório: Mapeie os MER da [Lista 1](https://docs.google.com/document/d/125keCkbNjf0MZM3PXv3u2xqRtyJoMC8fQxcM3u4HoPI/edit?usp=sharing) para o esquema relacional.
  * [Lista 3](https://docs.google.com/document/d/1dFWVYL9VfOEaMNX5KUnissp4M9_Bx8UxuGHO3tf9W48/edit?usp=sharing)
* [Modelo de Entidade e Relacionamento Estendido](https://drive.google.com/open?id=1XfTijKrRKd-7EZS9zN3vIQYu5LXLEwVEsAcVMh3_dps)
  * [Lista 4](https://docs.google.com/document/d/198bqAr1kpQDNYI3cxV5x26jIiV1D2r5Dr0863Aszr_U/edit?usp=sharing)
* [Álgebra Relacional](https://drive.google.com/open?id=1T_u8VMd9ljc3VqDAErhzqZPUsTXIlI-IyxS_kt6ZQIY)
  * [RelaX - relational algebra calculator](relax-conf.md)
  * [Lista de Exercícios 5.1](exercicios/lista-5.1.v2.md)
  * [Lista de Exercícios 5.2](exercicios/lista-5.2.md)

### Unidade 2
* Ferramenta SQL Online: [RELAX](https://dbis-uibk.github.io/relax/calc/local/uibk/local/0)
* [SQL - DDL - Básico](https://drive.google.com/open?id=1I21sC--ZbYov2FpWxnOcjJrLbROA3CXqz6k24W91GZc)
  * [MySQL - Instalação, execução e acesso](http://docs.google.com/presentation/d/1G9aglX3x5Rvy0qZaS3_nPTdzAER4EflgCsOn6AFCJCk)
  * [Lista de Exercícios 6](exercicios/lista-6.1.md)
* [SQL - DML - Básico](https://drive.google.com/open?id=1FT85SkldQPwp5AdGSXlR5XYT0R-98xF-7hBDKedF47w)
  * [Lista de Exercícios 7](exercicios/lista-7.1.md)
* [SQL - Consultas Avançadas](https://drive.google.com/open?id=12FElkhW_TdgN7JD30iuT_7QGwrL7la5akGHxPoRqR3U)
  * [Lista de Exercícios 8](exercicios/lista-8.1.md)
* [SQL - Asserções, Gatilho e Visões](https://drive.google.com/open?id=1mk3qPFa8CqGVEgOQd6buhlLWy-99chrFBNGLxMk4C2k)
  * [Lista de Exercício 9](http://drive.google.com/open?id=1s1bB1s1FeNy8CWBA8yHL1Uw29K7NRy0DyjGhCS0A_As)

### Unidade 3
* [Dependencia Funcional e Normalizacão](http://drive.google.com/open?id=1bvx4hvj13ijcQDa_KhEc8e5E4qHS9CRCFi2_9g8WkcM)
* [Conceitos e teoria de processamento de transações](http://drive.google.com/open?id=1FBYoErQmhqhP-etwd7ArKn7B1sr7REC1Ngl8Jwo9sN8)
* [SGBDs - Sistemas Gerenciadores de Bancos de Dados](http://docs.google.com/presentation/d/1u1bjiIqEVVLBHYUyUCQtvLFhdxat8ns3J0bel2BMPb0/edit?usp=sharing)

### Projeto - Aplicação Java para acesso ao MySQL com JDBC

#### Tutorial: (https://docs.google.com/presentation/d/1twzCouyc1b3ZE6-4lzWrbNty4KfL01uOL51W8oRfl8Y/edit?usp=sharing)
  
#### Requisitos
A aplicação deve fornecer interface gráfica ou de console que permita ao usuário executar as seguintes funções:

1. Adicionar estudante: informar os dados e adicionar ao banco
2. Atualizar estudante: informar a matrícula ou selecionar o estudante a ser atualizado, e em seguida informar os novos dados
3. Remover estudante: informar a matrícula ou selecionar o estudante  a ser removido
4. Listar estudantes: exibir os dados de todos os estudantes
5. Buscar estudantes: informar uma string qualquer e o sistema deverá listar os estudante cuja a string informada seja parte do seu nome ou email.
6. Exibir histórico de estudante: selecionar um estudante e listar as disciplinas que ele já cursou com o respectivo período, nota, e frequência.
7. Listar, adicionar, atualizar e remover disciplina
8. Buscar disciplina pelo nome
9. Selecionar uma disciplina, selecionar um período, e exibir os alunos que cursaram aquela disciplina naquele período, com suas respectivas notas e frequência
10. Selecionar uma disciplina, um aluno, um período e definir a nota e a frequência
