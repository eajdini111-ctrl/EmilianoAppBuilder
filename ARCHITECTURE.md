# Emiliano App Builder — Arkitektura e projektit

## Qëllimi

Emiliano App Builder është një platformë autonome për krijimin, zhvillimin, testimin, versionimin dhe ndërtimin e aplikacioneve Android me ndihmën e inteligjencës artificiale.

Platforma duhet të jetë e thjeshtë për përdorim, e përshtatshme për TalkBack dhe e aftë të vazhdojë zhvillimin e një projekti nga versioni i fundit i ruajtur.

## Menaxhimi i projekteve

Platforma duhet të mundësojë:

- krijimin e projekteve të reja;
- ruajtjen e projekteve;
- hapjen e projekteve ekzistuese;
- ruajtjen e të gjithë skedarëve të projektit;
- historikun e versioneve;
- rikthimin në një version të mëparshëm;
- ruajtjen e versionit aktual kur përdoruesi e miraton atë.

Kur përdoruesi thotë se një version është në rregull, ai version bëhet baza e re për zhvillimin e mëtejshëm.

## Inteligjenca artificiale

AI duhet të jetë në gjendje të kuptojë kërkesat e përdoruesit në gjuhë natyrore dhe të:

- krijojë aplikacione;
- modifikojë aplikacione ekzistuese;
- krijojë dhe ndryshojë skedarët e projektit;
- analizojë gabimet;
- propozojë dhe zbatojë përmirësime;
- ruajë kontekstin e projektit;
- vazhdojë zhvillimin nga versioni aktual.

AI nuk duhet të fshijë një version të mëparshëm pa e ruajtur atë në historikun e projektit.

## Arkitekturë modulare

Platforma duhet të përdorë një arkitekturë modulare.

Motorët, bibliotekat dhe shërbimet e jashtme duhet të trajtohen si varësi të kontrolluara dhe të zëvendësueshme.

Platforma nuk duhet të varet nga një motor i vetëm për të gjitha funksionet.

AI duhet të jetë në gjendje të zgjedhë komponentin më të përshtatshëm për detyrën që kërkon përdoruesi.

Kur është e mundur, duhet të preferohen komponentë me burim të hapur, të mirëmbajtur dhe me licenca të përshtatshme për përdorimin e projektit.

## Sistemi audio

Platforma duhet të ketë mbështetje për krijimin e aplikacioneve audio profesionale.

Duhet të parashikohet mbështetje për:

- regjistrim audio;
- regjistrim stereo;
- përpunim audio;
- prerje dhe bashkim audio;
- efekte audio;
- miksim;
- analiza të sinjalit audio;
- zbulim të tempos;
- zbulim të beat-it;
- analizë ritmike;
- krijim ritmesh;
- përdorim të samplerave të siguruar nga përdoruesi;
- sinkronizim të samplerave me tempo;
- përpunim në kohë reale kur teknologjia e përdorur e lejon;
- analizë melodike;
- zbulim të notave;
- kthim të audios në MIDI kur teknologjia e përdorur e lejon;
- analizë të regjistrimeve të instrumenteve, përfshirë klarinetën;
- krijim dhe përpunim MIDI;
- lidhje midis audios, MIDI-t, samplerave dhe ritmit.

Shembull i një kërkese të ardhshme:

"Përdor këtë regjistrim beatbox, zbulo ritmin dhe temp­on, ndaj tingujt sipas ritmit dhe krijo një pattern ritmik duke përdorur samplerat që të jap."

Një shembull tjetër:

"Analizo këtë regjistrim të klarinetës, zbulo notat dhe ritmin dhe krijo MIDI."

Platforma duhet të jetë e ndërtuar në mënyrë që këto funksione të mund të zhvillohen gradualisht dhe të përdorin motorë të specializuar sipas nevojës.

## Ndërtimi i aplikacioneve

Platforma duhet të jetë në gjendje të krijojë një projekt real Android nga skedarët e gjeneruar.

Duhet të parashikohet një sistem ndërtimi që mund të:

- kontrollojë projektin;
- zbulojë gabimet;
- ndërtojë projektin;
- krijojë APK;
- ruajë versionin e ndërtuar;
- mundësojë shkarkimin e APK-së.

GitHub mund të përdoret për ruajtjen e kodit, historikun e versioneve dhe automatizimin e ndërtimeve.

GitHub nuk duhet të konsiderohet si motori i vetëm i platformës.

## Automatizimi

Procesi duhet të jetë sa më autonom:

Kërkesa e përdoruesit
→ analiza nga AI
→ planifikimi
→ krijimi ose ndryshimi i skedarëve
→ kontrolli i projektit
→ testimi
→ ruajtja e versionit
→ ndërtimi
→ APK.

Çdo fazë duhet të jetë e kontrollueshme dhe të japë një status të qartë për përdoruesin.

## Aksesueshmëria

Platforma duhet të projektohet që në fillim për përdoruesit e TalkBack.

Të gjithë kontrollet duhet të kenë etiketa të qarta dhe kuptimplota.

Fokusi i ekranit  duhet të menaxhohet në mënyrë të parashikueshme.

Mesazhet e suksesit, gabimeve dhe statusit duhet të jenë të lexueshme nga TalkBack.

Navigimi duhet të jetë i thjeshtë dhe të shmangë kontrollet e panevojshme ose elementet që nuk mund të përdoren me lexues ekrani.

## Siguria

Çelësat API, fjalëkalimet dhe kredencialet nuk duhet të vendosen drejtpërdrejt në kodin e aplikacionit ose në skedarët publikë të projektit.

Varësitë dhe shërbimet e jashtme duhet të kontrollohen dhe të dokumentohen.

## Parimi kryesor

Emiliano App Builder duhet të jetë një platformë që koordinon AI-në, kodin, motorët audio, bibliotekat, testimin, versionet dhe ndërtimin e aplikacioneve.

Qëllimi nuk është të krijohet çdo teknologji nga zero, por të ndërtohet një sistem autonom që zgjedh dhe përdor komponentët më të përshtatshëm për çdo  projekt.
