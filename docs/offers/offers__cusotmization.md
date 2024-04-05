# Декомпозиция предложений по разделам

**Вернуться в раздел [Общие результаты вычитки раздела безопасность](../index.md)**

## Раздел [Модуль user-authn](https://deckhouse.ru/documentation/v1/modules/150-user-authn/) и его подразделы

* Дать определение статического пользователя в предложении - Управление *статическими пользователями*.
* В [подразделе](https://deckhouse.ru/documentation/v1/modules/150-user-authn/#%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F-%D1%81-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%D0%BC%D0%B8) предложил бы добавить ссылку на инструкцию - *в необходимом namespace и добавить несколько аннотаций к Ingress-ресурсу*.
* Для [примеров](https://deckhouse.ru/documentation/v1/modules/150-user-authn/usage.html#github) не хватает ссылок на документацию гитлаба/гитхаба или скриншотов с тем, как попасть в нужные разделы. Мы у себя сталкивались с тем, что в таком подходе клиенты не понимали куда идти.
* [Кат](https://deckhouse.ru/documentation/v1/modules/150-user-authn/configuration.html) предложил бы перенести в FAQ, так как пугает при раскрытии.
* В [предложении](https://deckhouse.ru/documentation/v1/modules/150-user-authn/configuration.html) - HTTP является *слишком значительной* угрозой безопасности, курсив можно удалить без потери смысла.
* В [примере](https://deckhouse.ru/documentation/v1/modules/150-user-authn/faq.html#%D0%BA%D0%B0%D0%BA-%D1%8F-%D0%BC%D0%BE%D0%B3%D1%83-%D1%81%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-kubeconfig-%D0%B4%D0%BB%D1%8F-%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0-%D0%BA-kubernetes-api) ожидал пример результата выполнения.

## Раздел [Модуль user-authz](https://deckhouse.ru/documentation/v1/modules/140-user-authz/#) и его подразделы

* В 4 местах доки написано по-русски   секреты (что смог поиском найти), мелочь. Но можно однообразно написать, здесь же по-английски. Может быть тогда унифицировать везде?
* В [примере](https://deckhouse.ru/documentation/v1/modules/140-user-authz/usage.html#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-clusterauthorizationrule) мне было бы полезно пояснение 1-2 предложения, зачем мы это делаем.
* В [примере](https://deckhouse.ru/documentation/v1/modules/140-user-authz/usage.html) может быть добавить ссылку на то, как выпустить сертификат?
* В предложении *Модуль включен по умолчанию в наборах модулей* предлагаю добавить маркированный список для упрощения отображения.
* В [примере 1](https://deckhouse.ru/documentation/v1/modules/140-user-authz/usage.html) и [примере 2](https://deckhouse.ru/documentation/v1/modules/150-user-authn/usage.html) для упрощения восприятия попробовать поделить топики по решаемым задачам. Т.е. одна ссылка — один топик. И есть общая разводящая, где кратко описано зачем этот раздел нужен. Разводящая — Примеры конфигурации модуля user-authn  На ней краткая история того, для чего мы в этом разделе оказались. Какие задачи можем решить и где применить. В идеале, еще дифференциация примеров на базовый/продвинутый уровень сложности.


## Раздел [Политики безопасности](https://deckhouse.ru/documentation/v1/modules/015-admission-policy-engine/)

* В [разделе](https://deckhouse.ru/documentation/v1/modules/015-admission-policy-engine/) слово *навесить* кажется сленговым.

## Раздел [Аудит](https://deckhouse.ru/documentation/v1/modules/650-runtime-audit-engine/#%D0%B0%D0%BB%D0%B5%D1%80%D1%82%D1%8B)

* В "подвале" [страницы](https://deckhouse.ru/documentation/v1/modules/650-runtime-audit-engine/#%D0%B0%D0%BB%D0%B5%D1%80%D1%82%D1%8B) не хватает дальнейших действий.

## Раздел [Модуль network-policy-engine](https://deckhouse.ru/documentation/v1/modules/050-network-policy-engine/)

* Предложение *Этот подход оказался прост и надежен, поэтому показал себя с лучшей стороны.* сразу вызывает вопрос - в сравнении с чем?
* В [заголовке](https://deckhouse.ru/documentation/v1/modules/050-network-policy-engine/examples.html) кажется можно сделать покороче - **Запретить обращаться снаружи к подам**

## Раздел [Модуль cert](https://deckhouse.ru/documentation/v1/modules/101-cert-manager/cr.html)

* Не понял назначения ссылок в разделе. Что с этой информацией делать? Нужно по ссылкам пройти и что-то поделать? Открыть ссылки и самому там искать что-то?
