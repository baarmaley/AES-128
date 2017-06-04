# AES-128
Rijndael algorithm
<p>Реализация AES-128 в режиме OFB</p>
<p>Работа выполнена в рамках дисциплины «Защита информации» осенью 2016 года</p>
<p>При выполнении старался пользоваться первоисточниками, корректность работы алгоритма проверял примерами из 
<a href="http://csrc.nist.gov/publications/fips/fips197/fips-197.pdf">FIPS197</a></p>
<p>В программе реализован следующий функционал:</p>
<ul>
<li>Чтение открытого текста или шифртекста из файла</li>
<li>Сохранение открытого текста или шифртекста в файл</li>
<li>Отображение открытого текста и шифртекста в hex (для проведения экспериментальной части курсового проекта)</li>
<li>Режим OFB с различным размером блока</li>
</ul>
<p>В экспериментальной части курсового проекта проводились испытания на проверку устойчивости системы к различного рода помехам (изменение/добавление/удаления байт, ).</p>
<p>Рассмотренны достоинства и недостатки поточных шифров (OFB)</p>
<p>Скриншот программы:</p>
<img alt="screenshot" src="https://cloud.githubusercontent.com/assets/19309892/20848136/d3bd44de-b8e1-11e6-9dec-a11b883e1ce5.png">