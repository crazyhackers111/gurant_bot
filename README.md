<h1 align="center"><aГарант-Бот.</a> 
Гарантированные сделки в телеграмме.</h1>
<h3 align="center">Получай комиссию со сделок других пользователей, ничего не вкладывая</h3>
  
    
<h6 align="center">* Оформлено и опубликовано для прикрепления к резюме в качестве примера работы</h6>

Главной проблемой продаж как в телеграмме, так и в любом другом уголке интренета, является доверие. Мало кто станет отправлять свои средства человеку, пообещавшему ему тот или иной товар, аналагично этому и сам продавец не пойдёт на уступок, отправляя товар покупателю первым. 
Исходя из этой ситуации, на форумах стали появляться так называемые гаранты - люди, являющиеся посредниками между покупателем и продавцом, которых интересовала лишь комиссия за проведённую сделку и их личная репутация для проведения новых. Но нанимать человека каждый раз, когда хочешь что-либо купить или продать как неудобно, так и не выгодно. 
Гаранты могут брать большие проценты, найти хорошего посредника не так уж и просто, и их график не всегда совпадает с нашей нуждой совершить сделку быстро. 
На смену им приходит моё решение - <a href="https://github.com/outp1/NewGarantBot" target="_blank">Гарант-Бот.</a>

<img src="https://github.com/outp1/NewGarantBot/blob/master/Gw1q6.gif" />

<b>Краткий принцип работы:</b>
1. Клиент договаривается с продавцом о сделке через бота, оба переходят в него, и покупатель нажимает на соответсвующую кнопку "🔍 Поиск продавца"
2. Вводится телеграмм никнейм, после чего выводится профиль пользователя, где можно посмотреть рейтинг и отзывы продавца, оставленные прошлыми покупателями по кнопке '💫 Отзывы'

![image](https://user-images.githubusercontent.com/81954928/167292893-fdd13356-93b0-4e59-8bd1-c56b867ed6d6.png)

3. Клиент нажимает на кнопку начать сделку, вводит сумму, которая впоследствии спишется с баланса покупателя и описывает условия сделки (техническое задание, описание товара и т.д).
4. Продавцу приходит уведомление о сделке, с которым он ознакамливается и принимает его.
5. После выполнения всех условий, если покупатель доволен, он открывает сохраненную сделку через бота и нажимает кнопку '💸 Отправить средства', после чего деньги приходят в личный кабинет продавцу. Но если покупатель считает что условия сделки невыполнены, то при нажатии на кнопку 'Открыть спор', к сделке присоединяется модератор, который общаясь с обоими сторонами через встроенный функционал бота решает, были ли выполенны условия, после чего средства либо возвращаются покупателю, либо отправляются продавцу. 
Продавец также может открыть спор, если считает, что условия были выполненны, но клиент не отправляет деньги.

![image](https://user-images.githubusercontent.com/81954928/167292815-1d8b4d27-feff-4a70-a641-aa26b3bf2ffe.png)

![image](https://user-images.githubusercontent.com/81954928/167292774-adc3d277-e72e-47db-ab9f-3352ece815d2.png)

Функционал помимо:
<ul>
 <li>Панель администратора с возможностью рассылки всем пользователям, создание реферальных ссылок для рекламодателей, смены реквизитов для пополнения средств пользователями, статистика бота, управления пользователями. </li>
 <li>Фильтрация сообщений в чате услуг, подключенных к боту</li>
 <li>Логирование ошибок в личные сообщения техническому администратору</li>
<li>Загрузка файла логов с сервера через панель администратора</li>
 <li>Пополнение средств через API киви, а также криптой через парсинг чеков от бота @BTC_CHANGE_BOT</li>
</ul>

Не до конца реализованные фичи:
<ul>
<li>Автопостинг сообщений в чат услуг</li>
<li>Реферальная программа пользователей</li>
<li>Некоторые платежные API</li>
</ul>
