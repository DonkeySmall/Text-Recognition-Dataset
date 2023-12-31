# Text Recognition Dataset

<b>Английский</b>


<ul>
  <li><a href="https://drive.google.com/file/d/1o2dk_HZgcF1ecdb4X8lux-4W8i7lh_ao/view?usp=sharing">Part 1</a>,
  <a href="https://drive.google.com/file/d/1pMYW1gfBCmmFRQSsNTDn-zPWsGssSxyW/view?usp=sharing">Part 2</a>,
  <a href="https://drive.google.com/file/d/1F2KgadB55IrdxoK5e9e06Z9TreNCsvne/view?usp=sharing">Part 3</a>, 
  <a href="https://drive.google.com/file/d/1A4onJ_7d6zm8YX4FhAR03ookyLkgY_Pt/view?usp=sharing">Part 4</a> - 2 000 000 картинок</li>  
  В основном символы <b>abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ</b>
</ul> 
<ul>
  <img src="https://user-images.githubusercontent.com/66531939/279373512-49d7ed5e-c04e-45bb-8797-168b424b1256.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279381338-8a4ff2cc-9fb2-4719-9ece-a5e622a5065f.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279381222-a8c25a98-560f-48ec-9fa0-be94d415686d.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279373629-5cf3251e-b18d-428a-8af0-7001f8917d0b.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279381144-6d767f80-ea04-4a81-8d65-348d2a8173a2.jpg" height="30">
</ul>
<ul>  
  <li><a href="https://drive.google.com/file/d/1fU99e_7TCrficzJ0NePaw2nuk9b6O437/view?usp=sharing">Part 5</a> - 500 000 картинок</li>  
  Символы <b>0123456789</b> 
</ul>
<ul>
  <img src="https://user-images.githubusercontent.com/66531939/279603333-319c849b-d88a-4985-889b-af02156cad81.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279603438-e4700b31-c9e9-4e6f-9595-7e4f8d3529b6.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279603509-5e92dc5e-1cd4-48af-bce3-415dcd787393.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279603248-bb3daeff-7634-4e3b-8424-8e9ad3f273d7.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279603289-cd9df25b-98f3-45b5-9246-3ebd3e8bae67.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279604100-df99cd90-7c99-42bc-be8e-3aa7c71b85a8.jpg" height="30">
</ul>
<ul>  
  <li><a href="https://drive.google.com/file/d/1Sy8K9fe8efUpdTPmBshEDVeImFjUh2QJ/view?usp=sharing">Part 6</a> - 500 000 картинок</li>  
  Символы <b>0123456789\,.:/-</b> 
</ul>
<ul>
  <img src="https://user-images.githubusercontent.com/66531939/279661555-ae6c4225-d960-4b0e-8931-55561b6aab35.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279661680-5c536ff4-9bc4-4c23-a528-6192d3ef5e90.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279661834-7fb61c04-8526-40c1-90e5-09dcc998d911.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279603509-5e92dc5e-1cd4-48af-bce3-415dcd787393.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279661498-f31eb144-5589-4165-9ac0-c711a820c98c.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279661531-b38402d0-ff0f-47ff-a2a2-5f5e30a8b82c.jpg" height="30">
  <img src="https://user-images.githubusercontent.com/66531939/279662788-656320c7-9bc1-40c1-9cc0-8ab3cfad0654.jpg" height="30">
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

![497565](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/49d7ed5e-c04e-45bb-8797-168b424b1256)
![498972](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/5cf3251e-b18d-428a-8af0-7001f8917d0b)
![490579](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/ae490e61-3d26-4de5-88b3-66bf74175fbc)
![494546](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/3fa0a3b9-d55d-4962-8e33-7fd2e32b7db0)
![492680](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/3887bc94-afc1-422c-96f6-72bd7d2ca593)
![495906](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/e808a871-4588-466a-b4ae-28dabff20a86)
![491508](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/0203aabe-69b6-461e-b5c2-deb6971772f9)
![494387](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/5bb69644-122d-480e-8145-765863906df9)
![496431](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/1ca8f159-1548-4c6d-bcf5-6e21a79adc24)
![490692](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/83e78094-1b2f-4590-88b6-3ae5bee6edcf)
![492759](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/f3a4aa97-70a8-4297-893a-b504a2bb6df0)
![491504](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/6d767f80-ea04-4a81-8d65-348d2a8173a2)
![491082](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/a8c25a98-560f-48ec-9fa0-be94d415686d)
![497052](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/2f0717fd-208d-495b-9e5b-b4418d2b1cd2)
![498748](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/8a4ff2cc-9fb2-4719-9ece-a5e622a5065f)
![492995](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/1bd4238f-dfc6-4868-9376-f3708b7385e4)
![495104](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/7301e3c1-764e-46d9-9ece-233601f5f2c1)
![495387](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/998fa06b-cdda-4f6b-8500-8e3247d30bbd)
![494408](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/c422dd7f-19e5-4beb-bc7f-c0d04215db56)
![493625](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/73d729b0-2a1b-4917-8950-4bcdef18f4b4)
![490067](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/bb3daeff-7634-4e3b-8424-8e9ad3f273d7)
![490115](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/cd9df25b-98f3-45b5-9246-3ebd3e8bae67)
![490392](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/319c849b-d88a-4985-889b-af02156cad81)
![490473](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/f8dd7c04-2212-425c-9d62-3fd36f3326e0)
![490516](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/e4700b31-c9e9-4e6f-9595-7e4f8d3529b6)
![490673](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/9d3e608a-d629-485f-9c1b-d398d2a8396f)
![490737](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/5e92dc5e-1cd4-48af-bce3-415dcd787393)
![490942](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/e555bd69-7b23-4394-a8a1-ad774ea4bb51)
![491041](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/df99cd90-7c99-42bc-be8e-3aa7c71b85a8)
![490204](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/f31eb144-5589-4165-9ac0-c711a820c98c)
![490232](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/b38402d0-ff0f-47ff-a2a2-5f5e30a8b82c)
![490346](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/ae6c4225-d960-4b0e-8931-55561b6aab35)
![490392](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/a62df146-e703-4ba8-bb05-655f7948bc7e)
![490546](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/8b973c80-21e0-47fd-bd8c-6b6f172f4873)
![490699](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/5c536ff4-9bc4-4c23-a528-6192d3ef5e90)
![490924](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/22e101ac-a530-4447-8a11-ca69d196c2b7)
![491066](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/7fb61c04-8526-40c1-90e5-09dcc998d911)
![491065](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/d2237cf6-df78-4895-b1c9-f0b80f4a7f14)
![491121](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/30617ebd-6b0b-4c99-a8ba-245c1175dae9)
![491115](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/49220277-59f6-4cb1-aedf-d5a11afdd987)
![491363](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/5f37b3fe-eeee-48ac-83af-612160938d0e)
![492190](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/19511c16-098a-4032-84ba-8849b9cc90b0)
![492701](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/656320c7-9bc1-40c1-9cc0-8ab3cfad0654)


![000004](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/7e12f082-e577-4673-88ea-6fd81282dc7b)

![000008](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/2d6f3695-6ae7-4123-8f74-b0272f108488)

![000000](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/2bd27f81-e935-4d76-aa7b-287e0773981e)

![000005](https://github.com/DonkeySmall/Text-Recognition-Dataset/assets/66531939/e287874b-d296-4baa-b85b-a02d995b851d)


<b>P.S.</b> Если вам что то не понятно мне поуху
