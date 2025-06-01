# Оптимизация изображений

## Форматы изображений и их параметры

### Оригинальные изображения
| Название | Формат | Размер | Вес |
|----------|--------|--------|------|
| photo_original | jpg | 2560x1674 | 368кб |
| screenshot_original |jpg | 1261x847 | 111кб |
| graphic_original | jpg | 612x465 | 57 кб |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### Lossless WebP
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | WebP | 1920x1080 | 1.51 MB | +302% |
| screenshot_original | WebP | 1366x768 |421 kB  | +273% |
| graphic_original | WebP | 3840x2400 | 214 kB | +271% |
![photo_original](<img/photo_original.webp>)
![screenshot_original](<img//screenshot_original.webp>)
![graphic_original](<img/graphic_original.webp>)
### PNG
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | PNG | 1920x1080 | 3.26 MB | +765% |
| screenshot_original | PNG | 1366x768 | 906 kB | +703% |
| graphic_original | PNG | 3840x2400 | 363 kB | +529% |
![photo_original](<img/photo_original.png>)
![screenshot_original](<img//screenshot_original.png>)
![graphic_original](<img/graphic_original.png>)
### Lossy

### MozJPEG 100%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 734 kB | +95% |
| screenshot_original | jpg | 1366x768 | 274 kB | +142% |
| graphic_original | jpg | 3840x2400 | 152 kB | +163% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### MozJPEG 75%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 92.8 kB | -75% |
| screenshot_original | jpg | 1366x768 | 53.0 kB | -53% |
| graphic_original | jpg | 3840x2400 | 42.7 kB | -26% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### MozJPEG 50%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 60.6 kB | -89% |
| screenshot_original | jpg | 1366x768 |34.6 kB | -69% |
| graphic_original | jpg | 3840x2400 | 27.9 kB | -52% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### AVIF 100%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 524 kB | +39% |
| screenshot_original | jpg | 1366x768 | 122 kB | +8% |
| graphic_original | jpg | 3840x2400 | 98.7 kB | +71% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)
### AVIF 50%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 23.0 kB | -94% |
| screenshot_original | jpg | 1366x768 | 12.3 kB | -97% |
| graphic_original | jpg | 3840x2400 | 24.5 kB | -58% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### AVIF 75%
| Название | Формат | Размер | Вес | Изменение |
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 52.1 kB | -86% |
| screenshot_original | jpg | 1366x768 | 24.9 kB | -78% |
| graphic_original | jpg | 3840x2400 | 42.5 kB | -26% |
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)

### AVIF min
| Название | Формат | Размер | Вес | Изменение | Якicть
|----------|--------|--------|------|-----------|
| photo_original | jpg | 1920x1080 | 12.2 kB | -97% |30%
| screenshot_original | jpg | 1366x768 | 10.8 kB| -90% |45%
| graphic_original | jpg | 3840x2400 | 10.4 kB| -82% | 20%
![photo_original](<img/photo_original.jpg>)
![screenshot_original](<img//screenshot_original.jpg>)
![graphic_original](<img/graphic_original.jpg>)
### Оптимизация размера по целевому использованию
| Название | Формат | Оригинальный размер | Веб (1200px) | Изменение | Мобайл (600px) | Изменение | Retina 2x (2400px) | Изменение |
|----------|--------|-------------------|-------------|-----------|---------------|-----------|-----------------|-----------|
| photo_original | jpg | 167.2кб | 392кб | +129% | 126кб | -26% | 1.13мб | +560% |
| screenshot_original | png | 688.2кб | 1.83мб | +160% | 476кб | -32% | 6.31мб | +795% |
| graphic_original | jpg | 1.14мб | 872кб | -27% | 249кб | -79% | 2.82мб | +135% |

## Выводы
- Оптимизация значительно уменьшила размер файлов без заметных потерь качества.
- WebP (lossless) наиболее эффективен для скриншотов и графики.
- JPEG (75%) – лучший вариант для фотографий.
- Для мобильных версий лучше использовать WebP во избежание размытия.
- Выбор подходящего формата позволяет существенно снизить вес файлов без потерь качества.
