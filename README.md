
# DonationExecutor - плагин для Minecraft (Spigot/Paper)

Плагин, который, получая информацию о новых донатах с Donation Alerts, автоматически генерирует различные события на основании суммы доната.

## FAQ

#### Как этим пользоваться?

1. Вам понадобится сервер версии 1.18.1 (другие версии не тестировались) на ядре Spigot / Paper.
2. Скачайте плагин, закиньте его в папку сервера "/plugins".
3. Запустите сервер, подождите полной загрузки, остановите сервер.
4. Откройте появившийся конфигурационный файл DonationExecutor.yml в папке "/plugins/DonationExecutor".
5. Заполните конфигурационный файл в соответствии с инструкциями в нем (особое внимание уделите токену Donation Alerts и никнеймам стримеров - каждый ник нужно ввести не только в строке с никами, но и перед каждой таблицей с суммами донатов). Сохраните изменения, закройте файл.
6. Запустите сервер. В случае корректно заполненного конфиг-файла, все должно работать.


#### Это плагин или мод?

Это плагин, его необходимо добавить только на сам сервер. Однако, для полной функциональности и работоспособности (например, отображение кастомных скинов на мобах) вам понадобится мод [Optifine](https://optifine.net/downloads) последней версии.

#### Могу ли я вручную сымитировать донат? (например, если донат не сработал автоматически, или я хочу протестировать донат)
Да. Донат можно протестировать командой "/d donate <сумма доната без копеек> <ник донатера (необязательно)>".

#### Где я могу увидеть доступные настройки?

После первого запуска сервера с плагином, откройте конфигурационный файл DonationExecutor.yml в папке "/plugins/DonationExecutor".

#### Могу ли я изменить/дополнить этот код и использовать его в коммерческих целях?

Нет, но вы можете связаться со мной и изложить свои коммерческие предложения через мой email - igortokach@gmail.com
Если я не ответил за 2 дня, значит ваше предложение мне неинтересно.
Под коммерческим использованием НЕ подразумевается стриминг - стримить с этим плагином вы можете АБСОЛЮТНО БЕСПЛАТНО. 
Если вы стример и хотите, чтобы я добавил в плагин какие-то уникальные действия/события именно для вас - свяжитесь со мной через email, указанный выше.

#### Планируется ли дальнейшее развитие плагина и добавление новых событий или функций?

Да. Но так как это по большей части мое хобби, я буду обновлять плагин по мере моих возможностей и наличия свободного времени.

#### Почему все комментарии и описание на русском языке?

Плагин в данный отлавливает донаты только с Donation Alerts, которым пользуются в подавляющем большинстве русские стримеры. Также зрители моего видео об этом плагине на YouTube могут не знать английского языка, что сделает процесс ознакомления с кодом для них более сложным.
Я знаю, что на гитхабе и в среде программистов общепринят английский язык, но в данной ситуации я не думаю, что это для кого-то будет критично.
## Автор

- [@link1107](https://www.github.com/link1107)
- [Мой YouTube-канал](https://youtube.com/c/ИгорьЛинк)

