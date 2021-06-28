# awesome-audio-dataset

## audio modality

### Music with tag
- MTAT
    - download : [MTAT](https://mirg.city.ac.uk/codeapps/the-magnatagatune-dataset)
    - sampleCNN split: [Sample-level Deep Convolutional Neural Networks for Music Auto-tagging using Raw Waveforms](https://github.com/jongpillee/music_dataset_split)
    - EvalCNN split: [Evaluation of CNN-based Automatic Music Tagging Models](https://github.com/minzwon/sota-music-tagging-models/tree/master/split)
```
# sampleCNN split
guitar, classical, slow, techno, strings, drums, electronic
rock, fast, piano, ambient, beat, violin, vocal, synth, female
indian, opera, male, singing, vocals, noVocals, harpsichord, loud, quiet
flute, woman, maleVocal, noVocal, pop, soft, sitar, solo, man, classic
choir, voice, newAge, dance, maleVoice, femaleVocal, beats, harp, cello,
noVoice, weird, country, femaleVoice, metal, choral
```

- MSD
    - download : not available
    - sampleCNN split: [Sample-level Deep Convolutional Neural Networks for Music Auto-tagging using Raw Waveforms](https://github.com/jongpillee/music_dataset_split)
    - EvalCNN split: [Evaluation of CNN-based Automatic Music Tagging Models](https://github.com/minzwon/sota-music-tagging-models/tree/master/split)
    - Last.fm Tag: 
    - Allmusic Tag: 
```
# sampleCNN split
rock, pop, alternative, indie, electronic, female vocalists, dance, 00s, alternative rock,
jazz, beautiful, metal, chillout, male vocalists, classic rock, soul, indie rock, Mellow, electronica,
80s, folk, 90s, chill, instrumental, punk, oldies, blues, hard rock, ambient, acoustic, experimental, 
female vocalist, guitar, Hip-Hop, 70s, party, country, easy listening, sexy, catchy, funk, electro
heavy metal, Progressive rock, 60s, rnb, indie pop, sad, House, happy
```
- Music4all
    - download : [music4all](https://sites.google.com/view/contact4music4all)
```
- id: Unique 16 characters identifier for the song in the database.  
- artist: Name of the artist that published the song in last.fm. There are 16,269 unique artists in the database. 
- song: Name of the song.
- tags: User-given tags from the last.fm application, with 19,541 unique tags.  
- genres: List of genres tags associated with the song. There are 853 unique genre tags in the database.
```
- Jamendo
    - download : [jamendo](https://github.com/MTG/mtg-jamendo-dataset)
    - EvalCNN split: [Evaluation of CNN-based Automatic Music Tagging Models](https://github.com/minzwon/sota-music-tagging-models/tree/master/split)
```
alternative, ambient, atmospheric, chillout, classical, dance, downtempo, easylistening, electronic, experimental, folk, funk, hiphop, house, indie, instrumentalpop, jazz, lounge, metal, newage, orchestral, pop, popfolk, poprock, reggae, rock, soundtrack, techno, trance, triphop, world, acousticguitar, bass, computer, drummachine, drums, electricguitar, electricpiano, guitar, keyboard, piano, strings, synthesizer, violin, voice, emotional, energetic, film, happy, relaxing
```

### Env
- TAU Urban Acoustic Scenes 2020
    - Development download : [music4all](https://zenodo.org/record/3819968)
    - Evaluation download : [music4all](https://zenodo.org/record/4767109#.YNnz6JMzaZw)
```
Airport - airport
Indoor shopping mall - shopping_mall
Metro station - metro_station
Pedestrian street - street_pedestrian
Public square - public_square
Street with medium level of traffic - street_traffic
Travelling by a tram - tram
Travelling by a bus - bus
Travelling by an underground metro - metro
Urban park - park
```
- Clotho
    - download : [Clotho](https://zenodo.org/record/4783391)
```
6974 audio samples
34870 captions(each audio sample has five captions))
```
- SINS
- TUT Acoustic scenes 2017
- FUSS dataset
- FSD50K dataset
- YFCC100M dataset

### Sound Scape & Sound Effect
- EMO SoundScape
    - download : [emo-soundscape](https://metacreation.net/emo-soundscapes/)

### Speech
- COMMONVOICE
    - download : [commonvoice](https://commonvoice.mozilla.org/en/datasets)
- LibroSpeech
    - download : [librospeech](https://www.openslr.org/12)
- LJSPEECH
    - download : [ljspeech](https://keithito.com/LJ-Speech-Dataset/)

## with langauge
- Env with Caption : Clotho dataset
- Music with Lyrics : Music4ALL
- Music with Album Review : MuMu Dataset (With MSD)

## with vision
- Music with Album Cover(Image) : MuMu Dataset (With MSD)
- Env with Media(Video) : YoutubeSet

## with playlist
- Musicwith Music4all