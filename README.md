# Ultrastar txt Documentation

Encoding should be UTF8

## :warning: Mandatory Attributes

### TITLE

The title of the song. This is the song name that will appear in the song selection screen.

```
#TITLE:Song Title
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

</details>

### ARTIST

The artist of the song. This is the name of the person or group who performed the song.

```
#ARTIST:Artist
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

</details>

### MP3

Filename of the audio file. This is the file that contains the sound of the song. It must be in the same folder as the txt file and should have the same name as the folder. See format support here: here

```
#MP3:Artist - Title.mp3
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

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
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

</details>

### GAP

Delay for the start the lyric in milliseconds.
Its used that the first word starts at 0. Otherwise the delay gap would be added to the start of the first line.

```
#GAP:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

</details>

## :information_source: Optional Attributes

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
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

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
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

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
| UltraStar               | 1.0.2 (2012-09-28)               | :heavy_check_mark: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :heavy_check_mark: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :heavy_check_mark: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :heavy_check_mark: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :heavy_check_mark: |

</details>

### VIDEOGAP

Specifies the delay in milliseconds between the start of the video and the start of the song. 
This value can be used to synchronize the video with the music.
This attribute is useful when the video and audio files are not perfectly synchronized and you need to adjust the timing of the video to match the audio. By setting a positive or negative value for VIDEOGAP, you can delay or advance the start of the video relative to the start of the song.

```
#VIDEOGAP:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### GENRE

Specifies the genre of the song. This information can be used to categorize songs by their musical style.
The value of the GENRE attribute can be any text string that describes the genre of the song. Some common genres include Pop, Rock, Hip-Hop, Country, and Jazz.

```
#GENRE:Pop, Rock, Jazz
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### EDITION

Specifies the SingStar edition of the song. See here: [SingStar-Editions](https://github.com/bohning/usdb_syncer/wiki/SingStar-Editions)
This information can be used to categorize songs by their edition.

```
#EDITION:SingStar Rocks! [DE]
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### CREATOR

Specifies the name of the person who created the ultrastar txt file. 
This information can be used to give credit to the person who created the file.
The value of the CREATOR attribute can be any text string that represents the name of the person who created the ultrastar txt file.

```
#CREATOR:UltraSinger [GitHub]
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### LANGUAGE

Specifies the language of the song. This information can be used to categorize songs by their language.
The value of the LANGUAGE attribute can be any text string that represents the language of the song.

```
#LANGUAGE:English
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### YEAR

Specifies the year the song was released. This information can be used to categorize songs by their release date.
The value of the YEAR attribute should be a four-digit number that represents the year the song was released.

```
#YEAR:2022
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### START

START specifies the time in seconds from the beginning of the audio file at which the song starts. This value can be used to skip any silence or intro at the beginning of the audio file.
The value should be positive integers that represent the start time of the song in seconds.

```
#START:123
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### END

Specifies the time in milliseconds from the beginning of the audio file at which the song ends. This value can be used to stop playback before any silence or outro at the end of the audio file.
The value should be positive integers that represent the end time of the song in milliseconds.

Keep it simple, its just seconds + 000
```
#END:678000
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### RESOLUTION

Changes the grid resolution of the editor.
Only for the editor and nothing for singing.

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### NOTESGAP

Todo: Unknown

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

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

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

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
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question:    |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question:    |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question:    |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question:    |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question:    |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question:    |

</details>

### PREVIEWSTART

Specifies the time in milliseconds from the beginning of the audio file at which the preview of the song starts. This value can be used to set the start time of the preview that is played when browsing songs.

```
#PREVIEWSTART:12345
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### MEDLEYSTARTBEAT

Specify the start beat of a medley section within the song. These value can be used to create a medley of multiple songs by specifying which section of each song should be included in the medley.
Needs `MEDLEYENDBEAT`

```
#MEDLEYSTARTBEAT:10
```


<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### MEDLEYENDBEAT

Specify the end beat of a medley section within the song. These value can be used to create a medley of multiple songs by specifying which section of each song should be included in the medley.
Needs `MEDLEYSTARTBEAT`

```
#MEDLEYENDBEAT:20
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### CALCMEDLEY

Specifies whether UltraStar should automatically calculate the medley section of the song. If this attribute is set to on, UltraStar will automatically determine the most suitable section of the song for a medley based on the note data.

```
#CALCMEDLEY:on
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### DUETSINGERP1 & DUETSINGERP2

Specify the names of the singers for a duet song. These values can be used to display the names of the singers on screen during a duet.

```
#DUETSINGERP1:John
#DUETSINGERP2:Jane
```

<details><summary>App Support</summary>

| App                     | Version                          | Supported       |
| ----------------------- | -------------------------------- | --------------- |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question: |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question: |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :grey_question: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question: |
| UltraStar World Party   | 21.02 (2021-02-07)               | :grey_question: |
| Vocaluxe                | 0.41 (2020-03-10)                | :grey_question: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question: |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question: |

</details>

### P1 and P2

Same as `DUETSINGERP1` and `DUETSINGERP2`

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :grey_question:    |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :grey_question:    |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :heavy_check_mark: |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :grey_question:    |
| UltraStar World Party   | 21.02 (2021-02-07)               | :x:                |
| Vocaluxe                | 0.41 (2020-03-10)                | :heavy_check_mark: |
| Performous              | 1.2.0 (2022-03-27)               | :grey_question:    |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :grey_question:    |

</details>

USDX Source - [USong.pas](https://github.com/UltraStar-Deluxe/USDX/blob/master/src/base/USong.pas#L1246)
US World Party Source: [USong.pas](https://github.com/ultrastares/ultrastar-worldparty/blob/master/src/base/USong.pas#L649)

### FIXER

Specifies the name of the person who made changes to the ultrastar txt file but want to give credit to the person who initialy created the file in `CREATOR`.

<details><summary>App Support</summary>

| App                     | Version                          | Supported          |
| ----------------------- | -------------------------------- | ------------------ |
| UltraStar               | 1.0.2 (2012-09-28)               | :x:                |
| UltraStar deluxe (USDX) | < 1.0.1a (2007-12-23)            | :x:                |
| UltraStar deluxe (USDX) | > 2020.4.0 (2020-04-30)          | :x:                |
| UltraStar deluxe CMD    | 1.0.1a r9.22 (2013-02-11)        | :x:                |
| UltraStar World Party   | 21.02 (2021-02-07)               | :heavy_check_mark: |
| Vocaluxe                | 0.41 (2020-03-10)                | :x:                |
| Performous              | 1.2.0 (2022-03-27)               | :x:                |
| UltraStar Play          | 0.9.0 (Pre-release) (2023-02-01) | :x:                |

</details>

Vocaluxe Source: [CSongLoader.cs](https://github.com/Vocaluxe/Vocaluxe/blob/develop/VocaluxeLib/Songs/CSongLoader.cs#L135)

- TITLE-ON-SORTING
- ARTIST-ON-SORTING
- AUTHOR and AUTOR
  - Same as CREATOR
  - Same as CREATOR
- VERSION
- SOURCE and YOUTUBE
- LENGTH
- ALBUM
- COMMENT
- VIDEOASPECT
- ENDSHORT
- P1 and P2
  - Same as DUETSINGERP1 and DUETSINGERP2

Performous Source: [song.cc](https://github.com/performous/performous/blob/master/game/song.cc)

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

USDX Manager Source: [UFiles.pas](https://github.com/UltraStar-Deluxe/USDX/blob/c56afde2d317feb9bee3196296e4d84234f4287b/src/base/UFiles.pas#L137)
