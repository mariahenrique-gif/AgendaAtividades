# AgendaAtividades

# README - AgendaAtividades

## Visão Geral
O **AgendaAtividades** é um sistema em Java para gerenciar atividades físicas, pensado como um Sistema para organizar os treinos que são feitos por pessoas ativas e que gostam de se organizar e manter o controle sobre aquio que faz.

---

## Funcionalidades
- **Cadastrar atividade**: insere uma nova atividade com nome, data, tipo, dificuldade, quilometragem e duração.  
- **Pesquisar por data**: mostra atividades cadastradas em um dia/mês específico.  
- **Pesquisar por tipo**: lista atividades de um determinado tipo (ex: corrida, musculação).  
- **Remover atividade**: exclui uma atividade pelo nome.  
- **Listar atividades**: exibe todas as atividades cadastradas.  
- **Relatórios**:
  - Total de horas por mês.
  - Total de quilômetros por mês.  
- **Salvar dados**: grava as atividades em arquivo.  
- **Recuperar dados**: carrega atividades previamente salvas.  

---

## Estrutura do Projeto
```
AgendaAtividades/
 └── src/main/java/br/ufpb/dcx/MH/agenda/
     ├── Agenda.java
     ├── AgendaMH.java
     ├── Atividade.java
     ├── GravadorDeDados.java
     ├── GUI/
     │    ├── AgendaGUIV2.java
     │    ├── AgendaGUIV3.java
     │    └── AgendaGUIV3ComMenu.java
     └── Controller/
          ├── AgendaCadastrarController.java
          ├── AgendaSearchController.java
          ├── AgendaRemoveController.java
          ├── AgendaListarController.java
          ├── AgendaTotalHorasController.java
          ├── AgendaTotalKmController.java
          ├── AgendaSalvarController.java
          └── AgendaRecuperarController.java
```

---

## Tecnologias Utilizadas
- **Java 17+**  
- **Swing** (para interface gráfica)  
- **IntelliJ IDEA** (IDE recomendada)  

---

## Interface
- **AgendaGUIV2**: mostra a capa central e todos os botões à direita.  
- **AgendaGUIV3**: versão refinada com botões organizados.  
- **AgendaGUIV3ComMenu**: versão com barra de menu, estilo sistema profissional.  

---

## Autoria
Projeto desenvolvido por **Maria Heloisa Henrique**, como parte de estudos de programação orientada a objetos em Java.
