# Пример использования библиотеки pyweb-progressbar

```
import pyweb_progressbar, time

pb = pyweb_progressbar.progressBar(base_amount=120, progressBarSize=50, lang='ru')

for i in range(1, 201):
  pb.updateProgressBar(i)
  time.sleep(0.5)

pb.end()
```
