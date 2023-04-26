# Camara
# cd Camara
# npm install
# ionic serve
# npx cap add android
# npm run build
# npx cap sync
# npx cap open android
## luego que abra android estudio esperar que instale las dependencias, buscar la opcion Build, luego Build blunde apk y build apk

# Dependencias que se instalo
## npm install @ionic/pwa-elements
### configurar main.ts
### agregar en la linea 6 ==>> import { defineCustomElements } from '@ionic/pwa-elements/loader';
### agregar dentro de router.isReady() ==>> defineCustomElements(window);
## npm install @capacitor/android
## npm install @capacitor/filesystem
## npm install @capacitor/camera
### cofigurar AndroidManifest.xml
### ruta ==>> android\app\src\main\AndroidManifest.xml
### <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
### <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />