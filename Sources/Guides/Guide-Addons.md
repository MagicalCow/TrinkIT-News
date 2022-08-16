# Гайд по аддонам

<p align="center">
<img src="https://raw.githubusercontent.com/MagicalCow/TrinkIT-News/main/Sources/Assets/Guides/Guide-Addons-01.jpg" width="600"/>

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
	- [**DBM**](#mod-dbm)
	- [**Details**](#details)
	- [**Exorsus Method Raid Tools**](#method-raid-tools)
	- [**MikScrollingBattleText**](#mik-scrolling-battle-text)
	- [**MistsOfTirnaScitheHelper**](#mists-of-tirna-scithe-helper)
	- [**MythicDungeonTools**](#mythic-dungeon-tools)
	- [**PersoLootRoll**](#persolootroll)
	- [**PGFinder**](#premade-group-finder)
	- [**PremadeGroupsFilter**](#premade-groups-filter)
	- [**Raeli's Spell Announcer**](#rsa)
	- [**RaiderIO**](#raiderio)
	- [**SavedInstances**](#savedinstances)
	- [**Armory**](#armory)
	- [**BattleGroundEnemies**](#battlegroundenemies)
	- [**BugGrabber**](#buggrabber)
	- [**BugSack**](#bugsack)
	- [**CovenantMissionHelper**](#covenantmissionhelper)
	- [**ElvUI/TukUI**](#elvui)
	- [**Executive_Assistant**](#exec_assist)
	- [**GSE: Advanced Macro Compiler**](#gse-gnome-sequencer-enhanced-advanced-macros)
	- [**LargerMacroIconSelection**](#larger-macro-icon-selection)
	- [**MacroToolkit**](#macro-toolkit)
	- [**Masque**](#masque)
	- [**MountJournalEnhanced**](#mount-journal-enhanced)
	- [**Notes**](#notes)
	- [**NoteworthyII**](#noteworthy-ii)
	- [**OmniCC**](#omni-cc)
	- [**OPie**](#opie)
	- [**Overachiever**](#overachiever)
	- [**Paste**](#paste)
	- [**Postal**](#postal)
	- [**SwitchSwitch**](#switchswitch)
	- [**TalentSetManager**](#talent-set-manager)
	- [**TinyPad**](#tinypad)
	- [**Titan**](#titan-panel)
	- [**ToyBoxEnhanced**](#toy-box-enhanced)
	- [**WeakAuras**](#weakauras-2)
	- [**WowheadQuickLink**](#wowhead-quick-link)
	- [**ZerethMortisPuzzleHelper**](#zereth-mortis-puzzle-helper)


- [**Инструменты**](#mods-tools)

<a name="mods-interface"/>  

## Аддоны интерфейса [⇑](#toc)
Начнем, пожалуй, с модов общего назначения, улучшающих окна и механики игры.

<a name="mod-dbm"/>

### [DBM](https://www.curseforge.com/wow/addons/deadly-boss-mods) [⇑](#toc)
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
- Мод полностью совместим с викаурами и моды могут опираться на таймеры и переменные друг друга.

**Команды:**  
- **/dbm** - показать/скрыть интерфейс аддона.  
- **/dbm help и /dbm help2** - Выведет в чатике все доступные команды.  
- **/dbm unlock** - Показывает таймер в строке состояния, таймер можно таскать.  
- **/range <число>** - Показывает окно с радиусом. Пример: /range 5 откроет окно радиуса на 5м., очень полезно для боев где нужно разбегаться в стороны.  
- **/dbm timer** - запускает кастомный таймер DBM. Пример: */dbm timer 10 ждем пока хил попьет* отобразит 10-секундную шкалу таймера со этой фразой.  
- **/dbm arrow** - Показывает стрелку DBM, которой можно указывать на координаты или другого игрока.  
- **/dbm pull <sec>** - отправляет рейдовым предупреждением таймер пулла; например, /dbm pull 10.  
- **/dbm break <min>** - Подобно команде pull, отправляет в рейд уведомление о перерыве с заданным количеством минут.  
- **/dbm version** - Проверяет версию DBM, установленную у игроков в рейде. Использование */dbm version2* также отправляет игрокам сообщение, если аддон устарел.  
- **/dbm lockout** - Проверяет КД босса у пати\рейда.  
- **/dbm lag** - Проверяет лаг у игрока.  
- **/dbm durable** - Проверяет на прочность состояние гира участников рейда.  

<a name="details"/>

### [Details](https://www.curseforge.com/wow/addons/details) [⇑](#toc)  
</p>  
<p align="center">
<img src="http://i.imgur.com/WjbOXzt.png" width="300"/><br>
<i>Самый оптимизированный, надежный и красивый счетчик ДПСА для World of Warcraft.</i>
</p>  

- **Легкая настройка**: Панель параметров с понятной навигацией, быстрое открытие и закрытие окон\вкладок, добавление избранных счетчиков в закладки.

- **Надежные результаты:** Чтение комбатлога в реальном времени позволяет точно совпадать с показателями сайтов с логами, навроде [warcraftlogs](https://www.warcraftlogs.com/).

- **Низкое потребление ресурсов:** В рейде, в интенсивных боях, во время БЛ, Details не просадит вам фреймрейт.

- **Дополнительные инструменты:**  
	- **Свои настраиваемые счетчики:** создайте свой собственный набор счетчиков, используя Details! API.

	</p>  
	<p align="center">
	<img src="https://i.imgur.com/wI9NkeJ.png" width="600"/>
	</p>  

	- **Рейдовые утилиты:** набор небольших инструментов, помогающих в рейдах.

	</p>  
	<p align="center">
	<img src="https://i.imgur.com/AUxPim7.png" width="600"/>
	</p>  

	- **Викауры на основе счетчиков:** Details позволит вам создавать свои викауры в несколько кликов.
	
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/ZfZhL05.png" width="600"/>
	</p>  
	
	- **Ранжирование боя:** В конце боя\инста вы сможете глянуть сводную таблицу с общими результатами урона\отхила.
	
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/esDLHVn.png" width="600"/>
	</p>  
	
	- **Отображение билдов и илвла:** Details покажет таланты и уровень гира любого участника боя.
	
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/KlWtUjZ.png" width="600"/>
	</p>  
	

- **Плагины:**
	- **Encounter Details:** Детальный отчет о последнем бое.

	</p>  
	<p align="center">
	<img src="https://i.imgur.com/1AjSgEH.png" width="600"/>
	</p>  
	
	- **Chart Viewer:** Отчет с графиками дпс\хпс.
	
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/Ev8Dhsy.png" width="600"/>
	</p>  
	
	- **Advanced Death Logs:** Отчет о частоте покидания тела варами.
	
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/WZVTWPC.png" width="600"/>
	</p>  
	
	- **Time Line:** отчет о применении баффов\дебаффов\кд во время боя.
	</p>  
	<p align="center">
	<img src="https://i.imgur.com/VKhLtdg.png" width="600"/>
	</p>  

<!--FIXIT:Как встраивать окна детейлса-->
<!--FIXIT:Настройки-->
<!--FIXIT:Зум окна-->
<!--FIXIT:Отображение Me и закрепление своей полоски-->

<a name="method-raid-tools"/>

### [Exorsus Method Raid Tools](https://www.curseforge.com/wow/addons/method-raid-tools) [⇑](#toc)  
description  

<a name="mik-scrolling-battle-text"/>

### [MikScrollingBattleText](https://www.curseforge.com/wow/addons/mik-scrolling-battle-text) [⇑](#toc)  
накати, красивенько выкатывает уведомления об откатах абилок, критах, уроне  

<a name="mists-of-tirna-scithe-helper"/>

### [MistsOfTirnaScitheHelper](https://www.curseforge.com/wow/addons/mists-of-tirna-scithe-helper) [⇑](#toc)  
description  

<a name="mythic-dungeon-tools"/>

### [MythicDungeonTools](https://www.curseforge.com/wow/addons/mythic-dungeon-tools) [⇑](#toc)  
description  

<a name="persolootroll"/>

### [PersoLootRoll](https://www.curseforge.com/wow/addons/persolootroll) [⇑](#toc)  
description  

<a name="premade-group-finder"/>

### [PGFinder](https://www.curseforge.com/wow/addons/premade-group-finder) [⇑](#toc)  
description  

<a name="premade-groups-filter"/>

### [PremadeGroupsFilter](https://www.curseforge.com/wow/addons/premade-groups-filter) [⇑](#toc)  
description  

<a name="rsa"/>

### [Raeli's Spell Announcer](https://www.curseforge.com/wow/addons/rsa) [⇑](#toc)  
description  

<a name="raiderio"/>

### [RaiderIO](https://www.curseforge.com/wow/addons/raiderio) [⇑](#toc)  
description  

<a name="savedinstances"/>

### [SavedInstances](https://www.curseforge.com/wow/addons/savedinstances) [⇑](#toc)  
напоминалки о кд инстов, полезно если фармишь что нибудь в героик\мифик инстах. Для тех кто забывает что сегодня среда.  

<a name="armory"/>

### [Armory](https://www.curseforge.com/wow/addons/armory) [⇑](#toc)  
более подробное армори, илвлы, прочность прямо на иконках, редактируемый список выводимых стат итд  

<a name="battlegroundenemies"/>

### [BattleGroundEnemies](https://www.curseforge.com/wow/addons/battlegroundenemies) [⇑](#toc)  
фреймы для спискоты на бг  

<a name="buggrabber"/>

### [BugGrabber](https://www.curseforge.com/wow/addons/buggrabber) [⇑](#toc)  
Description  

<a name="bugsack"/>

### [BugSack](https://www.curseforge.com/wow/addons/bugsack) [⇑](#toc)  
для бывалых, которые имеют более 50-100 модов, выдает более удобное и функциональное окно багрепортов луа.  

<a name="covenantmissionhelper"/>

### [CovenantMissionHelper](https://www.curseforge.com/wow/addons/covenantmissionhelper) [⇑](#toc)  
description  

<a name="elvui"/>

### [ElvUI/TukUI](https://www.curseforge.com/wow/addons/elvui) [⇑](#toc)  
на вкус  

<a name="exec_assist"/>

### [Executive_Assistant](https://www.curseforge.com/wow/addons/exec_assist) [⇑](#toc)  
description  

<a name="gse-gnome-sequencer-enhanced-advanced-macros"/>

### [GSE: Advanced Macro Compiler](https://www.curseforge.com/wow/addons/gse-gnome-sequencer-enhanced-advanced-macros) [⇑](#toc)  
description  

<a name="larger-macro-icon-selection"/>

### [LargerMacroIconSelection](https://www.curseforge.com/wow/addons/larger-macro-icon-selection) [⇑](#toc)  
description  

<a name="macro-toolkit"/>

### [MacroToolkit](https://www.curseforge.com/wow/addons/macro-toolkit) [⇑](#toc)  
минисреда для написания макросов  

<a name="masque"/>

### [Masque](https://www.curseforge.com/wow/addons/masque) [⇑](#toc)  
description  

<a name="mount-journal-enhanced"/>

### [MountJournalEnhanced](https://www.curseforge.com/wow/addons/mount-journal-enhanced) [⇑](#toc)  
description  

<a name="notes"/>

### [Notes](https://www.curseforge.com/wow/addons/notes) [⇑](#toc)  
description  

<a name="noteworthy-ii"/>

### [NoteworthyII](https://www.curseforge.com/wow/addons/noteworthy-ii) [⇑](#toc)  
description  

<a name="omni-cc"/>

### [OmniCC](https://www.curseforge.com/wow/addons/omni-cc) [⇑](#toc)  
description  

<a name="opie"/>

### [OPie](https://www.curseforge.com/wow/addons/opie) [⇑](#toc)  
выдает кольца абилок, на одну кнопку можно повесить кольцо с 8 абилками, как минимум пригодится для всех этих телепортирующих итемов  

<a name="overachiever"/>

### [Overachiever](https://www.curseforge.com/wow/addons/overachiever) [⇑](#toc)  
более функциональное окно ачивок  

<a name="paste"/>

### [Paste](https://www.curseforge.com/wow/addons/paste) [⇑](#toc)  
аддон для вставки многострочных макросов, поставь на вовхеде почти везде используют листы отметок для ачивок  

<a name="postal"/>

### [Postal](https://www.curseforge.com/wow/addons/postal) [⇑](#toc)  
небольшие изменения почтового окна  

<a name="switchswitch"/>

### [SwitchSwitch](https://www.curseforge.com/wow/addons/switchswitch) [⇑](#toc)  
description  

<a name="talent-set-manager"/>

### [TalentSetManager](https://www.curseforge.com/wow/addons/talent-set-manager) [⇑](#toc)  
редактор наборов талантов с кнопочкой для быстрой смены  

<a name="tinypad"/>

### [TinyPad](https://www.curseforge.com/wow/addons/tinypad) [⇑](#toc)  
description  

<a name="titan-panel"/>

### [Titan](https://www.curseforge.com/wow/addons/titan-panel) [⇑](#toc)  
description  

<a name="toy-box-enhanced"/>

### [ToyBoxEnhanced](https://www.curseforge.com/wow/addons/toy-box-enhanced) [⇑](#toc)  
description  

<a name="weakauras-2"/>

### [WeakAuras](https://www.curseforge.com/wow/addons/weakauras-2) [⇑](#toc)  
ну ето тупо второй интерфейс, поставь, посмотри канал автора мода.  

<a name="wowhead-quick-link"/>

### [WowheadQuickLink](https://www.curseforge.com/wow/addons/wowhead-quick-link) [⇑](#toc)  
description  

<a name="zereth-mortis-puzzle-helper"/>

### [ZerethMortisPuzzleHelper](https://www.curseforge.com/wow/addons/zereth-mortis-puzzle-helper) [⇑](#toc)  
description  




[Арт](https://www.artstation.com/artwork/Bmom99) от [Andrey Alekseev](https://www.artstation.com/jaddakcarter)  
#гайды #аддоны