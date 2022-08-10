# Гайд по аддонам

<p align="center">
<img src="https://raw.githubusercontent.com/MagicalCow/TrinkIT-News/main/Sources/Assets/Guides/Guide-Addons-01.jpg" width="600"/>
</p>  

Вы никогда не задавались вопросом отчего ваши глаза кровоточат в стольких играх или почему некоторая косметика интерфейса казалось бы очевидна всем кроме разработчиков игры? Это потому что разработчики игры заняты в основном тем чтобы игра быстро и исправно отрисовывала сам мир и считала цифры урона и отхила, разработчик по сути это пожилой уставший технарь который от рождения способен видеть красоту но не практикует прекрасное да и видит красоту *слегка* по другому.

Поэтому в редких играх есть действительно хороший интерфейс. Интерфейс конечно, по хорошему, стоило бы отдать людям которые выясняют статистическими методами отзывы игроков о нём но это все находится где то в далеком будущем, поэтому исправлять эту проблему придется нам, с помощью напильника и какой то матери.

В отличие от других игр, инфраструктура модов в WoW крайне текучая и то что было нормой в кате, возможно уже мхом поросло в актуале. И наоборот, когда жирные капиталисты рвут курсфордж на куски, порождая застой, появляются прекрасные куски кода навроде [Immersion](#mod-immersion) или [Narcissus](#mod-narcissus). Какие то моды, стоявшие в игре годами становятся частью игры, какие то отмирают из-за изменения механик игры, какие то не переживают смену патчей а какие то просто уходят освобождая место новым. Скоро у нас начнется Dragonflight и Близзард обещают большой реворк интерфейса, что заставляет задуматься о большом вымирании некоторых аддонов но, серьезно, все мы знаем как работает близзард и скорее всего большую часть интерфейса придется менять.

Поэтому запасемся мы заранее большим черным мешком модов чтобы быть готовым к любой пытке для глаз которую нам готовят близзы. Некоторые аддоны помечены разными пиктограммами:  
- **📖:** Аддон был предназначен для механик\систем прошлых патчей и уже не актуален но все еще может пригодиться на каче.  
- **⏳:** Аддон устарел и может вызывать ошибки но еще работает, благодаря милости титанов или пользовательским патчам.  
- **💀:** Аддон фактически мертв\заброшен\непоправимо сломан и находится тут только ради исторических отсылок.  
- Макросы для вызова тех или иных функций аддонов перечислены в секции самого аддона а в главе [*Инструменты*](#mods-tools) мы покажем как делать интересные кнопки или скрипты для интеграции.

<a name="toc"/>  

## Содержание
- [**Аддоны интерфейса**](#mods-interface)

- [**А когда?**](#dates)
- [**А как?**](#howto)
- [**Инструменты**](#mods-tools)

## Аддоны интерфейса
Начнем, пожалуй, с модов общего назначения, улучшающих окна и механики игры.

### [DBM](https://www.curseforge.com/wow/addons/deadly-boss-mods)
Один из самых старых и противоречивых (среди сомневающихся и безруких конечно) аддонов. Этот аддон призван помочь тебе не забыть о крайне болезненной абилке босса, прогнать тебя из лужи если ты зазевался или банально показать куда бежать на dance механиках. Некоторые игроки ноют мол никто не учит рейдовые механики из-за дбм но если подумать - а нахуй их запоминать то? Века эволюции дали нам роботов для запоминания унылого говна навроде таймеров фазы босса, гордиться тем что ты запомнил через сколько секунд Иннерва начнет тебя ебать третьим контейнером это такой себе повод для гордости. Да и даже если ты запомнил то обязательно ведь найдется пара варов у которых голова начинает болеть от таких объемов информации, поэтому лучше все таки иметь дбм у каждого рейдера чтобы исключить самые смешные и частые ошибки.  

- Мод разбит на модули и позволяет, для оптимизации памяти, включать только нужные, будь то модуль какого либо патча или специфичного данжа или рейда. Или положиться на мод в этом отношении, он самостоятельно выгружает все ненужные для текущего босса модули.  
<!--FIXIT: Картинка с модулями DBM-->
- Мод предупредит вас на манер рейдового предупреждения о грядущем спелле и в большинстве случаев даст короткое описание того что нужно сделать для противостояния ему. Используются множество средств чтобы предупредить вас, мигание текста, цветные рамки, звуки и даже ваши сторонние текстуры и звуки - все используется для максимизации времени отклика игрока на событие.  
<p align="center">
<img src="https://media.forgecdn.net/attachments/76/27/dbm-warnings1.png" width="300"/>
</p>  

- Мод так же поддерживает [паки озвучки](https://www.curseforge.com/wow/addons/search?search=vem), вы ведь всегда хотели чтобы Шварцнеггер вам говорил когда нужно [скорее садиться на вертолет](https://www.curseforge.com/wow/addons/arnold-schwarzenegger-vem-dbm)?

<p align="center">
<a href="https://www.youtube.com/watch?v=1BG77gB7Y2w"><img src="https://i1.ytimg.com/vi/1BG77gB7Y2w/hqdefault.jpg" width="500"/></a>
</p>  

- Мод понимает ваши роли в пати и фильтрует информацию таким образом чтобы не докучать дд предупреждениями о смене танка или большом уроне по рейду который требуется подхилить.  
- Мод работает автоответчиком и отвечает всем (кто не состоит в рейде) что вы деретесь с боссом и ответите им позже.  
- Аддон имеет свой оверлей на экране в котором отсчитываются красивыми полосочками с иконками откат тех или иных важных спеллов у вашей тимы или босса.  

<p align="center">
<img src="https://media.forgecdn.net/attachments/76/31/dbm_timers.jpg" width="300"/>
</p>  

- Аддон умеет общаться со своими копиями у других игроков в рейде и даже после дисконнекта будет иметь актуальную информацию о ходе боя.
- Мод полностью совместим с викаурами и моды могут опираться на таймеры и переменны друг друга.

**Команды:**  
- **/dbm** - показать/скрыть интерфейс аддона.  
- **/dbm help** - Выведет в чатике все доступные команды.  

### [Details](https://www.curseforge.com/wow/addons/details)
счетчик дпс\хпс\прочих показателей, нахуй скаду  
### [Exorsus Method Raid Tools](https://www.curseforge.com/WOW/addons/method-raid-tools)
description  
### [MikScrollingBattleText](https://www.curseforge.com/wow/addons/mik-scrolling-battle-text)
накати, красивенько выкатывает уведомления об откатах абилок, критах, уроне  
### [MistsOfTirnaScitheHelper](https://www.curseforge.com/wow/addons/mists-of-tirna-scithe-helper)
description  
### [MythicDungeonTools](https://www.curseforge.com/wow/addons/mythic-dungeon-tools)
description  
### [PersoLootRoll](https://www.curseforge.com/wow/addons/persolootroll)
description  
### [PGFinder](https://www.curseforge.com/wow/addons/premade-group-finder)
description  
### [PremadeGroupsFilter](https://www.curseforge.com/wow/addons/premade-groups-filter)
description  
### [Raeli's Spell Announcer](https://www.curseforge.com/wow/addons/rsa)
description  
### [RaiderIO](https://www.curseforge.com/wow/addons/raiderio)
description  
### [SavedInstances](https://www.curseforge.com/wow/addons/savedinstances)
напоминалки о кд инстов, полезно если фармишь что нибудь в героик\мифик инстах. Для тех кто забывает что сегодня среда.  
### [Armory](https://www.curseforge.com/wow/addons/armory)
более подробное армори, илвлы, прочность прямо на иконках, редактируемый список выводимых стат итд  
### [BattleGroundEnemies](https://www.curseforge.com/wow/addons/battlegroundenemies)
фреймы для спискоты на бг  
### [BugGrabber](https://www.curseforge.com/wow/addons/buggrabber)
Description  
### [BugSack](https://www.curseforge.com/wow/addons/bugsack)
для бывалых, которые имеют более 50-100 модов, выдает более удобное и функциональное окно багрепортов луа.  
### [CovenantMissionHelper](https://www.curseforge.com/wow/addons/covenantmissionhelper)
description  
### [ElvUI/TukUI](https://www.tukui.org/welcome.php)
на вкус  
### [Executive_Assistant](https://www.curseforge.com/wow/addons/exec_assist)
description  
### [GSE: Advanced Macro Compiler](https://www.curseforge.com/wow/addons/gse-gnome-sequencer-enhanced-advanced-macros)
description  
### [LargerMacroIconSelection](https://www.curseforge.com/wow/addons/larger-macro-icon-selection)
description  
### [MacroToolkit](https://www.curseforge.com/wow/addons/macro-toolkit)
минисреда для написания макросов  
### [Masque](https://www.curseforge.com/wow/addons/masque)
description  
### [MountJournalEnhanced](https://www.curseforge.com/wow/addons/mount-journal-enhanced)
description  
### [Notes](https://www.curseforge.com/wow/addons/notes)
description  
### [NoteworthyII](https://www.curseforge.com/wow/addons/noteworthy-ii)
description  
### [OmniCC](https://www.curseforge.com/wow/addons/omni-cc)
description  
### [OPie](https://www.curseforge.com/wow/addons/opie)
выдает кольца абилок, на одну кнопку можно повесить кольцо с 8 абилками, как минимум пригодится для всех этих телепортирующих итемов  
### [Overachiever](https://www.curseforge.com/wow/addons/overachiever)
более функциональное окно ачивок  
### [Paste](https://www.curseforge.com/wow/addons/paste)
аддон для вставки многострочных макросов, поставь на вовхеде почти везде используют листы отметок для ачивок  
### [Postal](https://www.curseforge.com/wow/addons/postal)
небольшие изменения почтового окна  
### [SwitchSwitch](https://www.curseforge.com/wow/addons/switchswitch)
description  
### [TalentSetManager](https://www.curseforge.com/wow/addons/talent-set-manager)
редактор наборов талантов с кнопочкой для быстрой смены  
### [TinyPad](https://www.curseforge.com/wow/addons/tinypad)
description  
### [Titan](https://www.curseforge.com/wow/addons/titan-panel)
description  
### [ToyBoxEnhanced](https://www.curseforge.com/wow/addons/toy-box-enhanced)
description  
### [WeakAuras](https://www.curseforge.com/wow/addons/weakauras-2)
ну ето тупо второй интерфейс, поставь, посмотри канал автора мода.  
### [WowheadQuickLink](https://www.curseforge.com/wow/addons/wowhead-quick-link)
description  
### [ZerethMortisPuzzleHelper](https://www.curseforge.com/wow/addons/zereth-mortis-puzzle-helper)
description  


[Арт](https://www.artstation.com/artwork/Bmom99) от [Andrey Alekseev](https://www.artstation.com/jaddakcarter)  
#гайды #аддоны