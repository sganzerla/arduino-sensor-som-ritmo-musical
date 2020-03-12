# arduino-sensor-som-ritmo-musical
Circuito simples que detecta ritmo musical através do sensor de som KY-038 e liga/desliga fita de leds conforme a música.

<p> Demonstração (vídeo)
 <a target="_blank" rel="noopener noreferrer" href="https://youtu.be/373_R5mCbJQ" >
  <img src="https://user-images.githubusercontent.com/22710963/76530463-859d5d00-6452-11ea-9c5f-bcabe1b05273.png" alt="reset" style="max-width:100%;"></a>
</p> 

##### Ambiente Virtual de Hardware e Software [TinkerCad](https://www.tinkercad.com)  
- É possível simular tanto componentes de hardware quanto a lógica de programação envolvida no circuito. Bastante útil porque dispensa a compra dos componentes eletrônicos físicos e a instalação da IDE no computador pra testes.
- Esse projeto não está no TinkerCad porque nem todos os componentes aqui usados são disponibilizados no ambiente.

### Software necessário

- [IDE Arduino](https://www.arduino.cc/en/Main/Software)
- [Documentação sintaxe C++](https://www.arduino.cc/reference/en/)

### Software p/ gerar esquemas de circuitos elétricos 

- Útil para documentar projetos

- Versão paga [Fritzing](https://fritzing.org/home/)

- Versão gratuita (permite que seja atualizada) [Fritzing](https://softfamous.com/fritzing/download/)

## Hardware necessário
```
- a) 1 Placa Arduino com cabo USB
- b) 1 Protoboard
- c) 8-10 Cabos de conexão 
- d) Fita Led Rgb 5050 Endereçável (10cm - 2m) 
- e) 1 Sensor de som KY-038 
```

 ### a) Placa Arduino com cabo USB
 Porta de 5V e 40mA
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/73710418-aac7de80-46e2-11ea-82d4-fabab3361d1f.png">
  <img src="https://user-images.githubusercontent.com/22710963/73710418-aac7de80-46e2-11ea-82d4-fabab3361d1f.png" alt="reset" style="max-width:100%;"></a></p> 

### b) Protoboard 
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/73710865-e7e0a080-46e3-11ea-9ec4-4800b2b345b9.png">
  <img src="https://user-images.githubusercontent.com/22710963/73710865-e7e0a080-46e3-11ea-9ec4-4800b2b345b9.png" alt="reset" style="max-width:100%;"></a></p> 

  ### c) Cabos de conexão
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/73711525-e57f4600-46e5-11ea-8cb9-e9bb27543ea4.png">
  <img src="https://user-images.githubusercontent.com/22710963/73711525-e57f4600-46e5-11ea-8cb9-e9bb27543ea4.png" alt="reset" style="max-width:100%;"></a></p>     
  
  ### d) Fita Led Rgb 5050 Endereçável
  O modelo usado aqui possui 4 fios 5v, Green, Red e Blue
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/76525426-91852100-644a-11ea-8566-34bf30b13e80.png">
  <img src="https://user-images.githubusercontent.com/22710963/76525426-91852100-644a-11ea-8566-34bf30b13e80.png" alt="reset" style="max-width:100%;"></a></p> 
  
  Outros modelos com espaçamento menor entre os leds e com o fio para controle do circuito digital são esses:
 <p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/76525813-52a39b00-644b-11ea-90f1-f2c73851f7c3.png">
  <img src="https://user-images.githubusercontent.com/22710963/76525813-52a39b00-644b-11ea-90f1-f2c73851f7c3.png" alt="reset" style="max-width:100%;"></a></p>
 
  
  ### e) Sensor de som KY-038
  Altere com calma a regulagem do sensor pois do contrário vai passar muita raiva com ele.
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/76327946-6aebac80-62c9-11ea-9b93-a7e231d9ef99.png">
  <img src="https://user-images.githubusercontent.com/22710963/76327946-6aebac80-62c9-11ea-9b93-a7e231d9ef99.png" alt="reset" style="max-width:100%;"></a></p> 

  
  

###  Aplicações
<p> Fazer painel luminoso reagirem com a intesidade do som  </p>
 


  
