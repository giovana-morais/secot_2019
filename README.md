# uma gentil introdução a computação musical

## o que tem nesse repositório:
1. um notebook chamado `intro_mir` com alguns dos conceitos básicos que eu mostrei na palestra
2. um notebook chamado `mood_classifier` que tem uma classificação beeem ruim de humor nas músicas
3. um arquivo chamado `realtime_spectrogram.py` que mostra um espectrograma em ASCII sendo gerado
em tempo real
4. um arquivo chamado requirements.txt pra salvar a vida de vocês

## o que eu preciso pra rodar tudo isso?
se você nunca mexeu com ambientes virtuais, esse talvez possa ser o momento.

você pode instalar na sua máquina um [ambiente virtual](https://virtualenv.pypa.io/en/stable/)
e aí instalar as dependências OU instalar direto na sua máquina. 

todos os códigos rodam em python 3.x, então se o seu padrão é o 2.7 (que vai perder suporte), 
eu recomendo o ambiente virtual.

enfim, a partir disso aí é só dar um 

`pip install -r requirements.txt` 

e tudo será lindamente instalado na sua máquina ou ambiente virtual.


o `librosa` depende do `ffmpeg` pra rodar as coisas, então talvez seja necessário
instalar ele. nesse caso, já não é uma lib do python, mas sim uma biblioteca do 
sistema. se o seu for Ubuntu, `sudo apt-get install ffmpeg`. se for Arch Linux
`pacman -S ffmpeg`. 


qualquer dúvida, manda aquele email pra `giovana.vmorais@gmail.com` e ficarei 
feliz em ajudar. (:



