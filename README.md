![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Platform-Arduino-blue?style=for-the-badge&logo=arduino&logoColor=white)


# Prometheus

<h3>Projeto de Conclusão de UC do Senac</h3>
    <P>Este projeto é sobre a criação de um robô capaz de desviar de obstáculos e encontrar o caminho certo para sair de labirintos, usando inteligência para tomar decisões durante o percurso.</P>
 <hr>
 
  <h3>Componentes</h3>
  <ul>
    <li> Chassis</li>
    <li> 6 pilhas de 1.5V</li> 
    <li> Motores</li>
    <li> mini arduino uno</li>
    <li> Mini Protoboard</li>
     <li>Roda boba</li>
      <li>encaixe de pilhas</li>
       <li>sonar ultrassônico HC-SR04</li>
       <li>Manta Anti-estatica</li>
       <li>L293D</li>
       <li>Pneu de brinquedo</li>
       <li>Suporte de engrenagem</li>
      <li>fita dupla-face</li>
    <li>multímetro (auxilio na montagem)</li>
    </li>

        
<h3>Funcionalidade</h3>
    
  <ul>
      <li>Desvio automático de obstáculos (HC-SR04)</li>  
    <li>Estratégia básica para resolução de labirintos (turns + tomada de decisão)</li>  
     <li>Driver de motor que controla o sentido e a velocidade dos motores DC do robô (L293D)</li>  
<li>Estrutura modular para facilitar acréscimos (sensores, comunicação, etc.)</li>
  <br>
  </ul>
  
  <ul>
      <h2>Demonstração</h2>
  <img width="439" height="585" alt="PrometheusFinalizado" src="https://github.com/user-attachments/assets/2f412210-bf11-46e5-b08a-6fb5ea02cc20" />
  </ul>
<h1>Passo a Passo</h1>
<h3>Monte o Hardware</h3>
<ul>
  <li>Fixe os Motores no chassi e conecte o motor</li>
  <li>Ligue o driver ao Arduino</li>
  <li>Conecte o HC-SR04: Vcc -> 5V, GND -> GND, TRIG -> pino definido, ECHO -> pino definido.</li>
  <li>Insira batéria / alimentação adequada ao driver (não alimente motores pelo 5V do Arduino)</li>  
    <li>Voltagem minima das pilhas deve ser de 8V</li>
</ul>
  <h3>Preparando o Ambiente</h3>
  <ul>
     <li>Abra o Arduino IDE (ou PlatformIO).</li>
     <li>Instalar a Biblioteca Distance.Sensor by Tin Dao</li>
  </ul>
<h3>Autores</h3>
 <ul>
  <li>Felippe Camargo</li>
  <li>Reginaldo Soares</li>
   <li>Gabriel Alexandre</li>
 </ul>
