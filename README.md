# Text-Recognition-Dataset

<b>Английский</b>


<ul>
  <li><a href="https://drive.google.com/file/d/1o2dk_HZgcF1ecdb4X8lux-4W8i7lh_ao/view?usp=sharing">Part 1</a> - 500 000 картинок, без аугментации</li>
  <li><a href="https://drive.google.com/file/d/1pMYW1gfBCmmFRQSsNTDn-zPWsGssSxyW/view?usp=sharing">Part 2</a> - 500 000 картинок, без аугментации</li>
  <li><a href="https://drive.google.com/file/d/1F2KgadB55IrdxoK5e9e06Z9TreNCsvne/view?usp=sharing">Part 3</a> - 500 000 картинок, без аугментации</li> 
  <li><a href="https://drive.google.com/file/d/1A4onJ_7d6zm8YX4FhAR03ookyLkgY_Pt/view?usp=sharing">Part 4</a> - 500 000 картинок, аугментация: 50 % картинок с тенью от текста </li>  
  В основном символы <b>abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ</b>
  , скоро добавлю еще 2 миллиона картинок в перемешку с символами 1234567890,./:;'"[]{}-_=+!?@#$€¥£₤₽¢¤«±%&*()~<>^|\№
</ul>

<b>Русский</b>
<ul>
  <li>пока нет</li>
</ul>

<b>Формат данных</b>

В каждой папке находится файл train.txt в котором для каждого изображения содержатся индексы символов

![000007](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/d9b6b0fa-f719-4668-820d-73f90bb10c4c)

Числа разделенные пробелами соответствуют символам из этого списка 
<b>abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890,./:;'"[]{}-_=+!?@#$€¥£₤₽¢¤«±%&*()~<>^|\№</b>

<b>Пример:</b> 34 15 2 19 105 105 105 105 105 105 105 105 105 105 105 = H o b s ![5](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/ffc7756d-24b8-42ac-90af-8c713e44c4f7)

Число 105 это пробел, находится в конце и не используеться, индекс <b>1</b> соответствует символу <b>a</b>, максимальная длина 15 символов

![000004](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/7e12f082-e577-4673-88ea-6fd81282dc7b)

![000000](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/2bd27f81-e935-4d76-aa7b-287e0773981e)

![000005](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/e287874b-d296-4baa-b85b-a02d995b851d)


<b>P.S.</b> Если вам что то не понятно мне поуху
