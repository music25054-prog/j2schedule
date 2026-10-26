# J2Schedule
## About
J2Schedule - new program for old J2ME platform, using simple code.
## Compiling
For compiling use these commands at Powershell
`& "C:\Program Files\Java\your_jdk\bin\javac.exe" -source 1.3 -target 1.3 -encoding UTF-8 -bootclasspath "your\path\to\wtk_or_j2me_sdk\lib\cldc_1.1.jar;your\path\to\wtk_or_j2me_sdk\lib\midp_2.0.jar" -d "saved\path\to\project\J2Schedule\bin" "saved\path\to\project\J2Schedule\src\J2Schedule.java"`


`& "your\path\to\jdk\bin\jar.exe" cvfm "your\path\to\project\J2Schedule\J2Schedule.jar" "your\path\to\project\J2Schedule\manifest.mf" -C "your\path\to\project\J2Schedule\bin" .`
