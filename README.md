# Algoritma
## memindahkan Air
1. mulai
2. siapkan 1 gelas kosong (gelas C)
3. pindahkan isi gelas teh ke dalam gelas kosong (gelas C)
4. pindahkan isi gelas kopi ke dalam gelas bekas teh (gelas A)
5. pindahkan isi gelas teh ke dalam gelas bekas kopi (gelas B)
6. selesai


## menentukan bilangan ganjil atau genap
1. mulai
2. tentukan atau pilih nilai yang akan dicari tau genap atau ganjil
3. terapkan operasi matematika modulo dengan angka 2, ke nilai awal yang sudah dipilih, yang akan memberikan sisa pembagian
4. jika sisa pembagian 1, maka angka yang dipilih diawal adalah ganjil
5. jika sisa pembagian 0, maka angka yang dipilih diawal adalah genap
6. selesai

### flowchart
```mermaid

flowchart LR
    Start((mulai))
    Nilai[/Nilai/]
    Kondisi{Nilai % 2 == 0}
    P2_1[/#quot;Genap#quot;/]
    P2_2[/#quot;Ganjil#quot;/]
    End(((selesai)))

    Start --> Nilai
    Nilai --> Kondisi
    Kondisi --> |ya| P2_1
    Kondisi --> |tidak| P2_2

    P2_1 --> End
    P2_2 --> End

```

## menghitung luas dan keliling lingkaran
1. mulai
2. tentukan nilai jari - jari lingkaran (r)
3. untuk menghitung luas lingkaran, maka nilai jari - jari yang dikuadratkan (r * r) di kalikan nilai pi (pi * r * r), dimana nilai pi bisa di approksimasikan sebagai 3.14
4. untuk menghitung keliling, maka nilai jari - jari dikali dengan 2 kali pi (2 * pi * r)
5. selesai

### flowchart

```mermaid

flowchart LR
    Start((mulai))
    Input[/r/]
    P1_1[luas = r * r * 3.14]
    P1_2[keliling = 2 * r * 3.14]
    Output1_1[/luas/]
    Output1_2[/keliling/]
    End(((selesai)))

    Start --> Input
    Input --> P1_1
    Input --> P1_2
    P1_1 --> Output1_1
    P1_2 --> Output1_2
    Output1_1 --> End
    Output1_2 --> End

```
