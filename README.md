# Bolideai Ui Kit

## Описание
Набор кастомных компонентов для приложения Bolideai.

## Установка

```sh
npm i tool-bolideai-icons-kit
```

### Список доступных компонентов
Card, ResourceList, PageTitle, Navigation

```js
import { PageTitle } from 'tool-bolideai-ui-kit';

export const App = () => {

    return (
       <PageTitle label='Dashboard'>
            <div className="flex space-x-6">
                <Button
                    onClick={() => alert('つ ◕_◕ ༽つ')}
                >
                    Click on me
                </Button>
            </div>
        </PageTitle>
    )
}

```


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
