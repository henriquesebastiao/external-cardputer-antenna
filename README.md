# Antena externa no Cardputer

<img src="img/main.jpg" width="300"/>

A ideia aqui é documentar o processo de instalação de uma antena externa no Cardputer, para melhorar o poder do sinal Wi-Fi, juntando o máximo de informações possíveis para facilitar a vida de quem quiser fazer o mesmo. Se você já fez isso e tem alguma dica, por favor, faça um pull request com suas informações.

Caso você tenha alguma dúvida, abra uma issue para que possamos te ajudar.

## 📜 Notas

Tenha em mente que você precisará abrir o Cardputer para instalar a antena externa, ele é um pouco delicado internamente, principalmente os componentes referentes a sua tela, logo todo o cuidado se faz necessário poara não danificar seu aparelho.

As imagens referentes a polaridades das malhas do conetor IPX presentes nesse passo a passo são oriundas do servidor Azur Firmware no Discord, cujo o crédito é devido aos usuários `@Cyber.odare` e `@keebasg`, agradeço a eles por compartilharem suas experiências.

## ⚠️ Cuidados a serem tomados ao abrir o Cardputer

- Tome cuidado ao abrir o Cardputer, pois o conector flat do display é frági e é conectado na parte de baixo do STAMP.
- Cuidado para não entortar os pinos do STAMP.

## 📝 Materiais

- Antena Wi-Fi SMA e adaptador IPX para SMA (recomendado: https://a.aliexpress.com/_mK5YhoU)
- Ferro de solda
- Estanho

Você deve escolher uma antena que tenha o conector compatível com o adaptador IPX para SMA, pois existem dois tipos de conectores SMA (SMA e RP-SMA), e você pode acabar se confundindo, veja a imagem abaixo:

<img src="img/rp-sma_sma.jpg" width="500" alt="Diferença entre conectores SMA e RP-SMA."/>

## 🛠️ Procedimento

Corte a ponta IPX do adaptador e descasque a ponta do cabo, separe a malha externa da interna, a malha externa representa o cabo negativo, já a interna representa o cabo positivo.

<img src="img/peeled-tip.jpg" width="500" alt="Ponta descascada do adaptador."/>

Com o ferro de solda esquente a solda da antena 3D integrada do Cardputer e a remova.

<img src="img/3d-antenna.jpg" width="500" alt="Antena 3D no STAMP."/>

Na foto abaixo você pode ver onde deve soldar os fios positivo e negativo da antena externa.

<img src="img/solder-antenna.jpg" width="500" alt="Onde soldar a antena."/>

Após soldar:

<img src="img/welded-antenna.jpg" width="300" alt="Onde soldar a antena."/>

Agora basta adaptar o conector SMA na carcassa do Cardputer e conectar a antena. Creio que não há muito a ser dito sobre essa parte.

Segue abaixo todas as demais imagens que podem lhe ajudar a entender melhor o processo:

<img src="img/img2.jpg" width="300"/>
<img src="img/img3.jpg" width="300"/>
<img src="img/img4.jpg" width="300"/>
<img src="img/img5.jpg" width="300"/>
<img src="img/img6.jpg" width="300"/>
<img src="img/img7.jpg" width="300"/>
<img src="img/img8.jpg" width="300"/>
<img src="img/img1.jpg" width="300"/>

## Fora de contexto 😅

Experiencia que eu, [@henriquesebastiao](https://github.com/henriquesebastiao) tive:

- Durante o processo de montar o Cardputer de volta eu quase desisti, o trem que não dava certo!
- E enquanto eu acho um espaço para caber o plug SMA eu optei por usar nada mais nada menos que uma furadeira para fazer um buraco na carcaça do Cardputer, pena que nao registrei isso.

<img src="img/cool.jpg" width="500"/>
