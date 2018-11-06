# voicelistJP - the dataset list for JP voice
voicelistJP is comprehensive Voice dataset database for Japanese speaker.  
Check the datasets which is good for your purpose!!  
I hope your pull request for adding dataset info!!


# List
| name                                   | id    | speaker# | data amount      | parallel | sr    | bit | info                          | references |
| -------------------------------------- | ----- | -------- | ---------------- | -------- | ----- | --- | ----------------------------- | ---------- |
| 声優統計コーパス                       | #sy   | 3        | #900 (3x3x3type) | yes      | 48k   | 16  | (long non-voice region)       |            |
| nico-opendata 音声読み上げデータセット | #nico | 1        | #100             | -        | 44.1k |     | parallel to #sy               |            |
| JSUT                                   | #jsut | 1        | 10 hours         | -        | 48k   | 16  | 無響室. Contain #sy parallel. |            |

[^sy_1]: 48kHz / 16bit の WAV ファイルであり [ref](https://voice-statistics.github.io/)  
[^nico_1]: check sampling rate by myself with librosa.core.load(path, sr=None)
[^jsut]: 音声データは48kHzでサンプリングされ，無響室で収録されました．一人の日本語女性話者の音声を収録しました．このコーパスは，10時間の音声 [ref](https://sites.google.com/site/shinnosuketakamichi/publication/jsut)

## other lang.
| name    | id     | speaker# | data# total | parallel | sr  | bit | info | link | references |
| ------- | ------ | -------- | ----------- | -------- | --- | --- | ---- | ---- | ---------- |
| VCC2016 | #vcc16 |          |             |          |     |     |      |      |            |
| VCC2018 | #vcc18 |          |             |          |     |     |      |      |            |


# links
[#sr]([link](https://voice-statistics.github.io/))
