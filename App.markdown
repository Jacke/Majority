Name: Majority

Description: SaaS based Application, that provide High-level and Low-level businnes automatisation plus Integration with Middle level, for Web agency, Web-market agency, Mobile developers, plain developers, freelancers...anyone who work in IT. That service build for IT Prof from IT Prof. We are love clear cashflow, big oportunuties and future technology. Closely concetrated on low-lever, but with sleek Hi-level callback.

Technology: 
1. Rails 4
2. Postgres 9
3. Backbone.js
4. Underscore
5. RequireJS
6. Localstorage
7. OfflineMode

Features:
Principle: Minimalism, as possible. Give Awesome feature to user, if he want it. Give freedom of choice, what service/language/merchant... decide user. 
Не поддерживать конкурентов, которые не идут на контакт, например Битрикс. Сделать как можно более удобный интерфейс, который сочитаеться с простотой и функциональностью, который будет работать из коробки, не требуя дополнительных завтрат. Если Студия хочет дополнительные сервисы, предоставить возможность широкого выбора из самых лучших продуктов на среднем уровне Basis.

Geography:
1. Russia
2. USA

_____
Сотрудники которые продаются(цена зависит от их ранга)


ERP Functional
- Развертывание отдельных модулей Stages, Mech, взаимодействие между ними в среде нескольких бизнес-объектов, которые находятся на большом растоянии друг от друга. 
- Предоставление возможности существовать как единая сущность, не влияя на расстояние.
- Средний уровень Basis, изменение во благо улучшения продуктов, которые будут подходить именно под определенную студию. Цена - качество - возможности
- Дополнительные функции для основных модулей Stages, Mech
Передача проектов партнерам, содействие в переходе через restavration mode.
- Big mech solution
- Enchanced Merchant(even cross-country, including their local taxes)
- Parthnership
- Legal stuff cross-city and changed based on business object
- Контроль доступности определеныых бизнес-объектов принять и выполнить заказ, если такое не представляется возможным то
- Перераспределение проектов на разные бизнес-объекты с целью скорейшего выполнения проекта, чтобы не потерять клиента.
- Cells betwen bussiness objects
ERP Merchant 
- Суммраный капитал компании в целом, исходя из всех офисов.
- Капитал по отделениям
- Контактирует плотно с Basis. 
- Поднимается вторая CRM для другого бизнес-объекта, либо добавляется если в существующей CRM есть такая возможность.
- Помощь по созданию и введению счета, предоставления выбора лучшего банка для введения его в определенном городе, в котором находится бизнес-объект.
ERP Parthnership
- Синхронизация и слияние некоторой функциональности моделуй Stages, Mech
- Кратко/Долговременные отношения между партнерами
- Позволяет обмениватся ресурсами(проектами, cells, вычислительными ресурсами), создавать совместный workflow, подстраивать enviorment.
- Позволяет избежать проектов которые висят, и на которых нету времени.
- Система отзывов, а также большое портфолио конкретно тех, кто будет заниматся чужим проектом, для того чтобы сделка между партнерами была успешной.


Биржа аутсорса(чтобы при минимальный сотрудниках студия могла работать(возможность создавать отвлетвления(работают как универсальная студия, но с другими проектами по другим требованиям Например студия 1 и студия 1.2 Лаборатория)))
Возможность заключать партнерские соглашения на проект


name: Pusher data to app
desc: 
Live push:
- commits
-creating/deleting branch
- update branch info
- while low level push to hight make it in realtime
- client feedback with abillity make post feedback hooks
- push changes when app be in online
- merchant data in realtime
___
thats all for now
Selected transport:
- websocket
- pusher.io
-- with fallback to plain page w/o javascript at all
flow: EV]___[request]__[transport]=___=[direct]___(APP)

name: Registration 
description: Студию регестрирует один человек, через специальную ссылку. Это позволяет сохранить формальности. Далее можно выполнить импорт mail адресов всех сотрудников студии, на которые будет отправленна ссылка регистрации, а также импортировать клиентов. При этом все эти действия можно вводить ручную. Импорт осуществляется через специальный шаблон файла в формате JSON, в котором содержаться специальные атрибуты и пустые значения, заполняющиеся скриптом импорта.
flow: [code]--/o_o\-[=]-/o_o\/o_o\

name: Location offers
description: Предоставление скидки в отдаленных районах от москвы для начинающих компаний. Еденица скидки определяется переменной Web 
Web = ст одной услуги в студии запросившей скидку / ст одной услуги в средней студии такого же уровня в москве
___
Внедрять только по необходимости, при низких продажах, или перед праздниками.

name: Wizard for routine work 
desc: 
flow: New bundle --> Two level configuration -> Cost -> [legal] - [legal] -> brief => BASIS => e_


name: Soft integration 
description: provide integration in system, that arleady used by making short links of Majority object
Also create browser plugin, that collect data from Majority and insert them to target or rewind
flow: 
if {%basis_app%} does creating project 
insert in textarea of creating project page link like http://majori.ty/dxt/p1 
plus data from that project page in Majority

name: Feed of action
description: Feed of Majority decentralized and in that feed info just most nececarsly for user, based on user status.
Trashy feed dont be there.

name: Future step
description: We provide service that engadge Basis object in Stage, also it may be integrated with solution that studio developed(sync their accouncy system with e-shop site)
