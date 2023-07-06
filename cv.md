<img src="ava.png" width="40%" height="30%" />

# Леонид Сиваков
#### Контактная информация
телефон: +375445744003 
e-mail: magnum94@vk.com 
#### Социальные сети
VK: @magnum94
Telegram: @stackhop

## Инженер-программист
#### Студент второго курса специальности "Программная инженерия" Белорусско-Российского университета.

|Hard skills| Soft slills|
|-------------|------------|
|Владение языком программирования С#|Пунктуальность|
|Владение языком программирования Java|Коммуникабельность|
|Навыки работы с SQL Server Management Studio|Умение грамотно управлять своим временем|
|Владение языком гипертекстовой разметки HTML, так же CSS|Работа в команде|
|Владение навыками работы с Git| |
|Базовые навыки создания мобильных приложений (AndroidStudio, Kotlin)| |

## Языки
* Русский
* English (B1)

## Пройденные курсы
* Курс [Андрей Сумин] Котлин - быстрый старт

## Опыт разработки
* Start-up проект "Мобильное приложение по управлению сварочными процессами" (Android Studio, Kotlin)
* Мобильное приложение "Crypto Compare" (Android Studio, Kotlin)
* Десктопное приложение DoodleJump (Unity, C#)

## Код
Создание функции logout
```java
   fun logout() {
        compositeBag.add(
        repository.logout()
            .subscribeOn(Schedulers.io())
            .observeOn(AndroidSchedulers.mainThread())
            .subscribe({
                Log.d("LOGOUT", "success")
                _uiState.value = SelectionModeScreenState.LoggedOut
            }, {
                Log.d("LOGOUT", "error")
                _uiState.value = SelectionModeScreenState.Error(it)
            })
        )
    }
```

[def]: va.jp