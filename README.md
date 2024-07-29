# Antena externa no Cardputer

<img src="img/main.jpg" width="300"/>

<details><summary><h3>English version:</h3></summary>

The idea here is to document the process of installing an external antenna on the Cardputer to improve the Wi-Fi signal strength, gathering as much information as possible to make life easier for anyone who wants to do the same. If you have already done this and have any tips, please submit a pull request with your information.

If you have any questions, open an issue so we can help you.

## 📜 Notes

Keep in mind that you will need to open the Cardputer to install the external antenna. It is somewhat delicate internally, especially the components related to its screen, so care is necessary to avoid damaging your device.

The images showing the polarities of the IPX connector braids in this guide come from the Azur Firmware server on Discord, and credit is due to users @Cyber.odare and @keebasg. Thank you for sharing your experiences.

I would like to thank the following person for sharing images and information that helped compose this guide:

- [@Lucas-Simoes-Lisboa](https://github.com/Lucas-Simoes-Lisboa)

## ⚠️ Precautions to Take When Opening the Cardputer

- Be careful when opening the Cardputer, as the display flat connector is fragile and is connected at the bottom of the STAMP.

<img src="img/img9.jpg" width="300" alt="STAMP flat connector"/>

Be careful not to bend the STAMP pins.

## 📝 Materials

- SMA Wi-Fi antenna and IPX to SMA adapter (recommended: https://a.aliexpress.com/_mK5YhoU)
- Soldering iron
- Solder

You must choose an antenna that has a connector compatible with the IPX to SMA adapter, as there are two types of SMA connectors (SMA and RP-SMA), and you might get confused. See the image below:

<img src="img/rp-sma_sma.jpg" width="500" alt="Difference between SMA and RP-SMA connectors."/>

## 🛠️ Procedure

Cut the IPX end of the adapter and strip the cable end, separating the outer and inner braids. The outer braid represents the negative cable, while the inner braid represents the positive cable.

<img src="img/peeled-tip.jpg" width="500" alt="Stripped tip of the adapter."/>

Use the soldering iron to heat and remove the solder from the integrated 3D antenna of the Cardputer.

<img src="img/3d-antenna.jpg" width="500" alt="3D antenna on the STAMP."/>

In the photo below, you can see where to solder the positive and negative wires of the external antenna.

<img src="img/solder-antenna.jpg" width="500" alt="Where to solder the antenna."/>

After soldering:

<img src="img/welded-antenna.jpg" width="300" alt="Soldered antenna location."/>

Now, adapt the SMA connector to the Cardputer case and connect the antenna. I believe there is not much more to say about this part.

Below are all the other images that can help you better understand the process:

<img src="img/img2.jpg" width="300"/>
<img src="img/img3.jpg" width="300"/>
<img src="img/img4.jpg" width="300"/>
<img src="img/img5.jpg" width="300"/>
<img src="img/img6.jpg" width="300"/>
<img src="img/img7.jpg" width="300"/>
<img src="img/img8.jpg" width="300"/>
<img src="img/img1.jpg" width="300"/>
<img src="img/img10.jpg" width="300"/>
<img src="img/img11.jpg" width="300"/>
<img src="img/img12.jpg" width="300"/>
<img src="img/img13.jpg" width="300"/>

## Out of Context 😅

An experience I, @henriquesebastiao, had:

- During the process of reassembling the Cardputer, I almost gave up; it just wasn’t working!
- And while I was finding space for the SMA plug, I opted to use nothing less than a drill to make a hole in the Cardputer case. Too bad I didn't record it.

<img src="img/cool.jpg" width="500"/>

</details>

A ideia aqui é documentar o processo de instalação de uma antena externa no Cardputer, para melhorar o poder do sinal Wi-Fi, juntando o máximo de informações possíveis para facilitar a vida de quem quiser fazer o mesmo. Se você já fez isso e tem alguma dica, por favor, faça um pull request com suas informações.

Caso você tenha alguma dúvida, abra uma issue para que possamos te ajudar.

## 📜 Notas

Tenha em mente que você precisará abrir o Cardputer para instalar a antena externa, ele é um pouco delicado internamente, principalmente os componentes referentes a sua tela, logo todo o cuidado se faz necessário poara não danificar seu aparelho.

As imagens referentes a polaridades das malhas do conetor IPX presentes nesse passo a passo são oriundas do servidor Azur Firmware no Discord, cujo o crédito é devido aos usuários `@Cyber.odare` e `@keebasg`, agradeço a eles por compartilharem suas experiências.

Agradeço às seguintes pessoa por compartilharem imagens e informações que ajudaram a compor esse passo a passo:

- [@Lucas-Simoes-Lisboa](https://github.com/Lucas-Simoes-Lisboa)

## ⚠️ Cuidados a serem tomados ao abrir o Cardputer

- Tome cuidado ao abrir o Cardputer, pois o conector flat do display é frági e é conectado na parte de baixo do STAMP.

<img src="img/img9.jpg" width="300" alt="Conector flat do STAMP"/>

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
<img src="img/img10.jpg" width="300"/>
<img src="img/img11.jpg" width="300"/>
<img src="img/img12.jpg" width="300"/>
<img src="img/img13.jpg" width="300"/>

## Fora de contexto 😅

Experiencia que eu, [@henriquesebastiao](https://github.com/henriquesebastiao) tive:

- Durante o processo de montar o Cardputer de volta eu quase desisti, o trem que não dava certo!
- E enquanto eu acho um espaço para caber o plug SMA eu optei por usar nada mais nada menos que uma furadeira para fazer um buraco na carcaça do Cardputer, pena que nao registrei isso.

<img src="img/cool.jpg" width="500"/>
