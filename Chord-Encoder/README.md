# Chord Encoder - 40 points
## Description

I tried creating my own [chords](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/chords.txt), but my [encoded sheet music](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/notes.txt) is a little hard to read. Please play me my song!

[chord_encoder.py](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/chord_encoder.py)

## Flag

```
flag{zats_wot_1_call_a_meloD}
```

## Solution

1. Langkah pertama konversi isi dari [encoded sheet music](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/notes.txt) ke bentuk [lagu.txt](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/lagu.txt). 

2. Kemudian konversi isi dari lagu.txt sesuai dengan [chords.txt](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/chords.txt).
Hasil konversi adalah [lagu2.txt](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/lagu2.txt).

3. Jalankan program [python](https://github.com/lumbricina/TJCTF-2020-05311840000044/blob/master/Reversing/Chord%20Encoder/chord_encoder.py) dan flag akan didapat.