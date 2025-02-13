---
description: >-
  С сентября 2019 г. (момента сохранения блокчейна силами сообщества).
  Подписывайтесь на новости https://golos.id/@goloschain
---

# Обновления на Голосе

## Сентябрь 2021

26 хардфорк \(обновление протокола блокчейна\)

### Конвертация токенов GOLOS в GBG

Добавлена конвертация в стейблкоин \(Gold backed by GOLOS\), привязанный к стоимости 1 мг золота в токенах GOLOS. Кроме того изменен срок понижения Силы Голоса аккаунтов с 8 до 4 недель и другие изменения. [Подробнее &gt;](https://golos.id/ru--golos/@lex/informaciya-o-nedavnikh-izmeneniyakh-26-khardforka-obnovleniya-koda-blokcheina)

### Сервис Golos Auth

Реализован отдельный сервис регистрации, OAuth и серверной авторизации, что позволит иметь более безопасную и функциональную основу для приложений и веб-клиентов к блокчейну. Сервис можно использовать как через API из своего интерфейса, так и запустить сконфигурируя его полностью под себя без затрат на проработку регистрации. [Подробнее &gt;](https://golos.id/ru--golos/@lex/servis-golos-auth-nachalo-biblioteki-golos-libs-s-webassembly-event-plagin)

### Влияние на репутацию аккаунтов из профиля

Репутация приобретает большее значение, менять её возможно и из профиля, без привязки к постам/комментариям в рамках 7 дневного окна. Позволит быстрее реагировать сообществу на нечто полезное для проекта, и наоборот \(по сути становясь отдельной "мини-игрой", с затратами батарейки аккаунта и вне общего пула наград\). [Подробнее &gt;](https://golos.id/ru--golos/@lex/informaciya-o-nedavnikh-izmeneniyakh-26-khardforka-obnovleniya-koda-blokcheina)

## Июль 2021

### Сервис уведомлений Golos Notify

Доработан сервис отображения активности, ускорения работы мессенджера, всплывающих уведомлений по наиболее актуальным операциям и действиях пользователей. [Подробнее &gt;](https://golos.id/ru--golos/@lex/obnovlenie-servisa-golos-notify-js-biblioteki-i-prochie-pravki)

### Сервис прокси/кеширования фото

Реализован сервис кеширования загружаемых фото, с адаптацией под веб-клиенты \(формат webp, фото стали более чем вдвое легче\). Это позволило снять зависимость от внешних сервисов, оптимизацию изображений. [Подробнее &gt;](https://golos.id/ru--golos/@lex/keshirovanie-foto-i-drugie-obnovleniya)

### Смешанная система вознаграждений

Наряду с [персональными пулами вознаграждений](update.md#sistema-voznagrazhdenii-donaty) пользователи путём голосования за посты/комментарии распределяют и общий авторский пул. Добавлены ленты отображения всех постов/комментариев в блокчейне \(без фильтров и скрытия по отрицательной репутации\) с сортировкой по размеру ожидаемой выплаты. [Подробнее &gt;](https://golos.id/ru--golos/@lex/vozvrashenie-obshego-pula-i-novye-pravki)

## Апрель 2021

### Добавлен мессенджер \(приватные сообщения\)

Возможность обмена личными сообщениями между пользователями блокчейна Голос в клиентах блогов и форумов. В планах десктоп/смартфон версии мессенджера. [Подробнее &gt;](https://golos.id/ru--golos/@lex/obmen-lichnymi-soobsheniyami-i-nachalo-dlya-golos-messenger)

## Февраль 2021

### Внутренний поиск по блокчейну с Elasticsearch

Весь контент из блокчейна сохраняется в индексе Elasticsearch, что позволяет быстро найти любой пост или комментарий из имеющихся в базе ~10 млн. записей. Поиск по фразе, автору, тегам, периоду... [Подробнее &gt;](https://golos.id/ru--golos/@lex/vnutrennii-poisk-na-golose-naidyotsya-vsyo)

### Возможность регистрации через соцсети

На странице регистрации веб-клиентов, помимо Gmail-почты и инвайта, добавлена возможность авторизации с помощью аккаунта ВКонтакте, Facebook, Яндекс и Mail.ru. [Подробнее &gt;](https://golos.id/ru--golos/@lex/obnovleniya-v-blogakh-i-forumakh)

## Декабрь 2020

25 хардфорк \(обновление протокола блокчейна\)

### Добавление GOLOS в сервисе [C**oins.Black**](https://coins.black/)

Сервис обмена криптовалют, позволяющий купить токены, используя сотню вариантов оплаты при минимальной комиссии и отсутствии верификации личности. [Подробнее &gt;](https://golos.id/ru--golos/@on0tole/pryamaya-pokupka-tokenov-golos-za-rubli-i-ne-tolko)

### Форумный веб-клиент на блокчейне

Этот формат может позволить привлечь иную аудиторию, проекты заинтересованные в нецензурируемости контента, расширить охват, что в целом пойдёт на пользу всему блокчейну. [Подробнее &gt;](https://golos.id/ru--golos/@lex/zapusk-foruma-golostalk-com)

## Октябрь 2020

24 хардфорк \(обновление протокола блокчейна\)

### Возможность создания собственных токенов

Добавлен функционал эмитирования активов пользователями \(User Issued Assets - UIA\). Это позволит создавать на блокчейне свои собственные токены, торговать ими на внутренней бирже, использовать их в качестве вознаграждений/донатов, интеграции в сервисах, ботах, играх, для запуска бирж и шлюзов \(открытия торговли с популярными криптовалютами\). [Подробнее &gt;](https://golos.id/ru--golos/@allforyou/sozdaem-i-ispolzuem-uia-na-golose)

### Сжигание токенов аккаунта bittrex

В целях снижения инфляции и долга GBG делегатами блокчейна было принято решение направить токены аккаунта `bittrex` на `null` \(произведя их сжигание из экономики, выведение из оборота\).

**Основные причины**: невозможность около года вывести токены с биржи, блокировка пользователей с Украины и Белоруссии, отрицательные результаты переговоров на протяжении многих месяцев по вопросу включения кошелька, аудита и сжигания, листинга и пр.

### Обновление базы знаний [wiki.golos.id](https://wiki.golos.id/)

Актуализация информации во всех разделах базы знаний о блокчейне Голос для пользователей, разработчиков, делегатов.

## Май 2020

23 хардфорк \(обновление протокола блокчейна\)

### Система вознаграждений \(донаты\)

Так как система вознаграждений с борьбой за распределение общего пула показала себя малоэффективной, было принято решение о внедрении персональных пулов вознаграждений.  
  
Теперь большая часть эмиссии токенов блокчейна поступает на [CLAIM-балансы](welcome/wallet.md#claim-balans) пользователей пропорционально размеру их Силы Голоса к общей СГ в системе. Именно с этого баланса пользователи самостоятельно получают/востребуют токены \(решая, сколько из них направить в увеличение СГ, а сколько на [TIP-баланс](welcome/wallet.md#tip-balans) для вознаграждения развития активности сообщества\).

### Снижение срока понижения Силы Голоса

С учётом перехода к новой системе вознаграждений и обсуждения влияния возможных спекуляций на рынке, принято компромиссное решение уменьшить срок понижения Силы Голоса до 8 недель \(было 13 недель\).

### Добавление системы чеков/инвайтов

Пользователи могут создавать чеки на любое количество ликвидных токенов, имеющихся на балансе. Такие чеки/коды на предъявителя представляют собой пару ключей \(публичный и приватный\).

Это удобный элемент для привлечения новых пользователей - отправлять им чек с балансом, который они могут использовать при [упрощенной регистрации](https://golos.id/ru--golos/@lllll1ll/registraciya-akkaunta-po-invait-kodu). С использованием чеков токены можно продавать/покупать через площадки цифрового контента, распечатывать в виде QR-кодов, игр и т.д. [Подробнее &gt;](https://golos.id/ru--golos/@lex/cheki-kak-instrument-peredachi-tokenov)

### Реферальная программа

Дополнительный инструмент стимулирования привлечения аудитории. К каждой ссылке на посты пользователей при их авторизации добавляется `?invite=РЕФЕРЕР` Например, если вы поделились постом или прямой ссылкой на страницу Добро пожаловать \(`https://golos.id/welcome?invite=АККАУНТ`\) в случае регистрации после перехода по такой ссылке новый пользователь станет вашим рефералом.  
  
На протяжении 1 года вы \(как приглашающий/реферер\) будете получать 10% от вознаграждений, поступающих в адрес приглашенного/реферала. [Подробнее &gt;](https://golos.id/ru--golos/@lex/referalnaya-programma-i-para-slov-o-fonde-soobshestva)

## Февраль 2020

### Вознаграждения за репосты в соцсети

При взаимодействии с блокчейн-проектом [Sharpay](https://sharpay.io/ru/#view) в Golos Блоги добавлен блок кнопок "Поделиться" в социальные сети. Каждый репост + органические визиты по таким ссылкам из соцсетей оплачиваются токенами GOLOS на баланс кошелька [личного кабинета](https://app.sharpay.io/profile/wallet) сервиса Sharpay. [Подробнее &gt;](https://golos.id/ru--golos/@lex/reposty-v-socseti-s-voznagrazhdeniem-golosami-i-prochie-novosti)

### Удобный просмотр фотопостов 

Так как большое количество постов на Golos Блоги содержат фотографии и порой их интересно рассмотреть подробнее, по нажатию на фото теперь открывается [просмотрщик](https://golos.id/ru--golos/@lex/udobnyi-prosmotr-fotopostov-pravki-po-skrytiyu-kommentariev) с возможностью пролистывания + увеличения фото.

### Добавление Голос в рейтинги

Актуализирована информация о блокчейне Голос на [CoinMarketCap](https://coinmarketcap.com/currencies/golos-blockchain/%20), [СoinGecko](https://www.coingecko.com/en/coins/golos-blockchain%20), [СryptoCompare](https://www.cryptocompare.com/coins/gls/overview) и в популярном приложении [Blockfolio](https://blockfolio.com/).

### Запуск альтернативных веб-клиентов

Был запущен дополнительный веб-клиент Golos Блоги [golos.in](https://golos.in), который расположен на других серверах и использует другие ноды. Кроме того, отдельно был выделен клиент [golos.today](https://golos.today) \(для тестирования обновлений\).

В сети TOR начал работать [goloszrorrdctlwf.onion](http://goloszrorrdctlwf.onion). Также при использовании децентрализованных DNS от [OpenNIC](https://www.opennic.org/) доступен [gol.oss](http://gol.oss).

## Декабрь 2019

22 хардфорк \(обновление протокола блокчейна\)

### Добавлена система воркеров

Это функционал, который позволяет оплачивать токенами из [общего фонда](https://golos.id/workers) сообщества любую полезную работу для блокчейна Голос: разработка кода, серверы, реклама, дизайн, документация и пр. Словом, всё что угодно, если эту активность голосованием поддержит сообщество.  
  
Подобная практика стимулирования активности токенами потенциально может привести к появлению новых приложений, сервисов, игр, маркетинговой активности и многому другому. Важно, что не только делегаты, а все участники сообщества могут голосовать по заявкам как "за", так и "против". [Подробнее &gt;](https://golos.id/ru--golos/@lex/interfeis-dlya-zayavok-vorkerov)

### Настройки распределения эмиссии

У [делегатов](https://wiki.golos.id/witnesses/basics) блокчейна появилась возможность менять параметры % распределения эмиссии/печати токенов по пулам наград, чтобы более оперативно регулировать экономические процессы.  
  
По состоянию на май 2021 г. установлены след. параметры:

* 74% эмиссии - поступает держателям Силы Голоса на CLAIM-баланс \(с которого можно как увеличивать свою долю, так и вознаграждать активность других пользователей через TIP-баланс\);
* 15% - поступает делегатам блокчейна на обеспечение технической поддержки функционирования сети и оплаты серверов;
* 10% - поступает в фонд сообщества/воркеров, на дальнейшее развитие функционала, инфраструктуры, приложений, маркетинг и прочее;
* 1% - поступает в общий пул публикаций, токены с которого распределяются в зависимости от Силы Голоса кураторов при лайках/дизлайках \(компенсация за ранжирование контента\).

### Понижение Силы Голоса при неактивности

В случае, если на аккаунте в течение 6 месяцев не было совершенно действий с использованием активного ключа \(перевод токенов с основного баланса, увеличение СГ, ставки на [внутренней бирже](https://golos.id/market/GBG/GOLOS), выбор [делегатов](https://golos.id/~witnesses) и др.\) - запускается механизм понижения Силы Голоса, т.е. токены перемещаются с баланса СГ на ваш обычный/ликвидный баланс.

Тем самым эти аккаунты перестают влиять на выбор делегатов и получать долю от эмиссии токенов блокчейна пропорционально своей Силе Голоса \(так как пассивны в управлении и развитии проекта\).

### Изменение принципа голосования за делегатов

Если ранее можно было выбирать до 30 делегатов с полным весом своей Силы Голоса за каждого из них \(о минусах подобного писали [тут](https://golos.id/newgolos/@newgolos/voterules323289)\), теперь размер СГ станет делиться на кол-во поддерживаемых делегатов.

Напр. если у вас 30 000 Силы Голоса и вы поддержите 3 делегатов, в поддержку каждого из них будет отдано только по 10 000 СГ.

### Решение вопроса долга токена GBG

При объеме долга более 20% запускается механизм ежедневной конвертации 1% доступных на балансах GBG в GOLOS \(при этом ордера на внутренней бирже отменяются перед конвертацией\).  
  
Этот вариант был описан [здесь](https://golos.id/golos/@gusaru/sostoyanie-defolta-golos-blockchain-i-chto-s-etim-delat), а также [рассматривался](https://steemit.com/steem/@dantheman/steem-dollar-stability-enhancements) ранее как оптимальный одним из создателей проектов Bitshares/Steem/EOS. Данное решение позволит сделать стейблкоин более устойчивым в будущем.

