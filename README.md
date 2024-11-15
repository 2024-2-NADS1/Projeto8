# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# 🌏 Sistema de identificação de água potável. 

## AquaSense 💦

## Integrantes: <a href="https://www.linkedin.com/in/luanpires-silva/">Luan Pires</a>, <a href="https://www.linkedin.com/in/lucas-lucena-361824l/">Lucas Lucena</a>, <a href="https://www.linkedin.com/in/pedro-augusto-da-silva-macedo-9a0200187/">Pedro Macedo</a>, <a href="https://www.linkedin.com/in/luiz-eduardo-souza-rocha-09aab2321/">Luiz Rocha</a>

## Professores Orientadores: <a href="https://www.linkedin.com/in/victorbarq/">Prof. Victor Bruno </a>.

## ✏️ Descrição
O Sistema de Identificação de Água Potável é uma solução baseada em Internet das Coisas (IoT) projetada para monitorar e analisar a qualidade da água em tempo real. O sistema utiliza sensores inteligentes para coletar dados críticos, como pH, turbidez, temperatura, condutividade elétrica e a presença de contaminantes químicos ou biológicos. Esses dados são transmitidos para uma plataforma na nuvem, onde são analisados e disponibilizados para os usuários por meio de um aplicativo ou dashboard web.
O objetivo do projeto é assegurar que a água esteja dentro dos padrões de potabilidade recomendados, promovendo saúde pública e o uso sustentável dos recursos hídricos.

![Imagem do WhatsApp de 2024-11-15 à(s) 12 07 46_54cdb279](https://github.com/user-attachments/assets/edae4a93-289c-4c92-8b22-4b54f13fbdbd)
![ods](https://github.com/2024-1-NADS1-A/Projeto9/blob/main/imagens/ODS.jpg)

 O sistema utiliza sensores inteligentes conectados a um microcontrolador para coletar dados como pH, turbidez, temperatura, condutividade elétrica e presença de contaminantes na água. Esses dados são transmitidos para uma plataforma em nuvem onde são analisados e armazenados. A solução fornece alertas automáticos em casos de contaminação ou condições inadequadas para o consumo, permitindo uma intervenção rápida. O projeto utiliza sensores IoT para medir parâmetros críticos da água, como pH, turbidez, temperatura, cloro residual e condutividade elétrica. Esses sensores são conectados a um microcontrolador que coleta os dados e os envia para uma plataforma na nuvem para análise e armazenamento. O sistema alerta os usuários caso a água não esteja potável, fornecendo dados detalhados sobre as condições da água.

O sistema é ideal para ser implantado em comunidades, indústrias, e instalações que necessitam de monitoramento contínuo da qualidade da água, como estações de tratamento e redes de abastecimento.


## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Documentação.docx<br>
|-->executáveis<br>
  &emsp;|-->windows<br>
  &emsp;|-->android<br>
  &emsp;|-->HTML<br>
|-->imagens<br>
|-->src<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.


## 🛠 Materiais utilizados.
![image](https://github.com/user-attachments/assets/b7d1debe-fba1-4727-889b-dd0fab4178bb)

 - Arduino IDE
 - ESP32
 - Sensor de turbidez
 - Sensor TDS
 - Componentes 


## 💻 Software utilizados

# 💻 Arduino IDE
---

## Passo 1: Acesse o Site Oficial do Arduino
1. Abra o navegador de sua preferência.
2. Acesse o site oficial do Arduino: [https://www.arduino.cc/](https://www.arduino.cc/).

---

## Passo 2: Navegue até a Página de Downloads
1. No menu superior, clique em **"Software"**.
2. Na seção "Downloads", selecione a versão do **Arduino IDE** compatível com o seu sistema operacional:
   - **Windows**
   - **macOS**
   - **Linux**

---

## Passo 3: Escolha a Versão do Arduino IDE
1. Existem duas versões disponíveis:
   - **Arduino IDE 2.x (Recomendada)**: Interface moderna e novos recursos.
   - **Arduino IDE 1.x (Clássica)**: Para quem prefere a versão mais antiga.
2. Clique na versão desejada e confirme o sistema operacional correto.

---

## Passo 4: Realize o Download
1. Na página de download, você pode:
   - Escolher uma doação opcional para o projeto Arduino.
   - Clicar em **"Just Download"** para prosseguir sem realizar uma doação.
2. O arquivo será baixado para a pasta padrão de downloads do seu computador.

---

## Passo 5: Instale o Arduino IDE
### No Windows:
1. Clique duas vezes no arquivo `.exe` baixado.
2. Siga as instruções do instalador.
3. Marque as opções para instalar os drivers necessários.

### No macOS:
1. Arraste o ícone do Arduino IDE para a pasta **Aplicativos**.

### No Linux:
1. Extraia o arquivo baixado.
2. Execute o script de instalação no terminal, seguindo as instruções fornecidas.

---

## Passo 6: Abra o Arduino IDE
1. Após a instalação, abra o **Arduino IDE**.
2. Conecte sua placa Arduino ao computador usando um cabo USB.
3. Configure a porta e a placa em:
   - **Ferramentas > Placa > Selecione sua placa Arduino**.

---

## Passo 7: Teste a Instalação
1. Na IDE, vá em **Arquivo > Exemplos > Basics > Blink**.
2. Carregue o código exemplo na sua placa clicando em **"Carregar"**.
3. O LED da sua placa deve começar a piscar, confirmando que tudo está funcionando corretamente.



## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" >Este trabalho está licenciado sob <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências

1. 
2.
3. 
4.
5. 
6. 
