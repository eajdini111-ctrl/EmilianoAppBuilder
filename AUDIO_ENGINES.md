# AUDIO ENGINES — Emiliano App Builder

## Qëllimi

Emiliano App Builder duhet të ketë një arkitekturë audio profesionale dhe modulare.

Platforma nuk duhet të varet nga një motor i vetëm audio. Në vend të kësaj, ajo duhet të jetë në gjendje të përdorë motorë dhe biblioteka të ndryshme sipas funksionit që kërkon aplikacioni.

AI duhet të analizojë kërkesën e përdoruesit dhe të zgjedhë teknologjinë më të përshtatshme për detyrën.

## Motorë dhe biblioteka që duhen hulumtuar

Platforma duhet të hulumtojë dhe të vlerësojë teknologji si:

- Google Oboe për audio me vonesë të ulët në Android;
- aubio për analizë të pitch-it, onset-it, beat-it dhe tempos;
- TarsosDSP për analizë dhe përpunim të sinjalit audio;
- Essentia për analizë të avancuar muzikore dhe audio;
- FFmpeg për dekodim, enkodim dhe konvertim të formateve audio dhe video;
- JUCE ose teknologji të ngjashme për aplikacione dhe përpunim audio profesional, kur licenca dhe arkitektura e projektit e lejojnë;
- motorë të tjerë të specializuar që mund të zbulohen dhe vlerësohen nga AI.

Këto janë kandidatë për hulumtim dhe jo varësi të detyrueshme.

Para përdorimit të çdo biblioteke ose motori duhet të kontrollohen:

- licenca;
- përdorimi komercial;
- kërkesat për shpërndarje;
- varësitë;
- përputhshmëria me Android;
- performanca;
- përpunimi në kohë reale;
- vonesa;
- mirëmbajtja e projektit.

## Audio në kohë reale

Platforma duhet të mbështesë, kur pajisja dhe teknologjia e përdorur e lejojnë:

- regjistrim në kohë reale;
- monitorim audio;
- përpunim me vonesë të ulët;
- efekte në kohë reale;
- analizë të sinjalit;
- zbulim të ritmit;
- zbulim të tempos;
- sinkronizim me tempo;
- përdorim të samplerave në kohë reale.

Arkitektura duhet të shmangë vonesat e panevojshme dhe të përdorë API-të më të përshtatshme të Android-it për audio profesionale.

## Analiza e ritmit

Një aplikacion i krijuar nga platforma duhet të mund të analizojë një regjistrim audio dhe, kur algoritmet e përdorura e lejojnë, të:

- zbulojë tempo-n;
- zbulojë beat-in;
- zbulojë onset-et;
- analizojë ritmin;
- krijojë një grid ritmik;
- sinkronizojë materiale audio me tempo;
- ndryshojë tempo-n pa ndryshuar domosdoshmërisht lartësinë e tingullit.

## Beatbox në ritëm muzikor

Platforma duhet të mundësojë zhvillimin e aplikacioneve që analizojnë një regjistrim beatbox ose tinguj të bërë me gojë.

Shembull:

Përdoruesi regjistron një beatbox.

Sistemi:

1. analizon sinjalin;
2. zbulon onset-et dhe beat-et;
3. vlerëson tempo-n;
4. ndan ngjarjet ritmike;
5. krijon një strukturë ritmike;
6. mund të zëvendësojë tingujt e regjistruar me samplerat e dhënë nga përdoruesi;
7. sinkronizon samplerat me grid-in ritmik;
8. krijon një pattern ritmik;
9. e luan atë në kohë reale kur performanca e pajisjes e lejon.

Qëllimi është që përdoruesi të mund të përdorë zërin e tij si burim për krijimin e një ritmi muzikor.

## Samplerat e përdoruesit

Aplikacionet e krijuara duhet të mund të përdorin samplerat që siguron vetë përdoruesi.

Sistemi duhet të parashikojë:

- importimin e samplerave;
- organizimin e tyre;
- caktimin e samplerave sipas ngjarjeve ritmike;
- sinkronizimin me tempo;
- prerjen dhe përpunimin e samplerave;
- ndryshimin e kohëzgjatjes;
- përdorimin në playback;
- përdorimin në kohë reale kur është e mundur.

## Audio në MIDI

Platforma duhet të hulumtojë teknologji për kthimin e audios në MIDI.

Aplikacionet e ardhshme duhet të mund të analizojnë, kur algoritmet e lejojnë:

- lartësinë e tingullit;
- notat;
- kohën e fillimit të notave;
- kohëzgjatjen;
- ritmin;
- dinamikën kur teknologjia e mbështet.

Rezultati mund të përdoret për krijimin e një skedari MIDI ose për kontroll MIDI në kohë reale.

## Analiza e klarinetës

Platforma duhet të parashikojë aplikacione që mund të analizojnë regjistrime të klarinetës.

Shembull:

Përdoruesi regjistron një frazë klarinete.

Sistemi analizon:

- notat;
- pitch-in;
- kohën;
- ritmin;
- onset-et;
- frazimin kur algoritmet e lejojnë.

Më pas sistemi mund të  krijojë MIDI nga analiza e regjistrimit, kur rezultati është mjaftueshëm i besueshëm.

Duhet të merret parasysh se instrumentet akustike, përfshirë klarinetën, mund të kërkojnë algoritme të specializuara dhe përpunim paraprak të sinjalit.

## Efektet audio

Platforma duhet të mbështesë zhvillimin e aplikacioneve me efekte audio si:

- gain;
- volume;
- pan;
- equalizer;
- compressor;
- limiter;
- reverb;
- delay;
- distortion;
- filter;
- pitch shifting;
- time stretching;
- noise reduction kur teknologjia e lejon.

Motorët duhet të zgjidhen sipas kërkesave të projektit dhe performancës së pajisjes.

## Formate audio

Platforma duhet të parashikojë mbështetje për formate të zakonshme audio, sipas nevojës së aplikacionit, duke përfshirë:

- WAV;
- PCM;
- FLAC;
- MP3;
- AAC;
- formate të tjera të mbështetura nga teknologjitë e zgjedhura.

FFmpeg ose teknologji të tjera mund të përdoren kur nevojitet mbështetje më e gjerë për formate.

## Zgjedhja automatike e motorit

AI nuk duhet të përdorë gjithmonë të njëjtën bibliotekë.

Shembull:

Nëse përdoruesi kërkon regjistrim me vonesë shumë të ulët në Android, AI duhet të vlerësojë një motor të përshtatshëm për audio të drejtpërdrejtë.

Nëse kërkon analizë të tempos dhe beat-it, AI duhet të vlerësojë bibliotekat e analizës muzikore.

Nëse kërkon konvertim formatesh, AI duhet të vlerësojë një motor të përshtatshëm për dekodim dhe enkodim.

Nëse kërkon audio në MIDI, AI duhet të zgjedhë algoritme të përshtatshme për pitch dhe analizë melodike.

Pra:

Kërkesa e përdoruesit
→ analiza e funksionit
→ zgjedhja e motorit
→ kontrolli i licencës
→ integrimi
→ testimi
→ optimizimi.

## Varësitë

Çdo varësi duhet të dokumentohet.

Platforma duhet të ruajë:

- emrin e bibliotekës;
- versionin;
- burimin;
- licencën;
- funksionin për të cilin përdoret;
- varësitë e saj;
- mënyrën e integrimit;
- kufizimet e njohura.

Versionet e varësive duhet të jenë të kontrolluara dhe të riprodhueshme.

## Pavarësia nga shërbimet e jashtme

Emiliano App Builder duhet të jetë sa më autonom.

Megjithatë, autonomia nuk do të thotë që duhet të krijojë çdo motor nga zero.

Platforma mund të përdorë:

- biblioteka me burim të hapur;
- motorë profesionalë;
- mjete Android;
- shërbime të jashtme;
- modele të inteligjencës artificiale;

kur ato janë teknikisht dhe ligjërisht të përshtatshme.

Duhet të shmanget varësia e panevojshme nga një shërbim i vetëm.

## Parimi kryesor audio

Emiliano App Builder duhet të jetë një orkestrues i teknologjive audio.

AI duhet të jetë në gjendje të zgjedhë kombinimin më të përshtatshëm të motorëve dhe bibliotekave për çdo aplikacion.

Qëllimi është që përdoruesi të mund të kërkojë një funksion audio në gjuhë natyrore dhe platforma të ndërtojë arkitekturën teknike të nevojshme për ta realizuar atë.

Shembull:

"Përdor këtë beatbox, zbulo tempo-n dhe ritmin, përdor samplerat e mi dhe krijo një ritëm të sinkronizuar në kohë reale."

Platforma duhet të jetë e projektuar që një kërkesë e tillë të mund të shndërrohet gradualisht në një aplikacion real  Android.
