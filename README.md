# 1. Подключение
  Копируете vless, открываете nekobox.
  Нажмите на «+» в правом верхнем углу -> «Импортировать из буфера обмена».
  Профиль появится в списке. Нажмите на него и  нажмите на кнопку снизу для запуска

# 2. Важная настройка
  Щас настроено так, чтобы с впн нельзя было зайти на сайты .ru, сделано это, чтобы снизить шансы потерять сервак.
  Чтобы у вас работали Сбербанк, Госуслуги, Яндекс.Карты и другие российские сервисы, настройте обход:
  В NekoBox зайдите в Настройки:<img width="305" height="581" alt="scrcpy_HUJuwvEr7o" src="https://github.com/user-attachments/assets/0e102aaa-8baf-4301-953a-ac58d31a5505" />


  Найдите пункт Режим VPN для приложений: <img width="417" height="174" alt="scrcpy_lTxhpWI2kL" src="https://github.com/user-attachments/assets/45f0fbed-88bb-4cef-854c-ee7e1a8ada56" />

  Сверху нужно нажать на кнопку "Обход" ( выделена красным на скрине), возможно ее не будет видно, для этого мне требовалось развернуть телефон в горизонтальное положение:
  <img width="406" height="446" alt="scrcpy_cIljU7gXqY" src="https://github.com/user-attachments/assets/f37675e1-c81f-4096-a1ef-a4ff89b9a98f" />
  
  Дальше выбираете нужные приложения (т.е, те на которые подключение будет без впна)
# 3. Чтобы снизить затупы у VPNа:
  Зайдите в Настройки Android вашего телефона -> Приложения -> NekoBox.
  Пункт Батарея -> выберите «Не ограничивать» (или «Высокая производительность»).

  В самом NekoBox зайдите в настройки и включите «WakeLock»:<img width="401" height="107" alt="scrcpy_5Rvi7oqoZV" src="https://github.com/user-attachments/assets/baef41d0-f233-44f2-8b44-7b27b1c7c4d7" />

Помимо этого, требуется в MTU установить значение: 1500 <img width="436" height="406" alt="scrcpy_SEnp1WRrlE" src="https://github.com/user-attachments/assets/6b34af95-a448-4909-9c27-1d5d7858bd5d" />

А также в настройках DNS выставить следующие параметры:
* Удаленный DNS: 8.8.8.8; Прямой DNS: 77.88.8.8
  <img width="469" height="769" alt="scrcpy_GK9mBVfBTf" src="https://github.com/user-attachments/assets/53da4e9d-0b5f-47e7-b706-1fb95a0a88ce" />
