# Mini-amplificador de aúdio:

Para amplificar o som stéreo do Audio DAC PCM5102, eu usei um módulo PAM8403: 

- Data sheet PAM8403:

https://www.mouser.com/datasheet/2/115/PAM8403-247318.pdf

O PAM8403 é um amplificador de áudio classe D de 3 W. Oferece baixo THD+N,
permitindo-lhe obter uma reprodução de som de alta qualidade. Alimentação com 5V. 

 - Wiki do módulo PAM8403:

https://www.sunrom.com/p/stereo-audio-amplifier-pam8403

Para a alimentação do miniDexed, usei um regulador LM2596. 

Alimentei o LM2596 com uma fonte de 12V (pode ser 9V também). 

Ajustei a tensão de sáida do regulador para 5,15V. 

O regulador LM2596 pode alimentar o Raspberry Pi, o mini-amplificador PAM8403 e o teclado MIDI através de uma conexão USB adaptada.(depois eu explicarei). 

Na entrada do circuito do mini-amplificador PAM8403 usei um potenciômetro duplo de 10K ohms linear. 

Para conectar as mini caixas de som eu interliguei as sáidas com dois capacitores de 47uF/25V (um em cada canal). 

Usei duas mini caixas de som Pioneer (antigas) com 6 ohms e 100W! Era o que eu tinha aqui e são de ótima qualidade sonora. Recomendo caixas de som com no mínimo 5W. 

Para conectar o fone de ouvido stéreo (headphone), acrescentei dois resistores de 100 ohms em série, um em cada canal. Se for usar o headphone, desconecte as caixas de som. 

- OBS: quando for usar o headphone, ajuste o potenciômetro para o mínimo. Depois ajuste o volume. O som poderá estar ajustado para um volume muito alto! 
