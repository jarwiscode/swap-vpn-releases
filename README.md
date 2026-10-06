# SWAP VPN — установщики

Официальные сборки приложений [SWAP VPN](https://swap-vpn.com). Скачивать удобнее
со страницы **[swap-vpn.com/downloads](https://swap-vpn.com/downloads)**: там же
приложения для других устройств и инструкция по подключению.

## Windows

SWAP VPN для Windows 10 и 11 — в разделе [Releases](../../releases): установщики
для x64 (Intel, AMD) и ARM64 (Snapdragon) и файл `SHA256SUMS.txt` с контрольными
суммами.

Приложение пока не подписано сертификатом разработчика, поэтому при первом запуске
Windows может показать «Система Windows защитила ваш компьютер». Нажмите
«Подробнее» → «Выполнить в любом случае». Проверить, что файл не изменён, можно
по контрольной сумме:

```powershell
Get-FileHash .\SWAP-VPN-1.0.0-amd64-setup.exe -Algorithm SHA256
```

В этом репозитории только готовые установщики, без исходного кода.

Поддержка: [help.swap@proton.me](mailto:help.swap@proton.me)
