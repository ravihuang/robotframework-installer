# RobotFramework installer
This is a windows installer, integrates [python3], [RobotFramework] test framework, [RIDE] editor and some robotframework libraries.

- created by NSIS

**Latest release - [RobotFrameworkSetup-v9.1.exe](https://github.com/ravihuang/robotframework-installer/releases/latest)**

### Include Library
```
python3.7.2
robotframework-ride==1.7.3rc1
robotframework==3.1
robotframework-appiumlibrary==1.5.0.1
robotframework-autoitlibrary==1.2.2
robotframework-csvlibrary==0.0.2
robotframework-databaselibrary==1.1.1
robotframework-debuglibrary==1.1.4
robotframework-excellibrary==0.0.2
robotframework-faker==4.2.0
robotframework-jsonlibrary==0.2
robotframework-mongodblibrary==0.3.4
robotframework-openstflibrary==0.1.1
robotframework-redislibrary==0.3
robotframework-requests==0.5.0
robotframework-seleniumlibrary==3.3.1
```
### Supported OS
|platform|arch|
|---|-----|
|win7|64bit|
|win10|64bit|
|win7|32bit|

### How to install
- download latest .exe release file
- double click the exe file and Click Next...

### How to install new library:
please use rfpip to install new package:
```
C:\Users\Administrator>rfpip install psycopg2
```
