## ALV

ABAP'ta  ALV, listeleri kullanıcı dostu ve etkileşimli bir şekilde görüntülemek için SAP tarafından sağlanan bir dizi standart işlevdir. Geliştiricilerin sofistike raporlar oluşturmasına ve tablolardaki verileri sıralama, filtreleme ve alt toplam alma gibi özelliklerle görüntülemesine olanak tanır.

## İçindekiler

1. [Salv](/1_Salv.abap)
2. [Reuse ALV Manuel Field Catalog And Layout](/2_REUSE_ALV_manuel_fcat_layout.abap)
3. [Reuse ALV Field Catalog Manual V2](/3_Reuse_ALV_Manuel_Fcat_V2.abap)
4. [Reuse ALV Field Catalog Merge Function](/4_REUSE_ALV_Fieldcat_Merge.abap)
5. [Reuse ALV CALLBACK-IT EVENTS](/5_REUSE_Alv_Callback_Events.abap)
6. [Reuse ALV TOP_OF_PAGE-END_OF_LIST](/6_REUSE_ALV_TOP_OF_PAGE-END_OF_LIST.abap)
7. [Reuse ALV pf status set](/7_REUSE_ALV_PF_STATUS.abap)
8. [Reuse ALV User Command](/8_REUSE_ALV_USER_COMMAND.abap)
9. [Reuse ALV Line Cell Color](/9_ALV_LINE_CELL_COLOR.abap)
10. [Reuse ALV Excluding Sort Filter](/A10_ALV_EXCLUDE_FILTER_SORT.abap)
### EXCLUDING Nedir?
Aşağıdaki bazı butonları gizlemeye yarayan yapıya denir.
![image](https://github.com/xryal/ALV/assets/81656700/7a29539b-bd31-41a2-8ee6-10b016e07b1f)

### SORT Nedir?
Kolon bazında Alvyi sıralar.

### FILTER Nedir?
ALV'yi Belirli Koşullara göre verileri filtreler.

11. [Reuse ALV SAVE VARIANT](/A11_REUSE_ALV_VARIANT.abap)
### SAVE Nedir?

ALV üzerinde yaptığımız düzenleme ve değişiklikleri kaydeden bir yapıdır kullanabilmemizi sağlayan bir yapıdır
açılınca 3 adet buton gelir ve bu butonlara alevlerin görünümlerini değiştirip varyantlar kaydedebiliriz.

I_SAVE  = 'X' verilirse her kullanıcı bu kayıt varyantlarından etkilenir.                                                      
I_SAVE  = 'U' verilirse  user bazlı kayıt gerççekleştirir.                                                            
I_SAVE  = 'A' verilirse kullanıcı özgü varyant kayıt da edilebilir
her kullanıcı için de varyant kayıt edilebilir bunun seçimini kullanıcıya bırakır.

ön ayar çalışıtırılır çalıştırılmaz bu varyant çalışsın anlamına gelmektedir
