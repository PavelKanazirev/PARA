7z pass - krpa27

# Preparation

* 01 - Define a goal of the talk.
To share with the audience - the computational process for environmental

* 02 - Who will be in the audience?
Robotic entusiasts who are interested in the automotive industry

* 03 - Brainstorm and think of facts, data, demos, but don't forget personal stories too!

  In Neaples ( South Italy ) - an automated vehicle would most probably stay stopped

* 04 - Filter out based on which content supports your goal in front of your audience

* 05 - Order the content so that there is logical flow in your presentation

* 06 - Rehears and time yourself! Don't underestimate this part! At least 5 rehearsals!

 Each of the slides should be scannable for 3 seconds  
 Chosing the right images for your slides is crucial! Look at the ones that support my point
 

# Delivery
 Never start your presentation with an excuse  
 Engage the audience before the session  
 Handle questions with empathy 
 Zoomlt is my friend - Ctrl+1 and Esc

## Slide 1
Малко за мен - гледна точка - опит с камери и най-интересния проблем за мен в работата с образи - разпознаването на обекти. Сега ще отделя малко време, за да опитам да споделя как си представям да протече тази среща. В никакъв случай не си я представям като лекция - такъв тип събития ме отчайват. Все пак предвид, че аз съм малко по-подготвен от другите участници ( най-малко предоставил съм слайдове, по които ще се движим ) - би било некоректно да го наречем и дискусия ... Аз си го представям като тематичен разговор - представям слайдовете един след друг и ако някой иска да сподели опит или да отбележи, че нещо е интересно - го обсъждаме. Иска ми се да науча малко повече за аудоторията - нека видим какви възможности ни дава Zoom за комуникация - има ли вдигане на ръка, чат, въпроси, ... Нека ги използваме, а аз ще опитвам да ги преглеждам в края на всеки слайд. Първо колко от вас имат някакъв опит с радио комуникация. Има ли хора от аудиторията, които не са шофьори? Има ли хора, които докато шофират са усещали как автомобила им автоматично е забавял скоростта или провокирал натискане на спирачка?

## Slide 2
В началото ще ви споделя всичко, което знаех за възприятията на роботите преди да получа възможността да участвам в проект свързан с разработването на радар професионално. ... 

## Slide 3
Разпознаването се случва на няколко нива и тук ще спомена един стар анекдот относно това как биха изглеждали системите за сигурност, ако бяха създадени от Майкрософт. Т.е. разпознаването е важно, но какво правим с наличната информация получена след разпознаването е не по-маловажно
...  
( DAQ - data acquisition )
Електрическото измерване на физично явление/физически явления наричаме събиране на данни.
  Какви са причините за събиране на данни?
  - следене представянето на системата - KPI
  - оценяване поведението на продукт при определени условия
  - тестване на система с цел оптимизиране на представянето
  - калибриране
  - изследване и разпознаване определени фактори в очаквана работна за продукта среда

Примери - логване, mf4, вибрация, температура, замърсяване, RPM ( revolutions per minute обороти в минута ), въртящ момент ( torque ), натоварване, налягане, скорост, ускорение, ...

  Най-често измеравни физични явления: температура, светлина, звук, сила и налягане, позиция и отстояние, вибрация, Potential of Hydrogen ( киселинност или алкалност на разтворими във вода елементи )

## Slide 4
Да. Хората далеч не сме съвършенни и минаваме през различни състояния, които ни правят още по-несъвършенни.
Ако например тъщата ми стои до мен - колкото и добър и внимателен шофьор да съм ... могат да станат грешки.
  Аз самия много обичам да карам колело, но като шофьор ми е много трудно с всички колоездачи и мотористи, които се движат по по-странен начин, отколкото съм свикнал. Има държави и градове, в които такъв тип участници в движението са мнозинство и електронния помощник би могъл да е незаменим, ако ние самите не сме свикнали да шофираме в такива условия.


## Slide 5
От какво има нужда едно автономно превозно средство, за да бъде водено от алгоритми и данни не по-лошо отколкото би се справил един човек?
  Човек има чувство за ориентация на база на заобикалящите го предмети. Същото е с шофьора - ние поглеждаме в огледалата и през прозорците, защото искаме да се ориентираме - преди често се случваше да изпращаме и човек на местата с ниска видимост ( например зад превозното средство ) , който да ни дава знаци, за да ни помогне да направим маневра по един по-безопасен начин. Сега в концепцията за автономно шофиране ( използва се съкращението ADAS - Advanced driver-assistance systems ) най-често срещаме следните устройства. Планирането е тези технологии да бъдат въвеждани на различни технологични стъпки -     
    Level 0: No Automation. ...
    Level 1: Driver Assistance. ...
    Level 2: Partial Automation. ...
    Level 2+: Advanced Partial Automation. ...
    Level 3: Conditional Automation. ...
    Level 4: High Automation. ...
    Level 5: Full Automation. )

## Slide 6
Относно ултразвуковите сензори - принципа на работа прилича, на този за който разказах в слайд 2 ...  Огромното предимство е, че масово разпространените сензори са евтини и почти не се влияят от климат - валежи, мъгла, ...
  Разчита се, че при паркиране няма нужда от разпознаване на бързо движещи се предмети и на прекалено малки също. Риска тук е от бързодвижещи се малки животни ( ако алгоритмите в бъдеще не ги засичат - природозащитници могат да ни погнат за намаляване популацията на градски плъхове )

## Slide 7
Такъв тип устройства са известни като GNSS ( Global Navigation Satellite System ) у нас по-разпространено като GPS ( Global Positioning System ) - системи съставени от 24 или повече спътника - разположени симетрично и излъчващи координиран сигнал относно текущото време - синхронизиран с останалите спътници. Когато го получи приемника ( обикновено приема от поне 4 спътника - данните са достатъчно, за да се направи извод за местоположението с точност от около метър до няколко метра )...  
  Налични карти обикновено има вградени и през връзка с Интернет - те могат да бъдат актуализирани - в зависимост от доставчика на автомобила ( обикновено OEM ). Тук мога да разкажа малко професионален опит от работата ми с подобни технологии - те са изключително напреднали и докато преди 15 години все още имаше водещи европейски производители, които допускаха сериозни дефекти, то вече процеса на актуализация е стандартизиран и много добре отработен

## Slide 8
  Различни видове automotive сертифицирани камери - освен за паркиране при задно виждане, които да заместват тъщата, която обикновено влиза в тази роля и такива, които надеждно разпознават маркировка и пътни знаци. Разликите между automotive и другите обикновено са ( размер, консумация, покрита дистанция, голямо многообразие от преглагани резолюции при обикновените - докато повечето automotive камери са преди всичко аналогови ) . Друго приложение на камерите е при сгънати огледала - могат да предотвратят произшествие свързано с отваряне на вратата ...
   Какъв според вас е най-големия минус на камерите - недостатък.

## Slide 9
  Термални камери - решават проблеми свързани с отблясъци от светлина, дим, отблясъци от пътя заради течности, нощ, ... Не са скъпи и личното ми усещане е, че този продукт към момента е подценяван и употребата му само ще се разширава

## Slide 10
  Все още навлизат - има голям потенциал особено за товарни превозни средства ...  

## Slide 11
  Тук може да си пофантазираме дали след време няма да има фейсбук или инстаграм за превозни средства ... 
    Идеи от ваша страна за какво би могло това да се ползва? 

## Slide 12
  Лидарите са относително нова технология, която предстои да узрява. Работи като на практика върти на 360 градуса лъч, като приема отразяването от него. Това създава малък недостатък, защото са въвлечени моторчета и по-висока степен на сложност. Ако трябва да ги съпоставим с нещо - най-подходящия аналог са радарите. Преди 20-22 години тепърва се говори в областта на автомобилната електроника за радари и те са доста скъпи. Сега технологията е узряла и все по-често идните 20 години очаквам да виждаме автомобили с "буркани" върху покрива. Ако ми позволите една аналогия - бих казал, че Лидара е като Тесла в смисъла на това, което ми разказа мой приятел, който кара "Тесла". Той ми каза, че е приятна като кола, но е необходимо човек ако има Тесла да има още една кола в гаража за изтински нужди ...  

## Slide 13
  За добро или за лошо климатичните условия влияят на контролерите, които се използват за моделиране. Казвам за добро, защото в много случаи при лошо време - шофьорите с развито чувство за опасност предпочитат да отлагат пътуването - трудно е да се предпазим от падащи разстения, понесени от вятъра предмети и т.н. Мой приятел ми е разказвал как докато го е изпреварвал камион скъсан болт от гумата на камиона е излетял перпендикулярно на посоката му на движение и това, че все още е жив си е случайност. Аз си представям какви предмети биха могли да летят с каква скорост при буря ... Тук се надявам и вие да ми помогнете - какви природни явления според вас не съм включил в този списък, а биха имали влияние върху възприятието на гореизброените сензори? ...  

## Slide 14
  Стигнахме и до основата и централната тема в тази презентация - радара. Някой измежду вас да е полицай или да е учил в школата в Симеоново? ( питам, защото по-нататък имам малко шеги с представителите на закона, та да проуча да си нямам проблеми ) Да разбирам и, че нямате близки, роднини, бащи, свекъри и тъстове от силите на реда и най-вече от КАТ нали? Ако обърнем внимание на снимката по-долу вдясно - нека увелича ( знаете различни колеги ползват различен размер монитори ) - се вижда много добре водещото предимство на лидара ( в добро време разбира се ), което съответно е водещ недостатък за радара ( дали е по-лесно да разпознаем човек, който не се движи с лидар или с радар ) ...  

## Slide 15
  Има история, която намирам за забавна - преди втората световна война английското правителство е обявило обществена поръчка или както тогава се е казвало за унищожаване на домашни животни от разстояние ( мисля, че овце) ... в резултат на това Робър Уотсън-Ват е помогнал на английското правителство да бъде една идея по-добре подготвено за втората световна война. В САЩ са развили технологията за засичане на кораби, разузнаване е извършвано от стратосферата с помощта на балони и радари, силно е приложимо от нашите метеоролози - спомагат за идентифициране на какво разстояние има водни капки и приблизително с какъв размер са в ( почти ) реално време. За места като Алпи, Апенини, Аляска, Сибир, ... разбира се и за да ни глобяват по всякакви невероятно изобретателни начини 

## Slide 16
   the United Kingdom, Germany, the United States, the USSR, Japan, the Netherlands, France, and Italy. In addition, Britain shared their information with the United States and four Commonwealth countries: Australia, Canada, New Zealand, and South Africa, and these countries also developed their own radar systems. During the war, Hungary was added to this list. 
     Сериозната стъпка е създадения в UK магнетрон, след което са създадени значително по-малки по размер устройства, които успяват да доставят измервания с точност под 1 метър ... 
  Heinrich Hertz - През 1886–1888 немският физик Heinrich Hertz завършва серия от експерименти доказващи наличието на електромагнитни вълни (включително радио вълни), това съществуване е предсказано през 1862–4 от шотландският физик Джеймс Максуел. През 1887 Hertz открива, че тези вълни могат да минават през различни материали и също да се отразяват от метални повърхности. Тези свойства наподобявали много свойството на светлината
  Guglielmo Marconi - 1899 - засича отразени радио вълни , а през 1916 съвместно с Чарлз Франклин - използват къси вълни за техни експерименти, което е основа за по-нататъшни развития на радара като технология; през 1922 година заключава пред Сдружение на Електрическите инженери в Лондон, че според техните изследвания е напълно възможно да се създаде уред, който изпращайки лъч към друг предмет - да получава информация относно отстоянието му
  Christian Hülsmeyer - 1904 прави публични демонстрации в Германия и Холандия за засичане отразени сигнали от кораби с устройство, което конструира и смята с него да помогне на корабите да намалят катастрофите. Той има успехи с кораби на 3 километра като не успява да измери дистанцията, но коректно отчита наличие или не на такива обекти.
  Робърт Уотсън Ват - съвместно с Арнолд Уилкинс успяват през 1935 да получат отразен лъч от бомбардировач летящ на 49 метра от земята.
  Джон Рандал и Хари Буут през 1940 създават "кух магнетрон" - който на практика е радар работещ с 10 сантиметрови вълни. Устройството е с големината на чиния и напълно приложимо за целите на полетите.

  В САЩ - Албърт Тейлър през 1922 като част от морската радио лаборатория докато извършва комуникационни експерименти - долавя отразен радио сигнал от дървен кораб. През 1924 създават такъв изпращач на сигнали ( transmitter )
  В СССР - Александър Попов 1897 засича върнат сигнал от кораб в Балтийско море

 В Япония е първия известен случай на използване на безжичен телеграф през 1904, което им помага да спечелят битка 

 В Холандия - Филипс през 1937 правят успешен магнетрон

 Във Франция - Морис Понте 1934 - патентова магнетрон
  
     
  След втората световна употребата се разширява и към цивилна авиация, морска навигация, метеорология, медицина

## Slide 17
  Ами това е употребата, за която аз знаех преди година. Вица си пада малко сексистки, но мен поне ме разсмя - полицая пита закъде бързахте толкова, защо не спряхте когато ви дадох знак и клетия шофьор отговаря, че преди време жена му избягала с полицай и сега избягва полицейски коли, за да не му я върнат обратно. Този тип измерване вече се правят доста лесно и бързо и са изключително достъпни. Технологията е узряла и усвоена и в повечето случаи грешките са от недобра или зловередна конфигурация. Тук да кажа, че имам приятели полицаи и уважавам много работата им, ако някой се съмнява колко е трудна работата на редовите съвестни служители - мога да му изпратя снимка на истинско полицейско чекмедже - пълно с ...  

## Slide 18
  Различни типове влизат в употреба за различни приложения:
  LCA - подаваме мигача, леко въртим волана на ляво и ... ако нещо писка ( освен тъщата на предната седалка ), то е добре че го има, защото вероятно сме пропуснали да погледнем в огледалото. Би могло да спомогне и при заспиване на шофьор ( това е много често срещана причина за произшествия )
  BSD - същите условия като предишните, но този път сме погледнали в огледалото, а не сме видяли предмета. Има такъв термин "сляпо петно", рядко огледалата покриват пълния периметър - особено с бързо движещи се мотористи е напълно реалистично да не бъде отразен подвижен предмет от огледалото
  PCR - зад нас някой се е засилил и в този случай може би е добре преди сблъсъка да се задейства въздушната възглавница
  RTA - излизаме на задна скорост от паркинг, ако нямаме спътник на задната седалка
  FCTA - минаваме на кръстовище, ние може да разчитаме на светофара, но някой друг да не разчита ( лична история - Адам Мицкевич и Сливница, добре че не си бях пуснал радиото и го чух )
  EAF - може да забрани на вратата да се отваря, ако сензора усети бързо движещо се превозно средство, което минава през радиуса ( хордата ) описана от отварянето на вратата
  OFI - понякога просто не преценяме добре габаритите на колата. В различните държави има различни култури - например може да преброите лично в град като Париж или Марсилия колко от колите са удряни по ъглите и колко не.
   ...  

## Slide 19
  Има радари с такива размери. Повечето са с размера на мишка за компютър например, но когато е ясно за какво ще се използва радара и как да бъдат разположени антените в платката вътре - този обем е достижим . В предишните слайдове споменах за еволюцията на лидарите - тази статистика имах предвид. Твърдението на експерти е, че автономните автомобили ще се ориентират към архитектура с 6 или повече радара, но нека приемем че са 6. Това означава от около 82 милиона автомобила очаквани да бъдат произведени през 2023-та и 60% ( 60% от 492 = около 300 ) млн радара ...  

## Slide 20
От коя формула тръгва цялата идея
...  

## Slide 21
Доплеровото отместване, ако не е ясно на някой - пълно е с клипчета в Интернет с линейки, които обясняват нещо звучащо толкова сложно, колко всъщност е лесно разбираемо и често срещано. Тук искам да обърна внимание на една матрица долу вдясно - триизмерна - обикновено тази матрица представлява изходните данни от самия сензор
...  

## Slide 22
Това е една от базовите теоретични формули включващи изкривявания на сигнала от антената.
...  

## Slide 23
ЛЧМ - линейно честотна модулация ( FMCW )
подава се както на предавателя, така и на смесителя на приемника, при което на междинна честота излиза постоянен спектър с разлика тау което е времезакъснението.
Ако се движат двата обекта се добавя и доплеровото отместване. Така на изхода на приемника се получава този голям израз. Като експонентата показва хармоничния характер, т.е. имаме синусоида. Същия този израз го има и в двумерното и в тримерното пространство, когато се добави азимута и елевацията. 
Последната формула е за времезакъснението на директен и отразен лъч. Тъй като имаме не само директни лъчи, които попадат в приемника, но и отразени. Всичко това е добре оттренирано 41-45 година по време на втората световна война.

## Slide 24
Тук искам само да отбележа основната разлика между FMCW и предишните типове радари. Новите работят с измерване измествания на честотата.
Всъщносто всичко това го имаме от физиката - просто извършваме едно заместване, за да получим формулата в синьо за статичен обект.
За динамичен обект има малко усложнения - ако се фокусираме единствено върху първата формула - нямаме достатъчно информация, затова правим и второ измерване - откъдето вече имаме да решим система от уравнения с две неизвестни ( R и vr )
...  

## Slide 25
При подвижни обекти много често се случва два обекта да са много близо един до друг - макар и големи е трудно да бъдат различени с радио вълни, особено ако те са с еднаква честота. При решаване на уравненията получаваме две двойки точки и за да получим, коя е истинската имаме нужда от трето измерване - с друга честота.
...  

## Slide 26
  Попитали Радио Ереван: "Вярно ли е, че България е изнесла за Япония 500 компютъра?". Радиото отговорило: "Има нещо вярно, само че не са били 500, а 500 хиляди, и не са били компютри, а компоти, и не са били за Япония, а за Германия, и не са били изнесени, а са били върнати." 
    Тук нямаме такъв лукс. Изследването на средата се прави на няколко нива. Първо разпознаване на отстоянията на обектите, след това скорост и параметри. След това състояние на самия автомобил. Приемане информация от камерите и другите сензори за самата траектория и на нашия автомобил и на околните ( при завой очакванията са други). Височина на препятствията ( видяхте ли вчерашната катастрофа на пътя Девин СувОрово ).
      Самото разпознаване на обекти обикновено се прави с приоритет на безопасността. Почти винаги заедно с разпознаването върви параметър - определящ сигурността на това разпознаване и за рискови предмети - различна стойност е определяща.

...  

## Slide 27
  Какъв е стандартния алгоритъм за разпознаване на обекти? виж и слайд 28
  А в бъдеще - ( невронни мрежи, big data, ml, AI, какви ли не други съкращения ЦРУ, ФБР, :) ... )
...  

## Slide 28
  Правим много измервания на реални такива обекти в различни условия. Стремим се подбрания материал да е статистически издържан и това се касае за обстановка ( различен климат и осветеност и зашумяване ), за гъстота на обектите - само 1 обект или много такива обекти сред 1 от другите и много от другите, количество подвижни и неподвижни, самото състояние на движещия се автомобил. Обикновено число от 10000 статистически добре разпределени заснети сцени са добра отправна точка за различни алгоритми като впоследствие 70 % от тях се използват за съставяне алгоритмите за класификация, а 30 за тестване
...  

## Slide 29
  Има ли хора, които да са работили над половин година с Матлаб? Разпознахте ли как проверяваме данните и как ги подготвяме, за да минат през алгоритмите за разпознаване?
...  

## Slide 30

...  

## Slide 31
...  

## Slide 32
Ето тук долу вляво - контролера вече знае, че има кола на пътя. Ако си имахме тъща седяща на предната седалка тя вече щеше да вика - внимавай, къде караш има кола на пътя, ти кьорав ли си - искаш да ме убиеш - знаех си аз, че ти не си подходящ за дъщеря ми, казах ѝ аз на Станка, Милка, Спаска или там както се казва дъщеря ѝ според случая. 
...  

## Slide 33
...  

## Slide 34
...  

## Slide 35
  Ами пожелавам ви да не се плашите от шофирането като този манекен от карикатурата и да си купувате нови коли - с радари, за да може моята заплата да расте :) ...  

## Slide 36
  Разбира се работата на радара е да разпознае и да подаде сигнал към другите контролери, а производителя ще вземе решение какъв вид ще бъде реакцията към шофьора - може да е нещо много приятно в далечните метри като пеещи птички, а с наближаването немските производители могат да вградят Рамщайн например - там ще се изказват психолози и други видове -лози. Аз съм си взел поука, че в последните деетилетия е добре човек да се специализира тясно, за да разбере дори и такива лесни наглед неща като микроконтролерите в автомобилната електроника и даже когато чуя човек да се изказва с претенцията за компетентност в 2-3 или повече сфери, скептика в мен заговаря.Сега искам да събудя скептика във вас. Нека преди да отворя последния слайд да ви питам - какви според вас ще бъдат бъдещите проблеми за разрешаване пред използването на радари за разпознаване на обекти от движещи се превозни средства?
...  
  Според вас какви са пречките за това да не се случат в близките 1-2 десетилетия масово използване на автономни автомобили? Или поне нека се фокусираме върху по-развитата част от географията - държави като САЩ, Канада, Норвегия, Япония, Германия. Мислите ли, че там до 20 години все още автономните автомобили ще са по-малко от 10%?

## Slide 37
Финално преди да пристъпим към общите въпроси да споделя с вас, че аз съм изключителен късметлия и имам страхотна тъща, която на моменти обичам повече от жена си, но има толкова много вицове по темата, че не можех да не се възползвам от тази употреба за целите на тази презентация
...  

# References
World Healthcare Organization
https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries

Medium:
https://medium.com/@BabakShah/ultrasonic-sensors-in-self-driving-cars-d28b63be676f

GPS Triangulation:
https://wiki.seeedstudio.com/GPS-Modules-Selection-Guide/

Cameras in ADAS:
https://www.futurebridge.com/industry/perspectives-mobility/gated-sensor-in-adas-improved-vehicle-safety/

https://www.bosch-mobility-solutions.com/en/solutions/camera/multi-purpose-camera/

Infrared Cameras:
https://www.intechopen.com/chapters/56860

http://autocaat.org/uploadedFiles/Content/Technologies/Connected_and_Automated_Vehicles/The_Road_to_Automated/FLIR%20Thermal%20for%20ADAS%20and%20AV.pdf

INS / GNSS
https://www.mathworks.com/discovery/inertial-navigation-system.html

V2X и DSRC
https://www.autonomousvehicleinternational.com/features/c-v2x.html#prettyPhoto/0/

Radar
https://en.wikipedia.org/wiki/History_of_radar#/media/File:F8F-2_Bearcat_of_VF-111_on_USS_Valley_Forge_(CV-45)_on_27_April_1949_(80-G-K-9904).jpg

Lidar 2 Radar
https://medium.com/@intellias/the-ultimate-sensor-battle-lidar-vs-radar-2ee0fb9de5da

Police Radar:
https://copradar.com/chapts/chapt3/ch3d1.html
https://imgflip.com/meme/69339111/Police-Fine

Radar IC size:
https://www.mwrf.com/technologies/systems/article/21849983/microwaves-rf-driving-safely-with-automotive-radar-systems

Radar explanation:


Weather conditions:
https://www.mdpi.com/1424-8220/21/16/5397

OTC:
https://www.mdpi.com/1424-8220/21/11/3854



Accidents caused by bad weather conditions:
https://www.after-car-accidents.com/car-accident-causes.html

Percentage vehicles with radar ( around 60 from 81.6 mln cars produced ):
https://youtu.be/RfJiiSlesyE?t=443
year 2000 cost - 7000 USD ( ACC )

FMCW - Rhode & Swartz
https://youtu.be/8qaCSQ83ZyU?t=268
static + movable object
Frequency ( 78 GHz )
Specific slope Fdev / Tcpi
With this type of radars we are not interested in t ( tao ) but in Fb ( beat frequency )
Tcpi = time at which a slope is identified
We exclude the time delay by using the beat frequency. The same value is received using a frequency measurement and not a timing measurement.

dynamic - R - distance, Vr - radial velocity

This equasion is not solvable as it is - so we are taking a new measurement by lowering the frequency
After appending the equasion for Fb2 - this system from equations is solvable unambiguously for a single target.

  In order to detect multiple targets - you need to have a different slope ( наклон )




IEEE - page 16
Graphics:
https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7870764&tag=1

Leading material:
https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7870764&tag=1

OTC:
https://ieeexplore.ieee.org/document/7533931


LCA, BSD, PCR, RTA, FCTA, EAF, OFI :
https://youtu.be/P-C6_4ceY64?t=809


Pulsed radar concern:
https://youtu.be/QYwkuvhuPgI?t=538
how to differentiate between multiple objects?


https://youtu.be/IxoPYhXY30k
