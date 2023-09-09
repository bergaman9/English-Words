# English Words

## Hakkında

Bu repo, 2020-2021 yıllarında oyun oynarken karşılaştığım İngilizce kelimeleri içermektedir. Kelimeler `.json` formatında saklanmaktadır ve ana dilim Türkçe'dir.

## Amaç

Bu kelimeleri öğrenmek ve hatırlamak benim için önemliydi, bu yüzden MongoDB'de saklıyorum. Bu repo'yu oluşturmanın ana sebebi, bu kelimeleri kendi projelerimde kullanabilmek. Ancak, başkalarının da faydalanabileceğini düşündüğüm için paylaşıyorum.

## Kullanım

Kelimeler `.json` formatında olduğu için, herhangi bir programlama dilinde kolayca okunabilir ve işlenebilir. Örneğin, Python'da `json` kütüphanesi ile:

```python
import json

with open('words.json', 'r') as f:
    words = json.load(f)
```
