# 以Astroquery套件擷取線上天文觀測資料

蘇羿豪@PyCon Taiwan 2018

---

[:alarm_clock:](https://medium.com/@eddiewen/%E6%88%91%E5%AF%AB%E4%BA%86%E4%B8%80%E5%80%8B%E6%AC%B8%E9%A0%97-%E9%98%BF%E6%9B%BF%E5%80%92%E6%95%B8%E4%B8%AD-b42ee59dace1)阿替倒數中: 0.3%的進展

* 主線任務： 與資訊領域人員聯盟，在台灣天文教育與學術界以遊戲化的方式推廣Python、開源精神及黑客文化。 [完成度：0.7%]
* 支線任務： 取得具有初級緊急救護/救火技能的消防替代役男的退伍令。 [完成度：26.6%]
* ~~主線任務： 成為中央大學天文研究所畢業的博士。~~[完成度：100%]

---

[:rainbow:](https://imagine.gsfc.nasa.gov/science/objects/milkyway2.html) 挑戰1: 拼接多彩銀河

[:stars:](https://imagine.gsfc.nasa.gov/Images/objects/milkyway_xray_rosat_full.gif) [:stars:](https://imagine.gsfc.nasa.gov/Images/objects/milkyway_optical_full.gif) [:stars:](https://imagine.gsfc.nasa.gov/Images/objects/milkyway_radio_408MHz_full.gif) [:stars:](https://imagine.gsfc.nasa.gov/Images/objects/milkyway_infrared_full.gif)

[:telescope:](https://irsa.ipac.caltech.edu/) [:telescope:](https://gea.esac.esa.int/archive/) [:telescope:](http://alma.asiaa.sinica.edu.tw/) [:telescope:](https://heasarc.gsfc.nasa.gov/cgi-bin/W3Browse/w3browse.pl)

---

:::info
:key: :snake: >>>
```Python
print("解鎖成就: 認識天文研究。")
```
:::

---

[:mag:](https://hackmd.io/p) 找資料, [Astroquery](https://astroquery.readthedocs.io)

```Python
from astroquery.service import Service

object_result = Service.query_object(objectname)
region_result = Service.query_region(coordinate, radius=)
```

---

[:unlock:](http://adsabs.harvard.edu/abs/2000A%26AS..143...23O) [VizieR](http://vizier.u-strasbg.fr/) 
[:lock:](https://almascience.nrao.edu/alma-data/archive) [:lock:](http://www.sdss.org/) [:lock:](https://exoplanetarchive.ipac.caltech.edu/) [:lock:](http://www.ukidss.org/index.html) 
[:lock:](https://ned.ipac.caltech.edu/) [:lock:](https://archive.stsci.edu/) [:lock:](https://irsa.ipac.caltech.edu) [:lock:](http://exoplanets.org/) 
[:lock:](https://fermi.gsfc.nasa.gov/ssc/data/) [:lock:](https://astrocats.space/) [:lock:](http://sky.esa.int/) [:lock:](https://gea.esac.esa.int/archive/)
[:lock:](https://heasarc.gsfc.nasa.gov/cgi-bin/W3Browse/w3browse.pl) [:lock:](http://www.gama-survey.org/dr2/query/) [:lock:](https://minorplanetcenter.net/web_service/) [:lock:](http://cdsxmatch.u-strasbg.fr/xmatch/doc/)

---

[:globe_with_meridians:](https://zh.wikipedia.org/wiki/%E5%A4%A9%E7%90%83%E5%9D%90%E6%A0%87%E7%B3%BB%E7%BB%9F#%E8%B5%A4%E9%81%93%E5%9D%90%E6%A8%99%E7%B3%BB%E7%B5%B1) 挑戰2: [梅西爾搜尋手](https://zh.wikipedia.org/wiki/%E6%A2%85%E8%A5%BF%E8%80%B6%E5%A4%A9%E4%BD%93%E5%88%97%E8%A1%A8)

[:notebook:](https://github.com/YihaoSu/astroquery-notes)

---

:::info
:key: :snake: >>>
```Python
print("解鎖成就: 開啟Astroquery技能樹的VizieR分支。")
```
:::


---

[:lock:](http://vizier.u-strasbg.fr/viz-bin/VizieR?-source=J/A+A/558/A12&-to=3) 再推進??% 

* 用[astroquery.vizier](https://astroquery.readthedocs.io/en/latest/vizier/vizier.html)搜尋其他梅西爾星體

* 找出隱藏在簡報中的彩蛋

* 解鎖其他天文資料庫，並貢獻[Astroquery套件的相關筆記](https://github.com/YihaoSu/astroquery-notes)

* 與[Astrohackers in Taiwan](https://github.com/Astrohackers-TW)合作[《Flip Astrocards Over》](https://github.com/Astrohackers-TW/flip-astrocards-over)專案

---

:::info
:information_source: :snake: >>>
```Python
print("Hello, 我是Astroquery旅遊服務中心的iPython， 旅途中有任何問題， 歡迎丟給我吃。")
```
:::