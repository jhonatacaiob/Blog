+++
date = '2026-03-18T02:59:04-03:00'
draft = false
title = 'Sincronizando minha coleção de música com syncthing'
tags = ["DIY", "offline", "python"]
+++


# Sincronizando minha coleção de música com syncthing

Ultimamente, tenho trabalhado em transformar meu velho Sansung A53 em um dispositivo offline-first, onde não vai entrar uma unica unidade de software proprietário, dedicado a criação e consumo de mídias. To chamando esse projeto de SketchPhone.

Um dos passos me dói é o consumo de músicas. Como escutar música de forma offline num mundo onde o spotify existe?

Faça igual aos antigos gregos e mesopotamicos e baixe mp3!!!!!!!

Ta!! Vou baixar só mp3!! Iuhuuu!!!!! Mas perai, eu vou ter que baixar tudo direto no celular?

Eu tinha pensado em baixar no pc, e jogar esse diretório no soulseek. Mas, eu ainda queria que ao adicionar algo nessa pasta (principalmente, via beets (uma das ferramentas mais legais que eu já vi escrita em python)), meu SketchPhone já tivesse a música lá tambem. Ou seja, será que tem como sincronizar o estado de duas pastas em dispositivos diferentes?

É aí que entra o SyncThing!!!

O syncthing resolve literalmente o problema acima!!!


Instalei dentro no container docker, e configurei a ferramenta pra rodar só quando tiver no wifi daqui de casa (unico lugar onde se deve conectar o SketchPhone na internet, é na sua casa).

Eu configurei para o meu computador ser um diretório que só envia, e no Sketch ser um diretório que só recebe.

Gosto de imaginar que o diretório de musicas do meu computador é um portal para o celular.

Hoje eu passei o dia organizando minha coleção de mp3, e pelo menos agora, eu faço seguro que qualquer alteraçãozinha, vai ta repercutido.
