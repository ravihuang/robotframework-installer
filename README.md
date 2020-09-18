# RobotFramework installer
This is a windows installer created by [NSIS3](https://nsis.sourceforge.io/Download), which integrates python3.7.2, [RobotFramework](https://github.com/robotframework/robotframework) test framework, [RIDE](https://github.com/HelioGuilherme66/RIDE) editor and some robotframework libs.

**Latest release - [RobotFrameworkSetup-v9.2.0.exe](https://github.com/ravihuang/robotframework-installer/releases/latest)**

### Involved Library
```
python3.7.2
robotframework==3.2.2
robotframework-appiumlibrary==1.5.0.6
robotframework-autoitlibrary==1.2.5
robotframework-csvlibrary==0.0.2
robotframework-databaselibrary==1.2.4
robotframework-datadriver==0.3.6
robotframework-debuglibrary==2.2.1
robotframework-excellibrary==0.0.2
robotframework-faker==4.2.0
robotframework-jsonlibrary==0.2
robotframework-mongodblibrary==0.3.4
robotframework-openstflibrary==0.1.1
robotframework-redislibrary==1.2.1
robotframework-requests==0.7.1
robotframework-ride==1.7.4.2
robotframework-seleniumlibrary==4.3.0
robotframework-stublibrary==0.1.5
RESTinstance==1.0.2
```
### Supported OS
|platform|arch|
|---|-----|
|win7|64bit|
|win10|64bit|
|win7|32bit|

### How to install
- download latest .exe release file
- double click the exe file and keep clicking the 'Next' button to the end

### How to install new library:
please use rfpip to install new package:
```
C:\Users\Administrator>rfpip install psycopg2
```
