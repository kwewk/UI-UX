# Оптимізація зображень за допомогою Squoosh
## Початкові зображення
Моі початкові зображення мають формати **jpeg**, **png** та **jpg**.

| Назва файлу | Формат | Розмір (px) | Вага (kb) |
|-------------|--------|------------|----------|
| photo.jpeg | JPEG | 1287x616 | 240 |
| screenshot.png | PNG | 1072x552 | 600 |
| graphic.jpg | JPG | 626x417 | 129 |

**Фото:**  
![Оригінал](images/photo/photo.jpeg)  

**Скриншот:**  
![Скриншот](images/screenshot/screenshot.png)  

**Графічне зображення з текстом:**  
![Графічне зображення з текстом](images/GI/graphic.jpg)  

## Стиснення без втрати якості (lossless)
**Фото у форматі PNG (lossless)**
![Фото](images/photo/photo_lossless.png)

**Фото у форматі WebP (lossless)**
<img src="images/photo/photo_lossless.webp" alt="Фото у форматі WebP (lossless)" width="1287" height="616">

**Скриншот у форматі PNG (lossless)**
![Скриншот](images/screenshot/screenshot_lossless.png)

**Скриншот у форматі WebP (lossless)**
<img src="images/screenshot/screenshot_lossless.webp" alt="Скриншот у форматі WebP (lossless)" width="1072" height="552">

**Графічне зображення з текстом у форматі PNG (lossless)**
![Графічне зображення з текстом](images/GI/graphic_lossless.png)

**Графічне зображення з текстом у форматі WebP (lossless)**
<img src="images/GI/graphic_lossless.webp" alt="Графічне зображення з текстом у форматі WebP (lossless)" width="626" height="417">

### Порівняння розмірів файлів після lossless стиснення
| Назва файлу | Розмір | Вага оригіналу | Вага після стиснення у PNG | Вага після стиснення у WebP |
|-------------|--------|----------------|----------------------|---------------------|
| photo.jpeg  | 1287x616 | 240 кб | 1,54 мб | 907 кб |
| screenshot.png | 1072x552 | 600 кб | 626 кб | 333 кб |
| graphic.jpg | 626x417 | 129 кб | 227 кб | 146 кб |

## Стиснення з втратою якості (lossy)
**Фото в форматі MozJPEG (стиснення з 100% рівнем якості)**
![Фото](images/photo/photoMozJPEG100.jpg)

**Фото в форматі MozJPEG (стиснення з 75% рівнем якості)**
![Фото](images/photo/photoMozJPEG75.jpg)

**Фото в форматі MozJPEG (стиснення з 50% рівнем якості)**
![Фото](images/photo/photoMozJPEG50.jpg)

**Фото в форматі WEbP (стиснення з 100% рівнем якості)**
<img src="images/photo/photoWebP100.webp" alt="Фото у форматі WebP (стиснення з 100% рівнем якості)" width="1287" height="616">

**Фото в форматі WEbP (стиснення з 75% рівнем якості)**
<img src="images/photo/photoWebP75.webp" alt="Фото у форматі WebP (стиснення з 75% рівнем якості)" width="1287" height="616">

**Фото в форматі WEbP (стиснення з 50% рівнем якості)**
<img src="images/photo/photoWebP50.webp" alt="Фото у форматі WebP (стиснення з 50% рівнем якості)" width="1287" height="616">

**Фото в форматі AVIF (стиснення з 100% рівнем якості)**
<img src="images/photo/photo100.avif" alt="Фото у форматі AVIF (стиснення з 100% рівнем якості)" width="1287" height="616">

**Фото в форматі AVIF (стиснення з 75% рівнем якості)**
<img src="images/photo/photo75.avif" alt="Фото у форматі AVIF (стиснення з 75% рівнем якості)" width="1287" height="616">

**Фото в форматі AVIF (стиснення з 50% рівнем якості)**
<img src="images/photo/photo50.avif" alt="Фото у форматі AVIF (стиснення з 50% рівнем якості)" width="1287" height="616">
