Make позволяет нарулить себе **библиотеку команд-шорткатов**, которые будут отражать семантику происходящего, а не реализацию:

`make deploy`, `make logs`, `make feature resubscription`

Makefile хранится в основном репозитории вместе с кодом и становится **живой документацией** по частоиспользуемым при разработке командам.


– *О, камон, Make - это же что-то очень древнее! Где ты это выкопал вообще?*
– *Я помню два года назад что-то собирал из сорцов мэйком. Разве он годится для чего-то еще?*
– *Слушай, я же не на сях пишу чтобы что-то там билдить. У меня уже есть **npm/rake/maven**, какой мне еще мэйк?*

Примерно так я думал, пока не разобрался в вопросе. 

По факту ==Make== – это такой **универсальный клей** между кучей технологий используемых в современной разработке. У него минимальный оверхед по сравнению со специфичными для языков инструментами.

Голосование в твиттере доказывает что с вероятностью в 75% вы не используете Makefile в своих проектах:

Если это так, значит что у вас сейчас есть возможность потратив пару часов, сэкономить себе в будущем гораздо больше времени.


Сейчас для меня ==Make== стоит в одном ряду с Ansible, Docker и GitLab CI. 
Это добротный универсальный, по-хорошему хипстерский инструмент для упорядочивания хаоса в рабочих скриптах на проекте.

Make всем хорош, но его официальная документация чересчур подробна, и, видимо, рассчитана на сисадминов-сишников, думающих на bash. Пробиться через неё без специальной подготовки нереально – слишком много специфики и деталей далеких от нужд современного разраба.

Поэтому я запилил мини-руководство по полезным для современного разраба фишкам Make. Получилось так:

7500 строк → 500 строк

На самом деле вам не нужно читать и их :)


Как же так?
Что же делать?

1. Чтобы **понять основную идею** использования Make и базовые правила, посмотрите [ролик от Хекслета](#intro) ▶️ (*8.5 минут на полуторной скорости*).

2. Если решили **применить Make на практике**, то вам пригодится [дока по основным фишкам и особенностям настройки Makefile](#handbook).

3. Если в стремлении навести порядок вы решили **идти до конца**, то для вас есть [расширенная версия](#soryan) с примером построения цельного workflow для dev/staging/production-окружений.


Руководство по современному ==Make==

1. Making your library of shortcuts
2. Overcoming Make weirdness
3. Multiple commands at once
4. Subcommands
5. Aliases
6. Multiline commands
7. Suppressing output
8. Conditional execution
9. Passing arguments

10. Advanced scripting==
11. Putting things in order==
12. Naming conventions==
13. Full workflow automation==
14. Guiding principles==

*Жмите на специальную [ссылку для самых умных](#too-smart) ;)*



## 💌Сорян!

Полная версия еще не готова.
Подпишитесь, и пришлю вам письмо, как только так сразу:

