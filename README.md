# Проект с индивидуальной предметной областью

**Выбранная предметная область:** ЮВЕЛИРНЫЙ МАГАЗИН

**Цель работы:** реализовать программное обеспечение для мониторинга и управления данными ювелирного магазина, включая учёт изделий, клиентов и сотрудников.

## Задачи проекта:
1.	Реализовать программное обеспечение для учета клиентов, сотрудников, изделий.
2.	Приложение должно обеспечивать возможность продавцу быстро и легко выполнять свои функции:
*	собирать данные о клиентах и их заказах,
*	вести учёт товаров,
*	отслеживать готовность заказов клиентов,
*	обновлять информацию о наличии товаров в сети магазинов,
*	уведомлять мастера о новых поступлениях заказов и ремонтов.
3.	Обеспечить возможность генерации отчётов по продажам, клиентам и товарам.

## Функциональные требования:
Приложение реализуется в виде windows-приложения с удобным навигационным меню, качественным отображением информации и простыми формами для заполнения данных.

*Основные возможности, которые будут предусмотрены приложением:*
1.	Приложение реализуется с авторизацией по логину/паролю.
2.	Основной режим работы приложения упрощает работу продавца, предоставляет все необходимые ему функции, однако ограничивает доступ к информации о сотрудниках.
3.	Доступ к особому режиму создания/изменения сотрудников, назначения им окладов, мониторингу их работы будет осуществляться по особому логину/паролю, которые будут выданы директору.
4.	Все данные будут храниться в csv-формате и подтягиваться при очередном запуске приложения. 
5.	При запуске приложения будет проводиться автоматическая проверка и удаление устаревших записей (например, неактуальных клиентов).
6.	Хранить информацию о предпочтениях клиентов и истории их покупок.