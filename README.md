<h1 align="center">
<img src="https://www.agroexpointernational.com.br/content/dam/sitebuilder/rxb/agro-expo/2020/icones/img1.png/_jcr_content/renditions/original.image_file.399.309.file/801470491/img1.png" width="399" height="309">
 <br>
 Irrigação
</h1>

<p align="justify">
Este programa é um projeto de automação de irrigação para jardins e hortas residenciais. Seu funcionamento é simples e consiste basicamente de um sensor de umidade do solo que realiza a leitura de umidade correspondente e se o solo estiver seco, o sistema de irrigação é acionado automaticamente, permanecendo ligado até que o sensor de umidade do solo detecte que o solo está em um nível de umidade aceitável. Além disso, o software conta ainda com mais outros periféricos que complementam o sistema como um todo sendo eles, um sensor de umidade e temperatura do ar (DHT22), um sensor de chuva, um sensor de vazão, um RTC (Real Time Clock), um display TFT, uma placa de reles e uma válvula solenóide (127v). Os pinos do Arduino podem ser setados da forma que o usuário preferir, porém nesse projeto eles foram adotados da seguinte forma.
<p>

[Documentação Notion](https://www.notion.so/Agroneg-cio-Irriga-o-0ebab5f47b8446da8c02cd44154d3e2a)

#### Product Vision Box
<h1 align="center">
<img src="https://trello-attachments.s3.amazonaws.com/60271f90a8474b8ce248783a/887x552/f8ecc0880181ff45c420e80a9b274bd3/AgronegocioVisionBox.png" width="887" height="552">
</h1>

## Atividades para o desenvolvimento

- [x] Elaboração do Conceito e definição de escopo
- [x] Entrar em contato com Stakeholder
- [x] Definir o escopo do projeto
- [x] Retorno Stakeholder
- [x] Desenvolver Product Vision Box
- [x] Criar documentação, BPMN (diagrama)
- [x] Elaboração de DFD de contexto e DFD de niveis
- [x] Desenvolver diagrama de casos (Enterprise architect)
- [x] Marco 01 do Projeto - Primeira versão do Diagrama de Casos de Uso
- [x] Revisar requisitos funcionais
- [ ] Deploy
- [x] Criar Banco de Dados. (Tabelas, dados estáticos, relacionamento e modelagem do dados) - "Formas normais".

#### Esquema de Montagem Sistema de Irrigação com Arduino (1° Opção)
<h1 align="center">
<img src="https://www.researchgate.net/profile/Marcello-Amorim/publication/320995131/figure/fig1/AS:559314113122304@1510362284107/Figura-1-Esquema-de-montagem-do-Sistema-de-irrigacao-inteligente-Foram-conectados-a.png" width="700" height="672.82">
</h1>

<p align="justify">
Esquema de montagem do Sistema de irrigação inteligente. Foram conectados à placa de circuitos integrado: o sensor de chuva YL-83 com comparador LM393, com saídas digital e analógica; o sensor de umidade de solo HL69, Relé SRD-05VDC-SL-C; e os leds indicadores. O led vermelho indica ausência de chuva e umidade em solo, situação na qual era disparado um evento que aciona a bomba de água por meio do relé, com o objetivo de irrigar o solo. O led verde indica a presença de chuva, e o amarelo indica que o nível de água em solo está adequado. O sensor de chuva funciona como um medidor de resistência, conforme o nível de água no sensor aumenta a resistência diminui e assim ele pode indicar se está chovendo. Caso o nível de chuva indicado pelo sensor seja suficiente para garantir um nível de umidade necessária no solo, o sistema mantém a bomba de água desligada, evitando desperdício de água e energia, assim como desgaste do equipamento. Para garantir o funcionamento correto, o sensor de umidade foi posicionado no mesmo nível das raízes das plantas, desta forma foi possível identificar o nível de umidade no solo em torno delas. O limiar de ativação inferior do sensor de umidade foi de 80%, valores inferiores a este indicam que as plantas necessitam de mais água no solo. O SII também permite configurar a vazão da bomba de água, assim foi possível.
<p>
 
 #### Fluxo de Atividades
 <h1 align="center">
 <img src="https://www.researchgate.net/profile/Marcello-Amorim/publication/320995131/figure/fig6/AS:631636836241418@1527605365378/figure-fig6.png" width="700" height="474.34">
 </h1>
 
## Contruibuidores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/allanrodriguesmachado">
        <img src="https://avatars.githubusercontent.com/u/54523516?v=4" width="100px;" alt="Foto do Allan Machado no GitHub"/><br>
        <sub>
          <b>Allan Machado</b>
        </sub>
      </a>
    </td>
   <td align="center">
      <a href="https://github.com/MateusMaceedo">
        <img src="https://avatars.githubusercontent.com/u/63172367?v=4" width="100px;" alt="Foto do Mateus Macedo no GitHub"/><br>
        <sub>
          <b>Mateus Macedo</b>
        </sub>
      </a><br>
    </td>
</table>
