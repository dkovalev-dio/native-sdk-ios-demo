# 2GIS iOS NativeSDK Demo

> ⚠️ 2GIS NativeSDK в процессе разработки. Не подготовлено к использованию в боевых приложениях.

2GIS NativeSDK iOS Demo - это проект, демонстрирующий разработчику возможности использования нативного инструмента работы с картой от команды 2ГИС под iOS.

### Документация:
Демо-проект не охватывает всех возможностей NativeSDK. Для более детального анализа и проработки необходимо обратиться к [официальной документации](https://docs-canary.2gis.com/ru/ios/native/maps/reference/Container).

### Минимальные требования:
- XCode 12;
- Для того чтобы запусить проект через XCode достаточно использовать любой симулятор или девайс с операционными системами iOS 13.0+ или iPadOS 13.0+ (это обусловлено использованием в проекте [SwiftUI](https://developer.apple.com/documentation/swiftui)).

> **При необходимости можно использовать xcframework, расположенный по [ссылке](https://github.com/2gis/native-sdk-ios-swift-package/blob/master/Package.swift) для сборки собственного проекта под iOS 12**.

### Установка:
1. Склонировать проект любым удобным способом
 - через Терминал, используя команду 
```bash 
git clone https://github.com/2gis/native-sdk-ios-demo.git
```
 - через SourceTree File -> New -> Clone with URL
 - любым другим удобным способом
2. Запустить проект `app.xcodeprojxx в рутовой директории проекта.
3. Выставить ключи `DGISDirectoryAPIKey` и `DGISMapAPIKey` в файле `Info.plist`.

> Для получения ключей [напишите нам](https://dev.2gis.ru/order/).

4. Дождаться подгрузки свифтовых зависимостей (необходимо иметь устойчивое интернет-соединение, т.к. zip-архив с xcframework весит 200+ МБ).
5. <kbd>Cmd</kbd> + <kbd>R</kbd>

> ⚠️ В случае если зависимости не подгрузились, вы увидите уведомление **Build operations are disabled: Package loading in progress**. В таком случае нужно дождаться выполнения предыдущего пункта.

