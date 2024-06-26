 
 <h2 align="center">Sensor de Quedas: Tecnologia Vestível para Idosos Protótipo Eletrônico de Detecção de Quedas</h2>

<h2>Introduçao </h2>
Para esse bimestre, nós tínhamos que trabalhar com hardware e software, enquanto simultaneamente continuamos nosso projeto voltado para idosos, então decidimos fazer um protótipo de   
sensor de queda, a fim de aproveitar as funcionalidades do Arduino para beneficiar os idosos para terem melhor segurança e bem-estar. Apesar das dificuldades encontradas durante o desenvolvimento do protótipo, conseguimos um bom resultado, através de uma pesquisa extensiva, explorando documentos, artigos científicos e vídeos.

<div>
<p>  </p>

</div>

<img width="620px" src="https://github.com/and3510/Arduino_Project/assets/127062559/75cd657c-6727-4a73-a592-849ae99c5b1d"  alt="GitHub Readme Stats" />
<p>Diagrama do projeto</p>

<h2>Componentes usados no Prototipo</h2>   
<img width="430px" src="https://github.com/and3510/Arduino_Project/assets/127062559/4e3e94aa-6668-4d12-a4c6-22a5c5c9c552"  alt="GitHub Readme Stats" />

- ##### Buzzer 5v -> Para aviso sonoro.
- ##### Protoboard de 300 pinos -> Usado para expandir as conecçoes entre os compoenentes e usar como base do prototipo.
- ##### Arduino Uno -> Um Microcontrolador, onde armazena um nosso codigo e processa todas as tarefas.
- ##### MPU-6050 -> É um acelerômetro e giroscópio capaz de medir a aceleração e rotação nos três eixos coordenados (x,y,z).
- ##### Bateria 9v -> Fonte de energia do dispositivo.

<h2> Desenvolvimento do Programa </h2>
<img width= "550px" src="https://github.com/and3510/Arduino_Project/assets/127062559/6c1e93b3-edb0-4c73-8721-099644e88d46" alt="GitHub Readme Stats" /> 
<p>Parte do codigo</p>

- ##### O programa analisa os dados do mpu6050 e calcula atraves da aceleraçao o movimento brusco e o angulo do dispositivo.
- ##### O codigo funciona com dois estagios para detecçao de queda.
  - ###### 1ºestagio verifica a condiçao de movimento brusco.
  - ###### 2ºestagio verifica a condiçao de uma real queda.




<h2> Resultados ate agora </h2>
<img width= "350px" src="https://github.com/and3510/Arduino_Project/assets/127062559/dc579d8e-597a-4cbd-a11d-3fd85406f05a" alt="GitHub Readme Stats" /> 
