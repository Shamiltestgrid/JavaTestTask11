## Лог mvn test
````
"C:\Program Files\AdoptOpenJDK\jdk-11.0.7.10-hotspot\bin\java.exe" -Dmaven.multiModuleProjectDirectory=D:\GDrive\Java\Lessons\5maven3 "-Dmaven.home=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\plugins\maven\lib\maven3" "-Dclassworlds.conf=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\plugins\maven\lib\maven3\bin\m2.conf" "-Dmaven.ext.class.path=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\plugins\maven\lib\maven-event-listener.jar" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\lib\idea_rt.jar=59448:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\bin" -Dfile.encoding=UTF-8 -classpath "C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\plugins\maven\lib\maven3\boot\plexus-classworlds-2.6.0.jar;C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.1\plugins\maven\lib\maven3\boot\plexus-classworlds.license" org.codehaus.classworlds.Launcher -Didea.version2020.1.1 test
[INFO] Scanning for projects...
[WARNING] 
[WARNING] Some problems were encountered while building the effective model for ru.netology:bonusCalculator:jar:1.0-SNAPSHOT
[WARNING] 'dependencies.dependency.version' for org.junit.jupiter:junit-jupiter:jar is either LATEST or RELEASE (both of them are being deprecated) @ line 14, column 22
[WARNING] 
[WARNING] It is highly recommended to fix these problems because they threaten the stability of your build.
[WARNING] 
[WARNING] For this reason, future Maven versions might no longer support building such malformed projects.
[WARNING] 
[INFO] 
[INFO] --------------------< ru.netology:bonusCalculator >---------------------
[INFO] Building bonusCalculator 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ bonusCalculator ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Copying 0 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ bonusCalculator ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ bonusCalculator ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory D:\GDrive\Java\Lessons\5maven3\src\test\resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ bonusCalculator ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-surefire-plugin:2.22.2:test (default-test) @ bonusCalculator ---
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running BonusServiceTest
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.041 s - in BonusServiceTest
[INFO] 
[INFO] Results:
[INFO] 
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  3.768 s
[INFO] Finished at: 2020-05-14T02:04:37+03:00
[INFO] ------------------------------------------------------------------------
````
Тестирование производилось в следующем окружении:

Windows 10 домашняя, 64-разрядная OpenJDK11 Командная строка Windows
