# postman-scratchpad
Postman version 11.37.5

[download patched file](https://github.com/arr037/postman-scratchpad/releases/download/p-11.37.5/newapp.asar)


![image](https://github.com/user-attachments/assets/ba8aaf9a-9488-461c-8db9-96719878c7ee)

Pre steps:
  1. export old current collection/env files

how make it:
1. Uninstall old version postman (if exists)
2.  Install new version (v11.37.5)
3.  Press `ctrl+shift+I`, then  click `Console tab`
4. paste `pm.settings.setSetting("offlineAPIClientEnabled", 0);` then close postman app
5. go to `C:\Users\{currentUser}\AppData\Local\Postman\app-{current-version}\resources`
6. rename `app.asar` to `old-app.asar`
7. download `newapp.asar`, paste to folder,  and rename it to `app.asar``
8. done

I recommend disabling auto-update.I haven't tested on later versions.

scratchpad is working postman latest version

