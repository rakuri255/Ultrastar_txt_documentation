# Ultrastar txt Documentation

Encoding should be UTF8

## :warning: Mandatory Attributes

### TITLE

The title of the song.

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### ARTIST

The artist of the song.

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### MP3

Filename of the audio file.
See format support here: here

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### GAP

Delay for the start the lyric in milliseconds

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

## :information_source: Optional Attributes

### COVER

Path to cover. Should end with `*[CO].jpg`

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### BACKGROUND

Path to background. Is shown when there is no video. Should with `*[BG].jpg`

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### VIDEO

Filename of the video file.
The sound of the video is not played.
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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :heavy_check_mark: |

</details>

### VIDEOGAP

Delay for the start the video in milliseconds

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

### GENRE

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### EDITION

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### CREATOR

- name or names of song creators

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### LANGUAGE

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### YEAR

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### START

Specifies from which second the song is played.
Normaly used when the song has a long into that you want to skip.

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### END

Specifies from which second the song will end.
Normaly used when the song has a long outro that you want to skip.

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### NOTESGAP

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### RELATIVE

Specifies whether the timestamps start again from 0 after each line or not ("yes" means they start again from 0).
If this line is missing, then the timestamps are absolute.
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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### ENCODING

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### PREVIEWSTART

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### MEDLEYSTARTBEAT

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### MEDLEYENDBEAT

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### CALCMEDLEY

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### DUETSINGERP1

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

### DUETSINGERP2

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question: |

</details>

USDX - [USong.pas](https://github.com/UltraStar-Deluxe/USDX/blob/master/src/base/USong.pas#L1246)

### P1 and P2

Same as DUETSINGERP1 and DUETSINGERP2

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :grey_question:    |

</details>

US World Party Source: [USong.pas](https://github.com/ultrastares/ultrastar-worldparty/blob/master/src/base/USong.pas#L649)

### FIXER

name or names of song fixers

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
| UltraStar Play          | 0.7.0 (Pre-release) (2022-08-20) | :x:                |

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
