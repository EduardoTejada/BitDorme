# BitDorme

## Escopo do projeto
1. Apresentação do projeto – breve descrição sobre o que trata o projeto.  
O projeto consiste em um sistema de monitoramento do sono utilizando o microfone da BitDogLab, aliado a um alarme interativo que inclui um puzzle para facilitar o despertar de forma mais eficiente.
 
2. Título do projeto – pequeno título para o projeto.  
“BitDorme: Monitoramento de sono e despertador inteligente”
  
3. Objetivos do projeto – descreva os objetivos do projeto.  
Busca-se fazer um sistema capaz de coletar dados de áudio durante a noite para que assim seja possível identificar padrões e ajudar a melhorar a qualidade do sono dos usuários
Também se deseja criar um jeito de fazer com que o usuário resolva um puzzle para fazer com que o alarme pare de tocar. Assim estimulando a atividade cognitiva fazendo com que não seja tão simples desligar o alarme e voltar a dormir.
Com a combinação de ambas tarefas o projeto contribui para uma rotina matinal mais produtiva e uma qualidade de sono melhor.
  
5. Principais requisitos – podem ser estipulados pelo usuário ou cliente, ou até por você (fazendo o papel de um deles).
 1. Requisitos funcionais:  
 - Monitoramento de áudio: O sistema deve captar sons do ambiente, como respiração e ronco, para análise da qualidade do sono.
 - Armazenamento de dados: Deve registrar informações relevantes durante a noite para posterior análise.
 - Ativação do alarme: O despertador deve ser acionado em um horário pré-definido.
 - Desbloqueio do alarme por puzzle: Para desligar o alarme, o usuário deve resolver um desafio (exemplo: sequência lógica, cálculo matemático, jogo simples).
 - Interface de usuário: Deve ter uma forma de configuração e visualização de dados.
  
 2. Requisitos não funcionais:  
 - Custo acessível: O projeto deve buscar componentes de baixo custo para viabilizar sua produção.
 - Baixa latência no processamento: A análise de áudio deve ser feita em tempo real ou com um pequeno atraso para garantir a precisão.
 - Durabilidade: Os componentes devem ser resistentes o suficiente para suportar o uso diário sem falhas.

5. Descrição do funcionamento – descreva as funcionalidades do projeto.  
Os sons captados são processados em tempo real e armazenados para futura análise, possibilitando que o usuário visualize informações relevantes sobre seu sono.
Há uma interface de configuração, permitindo ao usuário configurar o horário do despertador.
Para garantir que o usuário realmente acorde, o alarme só pode ser desligado após a resolução de um jogo da memória, estimulando a atividade mental e reduzindo as chances de voltar a dormir.
É mostrado no display OLED dos resultados coletados durante o sono, bem como é disponibilizado um código em Python capaz de gerar um na tela do computador para melhor visualização.

6. Justificativa – mostre que a execução do projeto se justifica.  
O sono é fundamental para a vida de todos, e garantir que ele esteja sendo realizado com qualidade é uma tarefa importante. Durante o sono o corpo realiza diversos processos essenciais e distúrbios no sono podem causar diversos problemas não só em relação ao comportamento mas também podem levar ao desenvolvimento de doenças crônicas.
Por outro lado, despertar de um sono profundo nem sempre é uma tarefa fácil, muitas pessoas, mesmo que sem querer, desligam o alarme e voltam a dormir sem nem perceber. Para combater isso, diversos aplicativos usam desafios para estimular o pensamento nos primeiros segundos do dia, assim ajudando a trazer o cérebro para a consciência mais rápido. Esses podem ser problemas matemáticos ou desafios de lógica, mas todos buscam minimizar a sonolência matinal e melhorar a disposição ao longo do dia.
Por conta disso o uso de um dispositivo que não só ajuda a monitorar o sono, coletando dados que podem indicar diversos problemas mas também que auxilia o usuário a acordar tende a ser muito benéfico para a saúde, rotina e bem-estar.

7. Originalidade – mostre através de uma pesquisa que existem projetos correlatos, mas não iguais.  
 - [Sleep Quality Monitor](https://projecthub.arduino.cc/SrVassili/sleep-quality-monitor-48a511): Um projeto semelhante que utiliza de mais sensores, permitindo conclusões mais precisas para a análise, mas não permite que os dados sejam salvos, visualizados através do computador e fazendo uma análise mais complexa. Além de utilizar ATMEGA328P, o que limita o poder de processamento do projeto. Ainda, não há a parte do despertador;
 - [A wearable wristband designed for sleep monitoring and analysis](https://github.com/NicolasHu11/Arduino-Sleep-Monitor): Esse projeto trás uma proposta interessante de uma pulseira que para fazer a detecção dos parâmetros, também dispõe de mais sensores e é feito com ATMEGA328P como no projeto anterior. O projeto também se torna um pouco diferente por se tratar não só de um detector para o sono, mas sim para ser usado 24 horas. Ainda, não há a parte do despertador;
 - [I made an alarm clock that you can't turn off from bed](https://www.reddit.com/r/arduino/comments/c2x9ww/i_made_an_alarm_clock_that_you_cant_turn_off_from/): Como não foi encontrado nenhum projeto de sistema embarcado de um despertador que para de tocar através de um puzzle, esse é algo semelhante, mas ao invés de um jogo da memória ele obriga o usuário a levantar da cama para desligar, porém não contém a parte de monitoramento de sono.

## Hardware

1. Diagrama em blocos – diagrama mostrando os blocos e sua interligação.

2. 
3. 
