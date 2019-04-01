# cRPi-BOX
Raspberry Pi3 pentester box.
Проект на стадії розробки.
<h3>АНОТАЦІЯ</h3>

<p>Постановка задачі. Досить часто пентестеру необхідно мати пристрій, який був би малопомітним і функціональним водночас. 
Мeтoю poбoти є створення такого пристрою на основі Raspberry Pi3B, який мав би два режими роботи: black-box і white-box.</p>

<p>В режимі black-box пристрій буде автоматично створювати точку доступу на вбудованій мережевій карті вай-фай, а зовнішня карта з антеною буде використовуватись для пентесту вай-фай мереж. У цьому режимі керування пристроєм відбувається через SSH.<p/>
<p>У режимі white-box пристрій буде підєднуватися до цільової вай-фай мережі і проводити внутрішній аудит локальної мережі. У цьому режимі керування пристроєм відбувається через SSH або Telegram-бота.</p>
<p align="center"><img src="https://github.com/cRPitonite/cRPi-BOX/blob/master/img/cRPi-BOX%20(square).png" height="500px" width="500px"></p>
