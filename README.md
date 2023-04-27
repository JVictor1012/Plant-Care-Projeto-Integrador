# Plant-Care-Projeto-Integrador
Projeto para a disciplina de Projeto Integrador 2

A ideia é criar um aplicativo de celular que se comunique com um sensor de umidade instalado no solo de uma planta doméstica.
O objetivo é analisar e criar uma rotina de cuidados com as plantas.

# Integração com disciplinas 

Neste projeto, está planejado fazer a integração da disciplina de desenvolvimento de dispositivos móveis, criar telas, funcionalidades juntamente com a disciplina de Internet das coisas, programando um sistema Arduino com um sensor de umidade fazendo com que esses dois serviços se comuniquem e interajam em tempo real usando tecnologias como o protocolo MQTT, Node Red e react native.

# Diagrama Gantt

```mermaid
    gantt
    title Cronograma de atividades do projeto
    dateFormat  YYYY-MM-DD
    section Pesquisa 
    Idealização do Projeto      :a1, 2023-04-01, 30d
    Escolha de tecnologias      :a2, after a1, 10d
    
    section App Mobile
    Criação de telas e modelagem      :b1, after a2 , 15d
    Programação do Aplicativo         :b2, after b1 , 30d
    
    section Arduino
    Organização de material         :c1, after b1, 15d
    Programação do Arduino          :c2, after c1, 15d

    
    section Defesa
    Preparação da Apresentação :p1, after c1, 10d
    Ensaio da apresentação :p2, after p1, 7d
    Apresentação e entrega  :milestone, after p2, 1d
```
