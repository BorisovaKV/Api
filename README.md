# Тестирование Api

На основе ресурса https://qa.demoshopping.ru/ 

Я создала [коллекцию](https://www.postman.com/qualityengineer-2891085/my-workspace/collection/hc6ovn2/demoshopping) в Postman и протестировала все методы, которые там предусмотрены

Для первых шести методов Products я написала автотесты и запустила их через функцию Run Collection, [результаты прогона](https://drive.google.com/file/d/1oNzeJluBlBO1CC2liwEOW4uRNygeH7R4/view?usp=drive_link)

Используя следующий [WSDL](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), я создала коллекцию в Postman

С помощью методов SOAP-сервиса были получены данные на примере России:
- `ListOfContinentsByName` — список континентов
- `ListOfCurrenciesByName` — список валют
- `ListOfCountryNamesByName` — список стран
- `CountryName` — получение названия страны по коду
- `CountryISOCode` — получение кода страны по названию
- `FullCountryInfo` — полная информация о стране
- `LanguageName` — название языка по коду

[Коллекция в Postman](https://www.postman.com/qualityengineer-2891085/my-workspace/folder/q52bs2p/soap)

