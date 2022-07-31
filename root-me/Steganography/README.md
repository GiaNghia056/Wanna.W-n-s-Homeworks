# Steganography
Write-ups for the challenges in the [Steganography section](https://www.root-me.org/en/Challenges/Steganography/) of [root-me](https://www.root-me.org/) 
## EXIF - Metadata [Meta or Beta?]
Our sad friend pepo got lost! Can you find where he is ?

The password is the city where pepo is located.<br/>
[ch1.png](http://challenge01.root-me.org/steganographie/ch1/ch1.png)
#### Solution
Use `exiftool` t view the Metadata of this file
```script
exiftool ch1.png
```
and I get the coordinates of where the picture was taken
![image](https://user-images.githubusercontent.com/88471003/180650349-125988eb-c138-4c61-a94e-40287e57c49a.png)<br/>
find it on `Google` and I know the city where `pepo is located` is `Marseille`
![image](https://user-images.githubusercontent.com/88471003/180650520-50a6047e-cea3-4a36-9d21-877919f28fc0.png)

## Dot and next line
“Rien de trop est un point dont on parle sans cesse et qu’on n’observe point.”

Jean de La Fontaine
[ch5.zip](http://challenge01.root-me.org/steganographie/ch5/ch5.zip)<br/>
#### Solution
Just watch this <br/>
![journal-2](https://user-images.githubusercontent.com/88471003/180650694-ff37b959-7fdf-4668-a1d2-51d1ebe1a160.jpg)

Flag : `chatelet15h`
## Steganomobile
After extraction of mobile data, the searcher, investigator have get this sequence of numbers. Maybe a phone number ?
[ch6.txt](http://challenge01.root-me.org/steganographie/ch6/ch6.txt)
#### Solution
I just convert the number to message by this

![image](https://user-images.githubusercontent.com/88471003/180651653-3e01901a-efee-474b-bdd0-6da2f795d11c.png)

Flag : `cellphone`
## Twitter Secret Messages [homoglyphs]
We suspect that this tweet hides a rendezvous point. Help us to find it.
```
Ｃhｏose  a  jοｂ  yоu  lονｅ,  and  you  ｗіｌl  ｎeｖｅｒ  have  tο  ｗｏrk  a  day  in  yοur  lіfｅ．               
```
#### Solution
Use this [tool](https://holloway.nz/steg/) to decrypt the message.<br/>
Flag : `grand central terminal`
## Poem from Space [Ternary Esoteric Language]
Deeply understand the meaning of this famous poem to validate this challenge.
[ch19.txt](http://challenge01.root-me.org/steganographie/ch19/ch19.txt)
#### Solution
I notice there are some white spaces at the end of each line. 

![image](https://user-images.githubusercontent.com/88471003/180652259-0eb0813b-1724-4bbc-a3c9-6c80c352c5e0.png)

So I just seperate the text from the white spaces, and I get a file contains just white spaces like this

![image](https://user-images.githubusercontent.com/88471003/180652329-cdafd7d0-71bb-41da-a27f-cd6bbeec07a9.png)

Use this [tool](https://ideone.com/l/whitespace) to compile the `Whitespace` code<br/>
Flag: `RootMe{Wh1t3_Sp4c3}`
## Yellow dots [Spying printers]
You attend an interview for a forensic investigator job and they give you a challenge to solve as quickly as possible (having the Internet).
They ask you to find the date of printing as well as the serial number of the printer in this document.
You remain dubitative and accept the challenge.

The answer is in the form:
`hh:mm dd/mm/yyyy SSSSSSSS`
with
 - hh: the hour of the event
 - mm: the minutes of the event
 - dd: the day of the event
 - MM: the month of the event
 - yyyy: the year of the event
 - SSSSSSSS: the serial number

[ch18.png](http://challenge01.root-me.org/steganographie/ch18/ch18.png)
#### Solution
After reading the Instructables, I try to find the Yellow Dots on the scan image and I found this

![image](https://user-images.githubusercontent.com/88471003/180653088-d7d2698f-2b4e-4de4-aa34-ce354a18cbe8.png)

I also found this on Internet and I just stick to it to solve the yellow dots

![image](https://user-images.githubusercontent.com/88471003/180653530-d8970abc-564a-4048-b9f3-3f54710e0cc8.png)
![Solve](https://user-images.githubusercontent.com/88471003/180653557-ac7011b5-90d6-487b-8868-e47457fa7cd2.png)

Flag: `11:05 27/07/2014 06922930`
## TXT - George and Alfred [Steganography in literature]
This challenge is only available in french language due to it specificity.<br/>
[ch4.txt](http://challenge01.root-me.org/steganographie/ch4/ch4.txt)
#### Solution
If you see carefully, each word at 2nd and 3rd poem can be a sentence if you joins it.
```
Quand je vous jure, hélàs, un éternel hommage
Voulez-vous qu’un instant je change de language
Que ne puis-je, avec vous, goûter le vrai bonheur
Je vous aime, ô ma belle, et ma plume en délire
Couche sur le papier ce que je n’ose dire
Avec soin, de mes vers, lisez le premier mot
Vous saurez quel remède apporter à mes maux.

Cette grande faveur que votre ardeur réclame
Nuit peut-être à l’honneur mais répond à ma flamme.
```
So, the password is `Cette Nuit`
## WAV - Noise analysis [A little bit music ?]
The password has to be given in lowercase.<br/>
[ch3.wav](http://challenge01.root-me.org/steganographie/ch3/ch3.wav)
## Solution
I open the wav file in Audacity and play it in `0.4x` speed but I couldn't hear anything that make senses so I use this [tool](https://mp3cut.net/vi/reverse-audio#) to reverse the audio.
After reversing the audio, play it in `0.4x` speed again and listen to the sound carefully.<br/>
Flag : `3b27641fc5h0`
## EXIF - Thumbnail [Russian dolls]
Find the password hidden in this image in JPG format.<br/>
[ch10.jpg](http://challenge01.root-me.org/steganographie/ch10/ch10.jpg)
