## Проект mobile автотестов для приложения Wikipedia

<!-- Технологии -->

### Технологии
<p  align="center">
  <code><img width="5%" title="Pycharm" src="./attachments/logo/pycharm.png"></code>
  <code><img width="5%" title="Python" src="./attachments/logo/python.png"></code>
  <code><img width="5%" title="Pytest" src="./attachments/logo/pytest.png"></code>
  <code><img width="5%" title="Selene" src="./attachments/logo/selene.png"></code>
  <code><img width="5%" title="GitHub" src="./attachments/logo/github.png"></code>
  <code><img width="5%" title="Browserstack" src="./attachments/logo/browserstack.png"></code>
  <code><img width="5%" title="Appium" src="./attachments/logo/appium.png"></code>
  <code><img width="5%" title="Selenium" src="./attachments/logo/selenium.png"></code>

</p>

### Что проверяется в проекте:
Навигацию по экранам приложения Wikipedia 
- [x] Проверка отображения стартового экрана
- [x] Проверка отображения второго экрана
- [x] Проверка отображения третьего экрана
- [x] Проверка отображения четвертого экрана

### :computer: Запуск тестов из терминала
```bash
env -S "context=browserstack" pytest .
env -S "context=emulation" pytest .
```

<!-- Browserstack -->

### <img width="3%" title="Browserstack" src="attachments/logo/browserstack.png"> Запуск тестов в Browserstack
#### В Browserstack можем следить за прохождением тестов в реальном времени, а так же смотреть логи.

![This is an image](attachments/screenshots/browserstack.jpg)

<!-- Android Studio -->
### <img width="3%" title="Android Studio" src="attachments/logo/android-studio-icon.png"> Запуск тестов в Browserstack + эмулятор Android
![This is an image](attachments/video/mobile.gif)