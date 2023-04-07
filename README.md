## #1 - Запуск софта.

Натисніть подвійним кліком по `____script3_startTool.cmd`
Або команда в консолі `python labelImg.py` в директорії з скриптом

<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/window.png?raw=true" alt="Sublime's custom image"/>
</p>
Вікно застосунку.

## #2 - Відкриття директорії зі зображеннями.

<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/opendir.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  Натиснути Open Dir та обрати директорію з зображеннями.
</p>

## #2 - Відкриття директорії зі лейблами (файлами результату).

<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/savedir.png?raw=true" alt="Sublime's custom image"/>
</p>

<p align="center">
  Натиснути Change Save Dir та обрати директорію для зберігання результату.
</p>




## Завдання: **розмітити прямокутниками техніку (ВСЮ) не пропускаючи, щільно-прилягаючими боксам(прямокутниками)**

Класи техніки що цікавлять:

- `military`----------(бронетехніка, військові вантажівки)
- `large vehicle`---(цивільні вантажівки, міктоавтобуси, с/г техніка)
- `small vehicle`---(легкові машини)
- `plane`--------------(літаки військові та цивільні)
- `helicopter`-------(гелікоптери військові та цивільні)


# Керування:

- `W` - Створити новий прямокутник. Після цього застискаєте і проводите мишку щоб намалювати прямокутник. 

<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/draw.png?raw=true" alt="Sublime's custom image"/>
</p>


- Обираєте клас зі списку що з'являється.
<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/select.png?raw=true" alt="Sublime's custom image"/>
</p>
-----------

"Хватаючись за центр" - змінити розташування
<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/resize.png?raw=true" alt="Sublime's custom image"/>
</p>
-----------
"Тримаючись за куточки":

- лівою кнопкою миші - змінити розмір
<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/resize2.png?raw=true" alt="Sublime's custom image"/>
</p>
- правою кнопкою миші - прокрутити
<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/fit.png?raw=true" alt="Sublime's custom image"/>
</p>

-----------

- `Сtrl+ Ctrl-`     - масштабування
- `Ctrl wheel`     -- масштабування

----------

- `A` - попереднє фото
- `D` - наступне фото
(або кнопки зі стрілочками)
<p align="center">
  <img src="https://github.com/ioretcio/labelImg_OBB_bad_one/blob/master/resources/md_jpegs/arrows.png?raw=true" alt="Sublime's custom image"/>
</p>

----------

- Затискання коліщатка миші + перетягування - перетягування картинки

- Затискання Alt  + перетягування лівою кнопкою миші - перетягування картинки

---------

- `Затискання Ctrl` - пересування прямокутника, ігноруючи кути (щоб точно перетягувати а не змінювати розмір)

---------

- `Ctrl d` - створити дублікат прямокутника (корисно у випадку багатьох однакових підряд)

---------

- Права кнопка миші по центру бокса - його опції

---------

- Кнопка `Save`, або комбінація `Ctrl+S` - зберегти зображення перед переходом до наступного, або перед виходом зі застосунку.

