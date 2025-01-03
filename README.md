![Adaptive Notepad](https://media.discordapp.net/attachments/1313895396766126140/1313895451208056994/adaptivenotepad.png?ex=6751cbfe&is=67507a7e&hm=a8b95e0aade40d47c2fdf069ed9f0f46f6f24e66a78b2d5a2efc93f2d842ee47&=&format=webp&quality=lossless)

> [!Warning]
> Aplikācija un tās mājaslapa pašlaik nedarbojas.

## Iedvesma
Kāpēc tieši **Adaptive Notepad**?

- Mūsu ideja par **Adaptive Notepad** radās nelielā prāta vētrā, no angļu valodas **"adaptive notepad"** - adaptīvais piezīmjbloks, par cik neko šādu līdz šim momentam neesam redzējuši, nolēmām ko tādu izgatavot.

## Kā "Adaptive Notepad" strādā?

### Frontend
- **Nospiežot specifisku pogu, pašlaik **F9**, programmas lietotājam atveras piezīmjbloks, kur ir sākumā jaizveido konts/jāielogojas kontā, tālāk lietotājam ir iespēja kaut ko ierakstīt teksta failā un saglabāt to gan uz darbavirsmas, gan mūsu datubāzē.**

- **Saglabātos teksta failus var apskatīt caur aplikāciju, vai arī mūsu mājaslapā, ielogojoties https://adaptivenotepad.onrender.com/.**

##

### Backend
- **Tad kad lietotājs mēģina izveidot kontu, tiek pārbaudīts vai jau neeksistē kāds lietotājs ar identisku lietotājvārdu, priekš drošības, kā arī lai nebūtu nevēlamu backend konfliktu.**

- **Tad kad lietotājs mēģina ielogoties, tiek veikta ievadītā lietotājvārda un paroles salīdzināšana ar datubāzi, kā arī, parolei ir jābūt identiskai ar datubāzē saglabāto paroli, piemēram, ja parole ir "parole123" un datubāzē ir saglabāta kā "Parole123" ar lielo "P", tad serveris izmet, ka parole nav pareiza.**

- **Drošībai, serveris sajauc lietotāju paroles ar specifisku servera paroli, kura nav citiem lietotājiem pieejama, kā arī to izmanto pie reģistrēšanās un pie ieiešanas kontā.**




##


## Informācija
### Svarīgs

### Pašlaik visa mājaslapa tiek uzturēta uz render.com serveriem, tāpēc pie neaktivitātes, tā izslēdzas, un, ieslēdzas, tikai tad, kad kāds mēģina tajā ieiet.
### Mājaslapa uzreiz neieslēdzas, ir jāpagaida kādas 30-50 sekundes pirms tā sāks darboties.

##

### Pamācība

1. Ielādējat mūsu aplikāciju https://adaptivenotepad.onrender.com/.
2. Tad kad esat palaiduši aplikāciju, nospiediet **F9**, lai to atvērtu, tālāk izveidojiet kontu.
3. Tagad jums ir iepsēja izveidot pašam savu teksta failu un to saglabāt, gan uz sava datora, gan mūsu datubāzē.
4. Ja vēlaties apskatīt savus saglabātos teksta failus, jums ir iespēja tos apskatīt mūsu mājaslapā https://adaptivenotepad.onrender.com/.


## PIEEJA LIETOTĀJAM UN VIRSLIETOTĀJAM

![abc](https://media.discordapp.net/attachments/1313895396766126140/1314304636819345429/image.png?ex=67534914&is=6751f794&hm=b3192689df5b06901167722542f06bfa76b12996319429e0b473b21df4a515bb&=&format=webp&quality=lossless&width=720&height=424)

## Veidotāji

[![Matīss Grūbe](https://static1.srcdn.com/wordpress/wp-content/uploads/2020/03/Vin-Diesel-In-Furious-7-next-to-paul-walker.jpg)](https://github.com/CodeMytz) |
:---:|
[Matīss Grūbe](https://github.com/CodeMytz)|
[![Daniels Leškevičs](https://cdn.mos.cms.futurecdn.net/PosvCa2386NXwo4cM4VWa3.jpg)](https://github.com/danielsleskevics)|
[Daniels Leškevičs](https://github.com/danielsleskevics)
