# Bolideai Ui Kit

## Описание
Провайдер для передачи состояний между микрофронтэндами в Module Federation

## Установка

```sh
npm i tool-microfrontend-shared-state
```

### Как использовать?

В родительском приложении:
```js
import { ShareContextProvider } from 'tool-microfrontend-shared-state';

<ShareContextProvider.Provider value={{ key: 12345, time: Date.now() }}>
    ...
</ShareContextProvider.Provider>

```

В любом дочернем приложении


## Сборка и обновление

1. Установить зависимости
```sh
npm install
```
2. Внести изменения
3. Сбилдить
```sh
npx webpack
```

## Автор
Дубов В.C.
vitaliy.dubov@bolide.ai
