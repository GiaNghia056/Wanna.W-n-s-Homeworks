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
