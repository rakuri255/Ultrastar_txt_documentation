> [!WARNING]
> This page is moved here:
>
> [WEB](https://usdx.eu/format/)
>
> [GitHub - UltraStar-Deluxe/format](https://github.com/UltraStar-Deluxe/format)
>

# Ultrastar txt Documentation

Encoding should be UTF8

## Table of Contents

- [Ultrastar txt Documentation](#ultrastar-txt-documentation)
  - [Table of Contents](#table-of-contents)
  - [:warning: Mandatory Attributes](#warning-mandatory-attributes)
    - [TITLE](#title)
    - [ARTIST](#artist)
    - [MP3](#mp3)
    - [BPM](#bpm)
    - [Notes](#notes)
      - [Note description](#note-description)
      - [End of phrase](#end-of-phrase)
      - [NoteTypes](#notetypes)
        - [Normal `:`](#normal-)
        - [Golden `*`](#golden-)
        - [Freestyle `F`](#freestyle-f)
        - [Rap `R`](#rap-r)
        - [Rap Golden `G`](#rap-golden-g)
  - [:information\_source: Optional Attributes](#information_source-optional-attributes)
    - [GAP](#gap)
    - [COVER](#cover)
    - [BACKGROUND](#background)
    - [VIDEO](#video)
    - [VIDEOGAP](#videogap)
    - [GENRE](#genre)
    - [EDITION](#edition)
    - [CREATOR](#creator)
    - [LANGUAGE](#language)
    - [YEAR](#year)
    - [START](#start)
    - [END](#end)
    - [RESOLUTION](#resolution)
    - [NOTESGAP](#notesgap)
    - [RELATIVE](#relative)
    - [ENCODING](#encoding)
    - [PREVIEWSTART](#previewstart)
    - [MEDLEYSTARTBEAT](#medleystartbeat)
    - [MEDLEYENDBEAT](#medleyendbeat)
    - [CALCMEDLEY](#calcmedley)
    - [DUETSINGERP1 \& DUETSINGERP2](#duetsingerp1--duetsingerp2)
    - [P1 and P2](#p1-and-p2)
  - [Special](#special)
    - [Multiple](#multiple)
      - [ALBUM](#album)
      - [VERSION](#version)
      - [LENGTH](#length)
    - [UltraStar World Party](#ultrastar-world-party)
      - [FIXER](#fixer)
    - [Vocaluxe](#vocaluxe)
      - [TITLE-ON-SORTING](#title-on-sorting)
      - [ARTIST-ON-SORTING](#artist-on-sorting)
      - [AUTHOR and AUTOR](#author-and-autor)
      - [SOURCE and YOUTUBE](#source-and-youtube)
      - [COMMENT](#comment)
      - [VIDEOASPECT](#videoaspect)
      - [Preview](#preview)
      - [ENDSHORT](#endshort)
    - [Yass](#yass)
      - [ID](#id)
    - [UltraStar Play](#ultrastar-play)
      - [PreviewEnd](#previewend)
      - [VOCALS](#vocals)
    - [Performous](#performous)
  - [Source](#source)

## :warning: Mandatory Attributes

### TITLE

The title of the song. This is the song name that will appear in the song selection screen.

```
#TITLE:Song Title
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### ARTIST

The artist of the song. This is the name of the person or group who performed the song.

```
#ARTIST:Artist
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### MP3

Filename of the audio file. This is the file that contains the sound of the song. It must be in the same folder as the txt file and should have the same name as the folder. See format support here: here

```
#MP3:Artist - Title.mp3
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### BPM

Speed of the song in Ultrastar Beats Per Minute. Which is not the real song BPM.
The UltraStar BPM information is a quarter of the real BPM.

```
#BPM:400
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### Notes

#### Note description

The sing line is defined so that it has the `NoteType`, `StartBeat`, `Lenght`, `Pitch` and `Text`.

- For the syles see [NoteTypes](#noteTypes).
- The `StartBeat` and `Lenght` must be calculated against the `BPM`, `GAP` and `Relative`. Is a beat number.
- The pitch describes the note as a number. The number 0 corresponds to the note C4 and Midi Note 60.
- Text is the part of the lyrics that is sung in this note.

```
NoteType StartBeat Lenght Pitch Text
```

```
: 10 10 10 Text
```

#### End of phrase

`-` represents the end of a phrase and how long it lasts by the `StartBeat`. The length is calculated against the `BPM`, `GAP` and `Relative`. Is a beat number.

```
- StartBeat
```

#### NoteTypes

##### Normal `:`

The normal note.

```
: 0 1 8 Normal
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

##### Golden `*`

The golden note. Gives twice the point of a normal point

```
* 0 1 8 Golden
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

##### Freestyle `F`

Note that will NOT be scored.

```
F 0 1 8 Freestyle
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

##### Rap `R`

Rap note

```
R 0 1 8 Rap
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported           | Comment      |
| ----------------------- | -------------------------------- | ------------------- | ------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark:  |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark:  |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_equals_sign: | Is Freestyle |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:     |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark:  |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark:  |

</details>

##### Rap Golden `G`

Golden Rap note. Gives twice the point of a rap point

```
G 0 1 8 RapGolden
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported           | Comment      |
| ----------------------- | -------------------------------- | ------------------- | ------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark:  |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark:  |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_equals_sign: | Is Freestyle |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:     |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark:  |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark:  |

</details>

## :information_source: Optional Attributes

### GAP

Delay for the start the lyric in milliseconds.
Its used that the first word starts at 0. Otherwise the delay gap would be added to the start of the first line.

```
#GAP:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### COVER

Filename of the cover image. Should end with `*[CO].jpg`
This is an image that shows the album cover or a picture related to the song.
It should be in 1:1 apec ratio.

```
#COVER:Artist - Title [CO].jpg
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### BACKGROUND

Filename of the background image. Is shown when there is no video. Should with `*[BG].jpg`
This will be shown when there is no `VIDEO` available.

```
#BACKGROUND:Artist - Title [BG].jpg
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### VIDEO

Filename of the video file.
This is a video that shows a music video or other visual content related to the song.
The sound of the video is not played.
It must be in a format supported by UltraStar, such as MP4 or AVI.
See format support here: here

```
#VIDEO:Artist - Title.mp4
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### VIDEOGAP

Specifies the delay in milliseconds between the start of the video and the start of the song.
This value can be used to synchronize the video with the music.
This attribute is useful when the video and audio files are not perfectly synchronized and you need to adjust the timing of the video to match the audio. By setting a positive or negative value for VIDEOGAP, you can delay or advance the start of the video relative to the start of the song.

```
#VIDEOGAP:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### GENRE

Specifies the genre of the song. This information can be used to categorize songs by their musical style.
The value of the GENRE attribute can be any text string that describes the genre of the song. Some common genres include Pop, Rock, Hip-Hop, Country, and Jazz.

```
#GENRE:Pop, Rock, Jazz
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### EDITION

Specifies the SingStar edition of the song. See here: [SingStar-Editions](https://github.com/bohning/usdb_syncer/wiki/SingStar-Editions)
This information can be used to categorize songs by their edition.

```
#EDITION:SingStar Rocks! [DE]
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### CREATOR

Specifies the name of the person who created the ultrastar txt file.
This information can be used to give credit to the person who created the file.
The value of the CREATOR attribute can be any text string that represents the name of the person who created the ultrastar txt file.

```
#CREATOR:UltraSinger [GitHub]
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### LANGUAGE

Specifies the language of the song. This information can be used to categorize songs by their language.
The value of the LANGUAGE attribute can be any text string that represents the language of the song.

```
#LANGUAGE:English
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### YEAR

Specifies the year the song was released. This information can be used to categorize songs by their release date.
The value of the YEAR attribute should be a four-digit number that represents the year the song was released.

```
#YEAR:2022
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### START

START specifies the time in seconds from the beginning of the audio file at which the song starts. This value can be used to skip any silence or intro at the beginning of the audio file.
The value should be positive integers that represent the start time of the song in seconds.

```
#START:123
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### END

Specifies the time in milliseconds from the beginning of the audio file at which the song ends. This value can be used to stop playback before any silence or outro at the end of the audio file.
The value should be positive integers that represent the end time of the song in milliseconds.

Keep it simple, its just seconds + 000

```
#END:678000
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### RESOLUTION

Changes the grid resolution of the editor.
Only for the editor and nothing for singing.

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

### NOTESGAP

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

### RELATIVE

Specifies whether the note timings in the file are relative to the previous note or absolute. If this attribute is set to yes, the note timings are relative to the previous note. If it is set to no or not present, the note timings are absolute.
If this line is missing, then the timestamps are absolute.

```
#RELATIVE:yes
```

Relative timestamps make working on a TXT file much easier, because if you want to insert a pause, you don't have to adjust all following timestamps, but only the ones until the end of the line.
If you now want to change from absolute to relative timestamps yourself, this means a lot of manual work.

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question:    |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### ENCODING

:warning: Deprecated: The games should be able to detect the encoding themselves.
For Vocaluxe there is a updated version that can detect the encoding itself. [Vocaluxe fork by flokuep](https://github.com/flokuep/Vocaluxe)

Specifies the character encoding used in the txt file. This attribute can be used to ensure that special characters are displayed correctly.

```
#ENCODING:UTF8
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### PREVIEWSTART

Specifies the time in milliseconds from the beginning of the audio file at which the preview of the song starts. This value can be used to set the start time of the preview that is played when browsing songs.

```
#PREVIEWSTART:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question:    |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### MEDLEYSTARTBEAT

Specify the start beat of a medley section within the song. These value can be used to create a medley of multiple songs by specifying which section of each song should be included in the medley.
Needs `MEDLEYENDBEAT`

```
#MEDLEYSTARTBEAT:10
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### MEDLEYENDBEAT

Specify the end beat of a medley section within the song. These value can be used to create a medley of multiple songs by specifying which section of each song should be included in the medley.
Needs `MEDLEYSTARTBEAT`

```
#MEDLEYENDBEAT:20
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### CALCMEDLEY

Specifies whether UltraStar should automatically calculate the medley section of the song. If this attribute is set to on, UltraStar will automatically determine the most suitable section of the song for a medley based on the note data.

```
#CALCMEDLEY:on
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

### DUETSINGERP1 & DUETSINGERP2

Specify the names of the singers for a duet song. These values can be used to display the names of the singers on screen during a duet.

```
#DUETSINGERP1:John
#DUETSINGERP2:Jane
#DUETSINGERP3:Tina
...
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          | Comment         |
| ----------------------- | -------------------------------- | ------------------ | --------------- |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: | up to 2 singers |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: | up to 4 singers |

</details>

### P1 and P2

Same as `DUETSINGERP1` and `DUETSINGERP2`

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

## Special

### Multiple

#### ALBUM

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

#### VERSION

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

#### LENGTH

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### UltraStar World Party

#### FIXER

Specifies the name of the person who made changes to the ultrastar txt file but want to give credit to the person who initialy created the file in `CREATOR`.

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

### Vocaluxe

#### TITLE-ON-SORTING

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### ARTIST-ON-SORTING

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### AUTHOR and AUTOR

Same as CREATOR

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### SOURCE and YOUTUBE

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### COMMENT

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### VIDEOASPECT

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### Preview

Todo: Unknown
//This is stored in ms not like PREVIEWSTART!

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### ENDSHORT

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

### Yass

#### ID

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |
| Yass                    | 2.4.3 (2023-03-18)               | :heavy_check_mark: |

</details>

### UltraStar Play

#### PreviewEnd

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :x:                |

</details>

#### VOCALS

If the song at #MP3 is an instrumental version you can add an audio file containing the vocals here.

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:             |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:             |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:             |
| Performous              | 1.2.0 (2022-03-27)               | :x:             |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |
| Yass                    | 2.4.3 (2023-03-18)               | :x:             |

</details>

### Performous

- txtFileFolder
- txtFile
- artist
- title
- language
- edition
- creator
- genre
- cover
- background
- videoFile
- midiFile
- videoGap
- start
- previewStart
- duration
- songFile
- vocals
- vocalsBacking
- preview
- guitar
- bass
- drums
- drumsSnare
- drumnsCymbals
- drumsToms
- keyboard
- guitarCoop
- guitarRhythm

## Source

- USDX Source - [USong.pas](https://github.com/UltraStar-Deluxe/USDX/blob/master/src/base/USong.pas#L1246)
- US World Party Source: [USong.pas](https://github.com/ultrastares/ultrastar-worldparty/blob/master/src/base/USong.pas#L649)
- Vocaluxe Source: [CSongLoader.cs](https://github.com/Vocaluxe/Vocaluxe/blob/develop/VocaluxeLib/Songs/CSongLoader.cs#L135)
- Yass: [YassSong](https://github.com/SarutaSan72/Yass/blob/master/src/yass/YassSong.java), [YassNote](https://github.com/SarutaSan72/Yass/blob/master/src/yass/renderer/YassNote.java), [YassSongList](https://github.com/SarutaSan72/Yass/blob/master/src/yass/YassSongList.java#L3260)
- UltraStar Play: [SongMetaBuilder.cs](https://github.com/UltraStar-Deluxe/Play/blob/master/UltraStar%20Play/Packages/playshared/Runtime/Song/Builder/SongMetaBuilder.cs#L11)
- Performous Source: [song.cc](https://github.com/performous/performous/blob/master/game/song.cc)
