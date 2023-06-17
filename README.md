# BurpSuiteProfessional-2023
Burp or Burp Suite is a set of tools used for penetration testing of web applications. It is developed by the company named Portswigger.
<br>

<b>Burp Loader Keygen For Linux:</b>
<br>
https://drive.proton.me/urls/BSKP5VM4SC#i5iW1Z2OghRi

<b> Burp Suite 2022.8.5 Linux</b>
<br>
https://portswigger-cdn.net/burp/releases/download?product=pro&version=2022.8.5&type=Jar


<b>Burp Suite for Windows 2022.8.5</b>

--> https://drive.google.com/drive/folders/1UIYfUAFJFfwIwhp-IukJeqSpkzdXRcAz?usp=share_link



# Burp-Loader
##################################** Prequisites **#############################################

	**Download .jar file for Burp Suite Pro from**
		--> https://portswigger.net/burp/releases/
	**Download Burp Loader files. Then Follow Below Steps for Activation**
		--> https://github.com/hackwithsumit/Burp-Loader/
	**If using in Windows 10, Download and Install Java and JDK**
		**For Java** --> https://javadl.oracle.com/webapps/download/AutoDL?BundleId=244068_89d678f2be164786b292527658ca1605
		**For JDK**  --> https://www.oracle.com/in/java/technologies/javase-jdk15-downloads.html

################################** Execution and Activation **################################
	
	**1. Place all files in 1 folder**
		For Example lets take as --> C:\Users\hackwithsumit\Desktop\burp\
	----------------------------------------------
	**2.1 Run This Command for Windows in CMD Prompt.**
		java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"C:\Users\hackwithsumit\Desktop\burp\loader.jar" -noverify -jar "C:\Users\hackwithsumit\Desktop\burp\burpsuite_pro_v2022.1.jar"
	**2.2 Run this command for Linux in Terminal. Suppose Your files are in /home/kali/Desktop/burp/**
		java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:/home/kali/Desktop/burp/loader.jar -noverify -jar /home/kali/Desktop/burp/burpsuite_pro_v2022.1.jar &
	----------------------------------------------
	**3. Use keygen.jar to generate the License key**
		java -jar keygen.jar
	----------------------------------------------
	**4. Activate Burp Suite Pro**
		1. Modify License String like "license to 
    3r"
		2. Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
		3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
		4. Copy License Request from BurpSuite_Pro and paste in keygen.jar
		5. Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
	----------------------------------------------
	**5.1 For Windows Follow These Steps**
		1. Open Notepad and Paste command at 2.1 and save the file with name burp.bat in C:\Users\hackwithsumit\Desktop\burp\   Folder.
		2. Open another Notepad and Paste below command and save it with burp.VBS extension in Desktop.
			Set WshShell = CreateObject("WScript.Shell")
			WshShell.Run chr(34) & "C:\Users\hackwithsumit/Desktop\burp\burp.bat" & Chr(34), 0
			Set WshShell = Nothing
	**5.2 For Linux Follow these Steps**
		1. With Sudo Permissions, Create a file with command "gedit /bin/burp"
		2. Paste command in text editor "java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:/home/kali/Desktop/burp/loader.jar -noverify -jar /home/kali/Desktop/burp/burpsuite_pro_v2022.1.jar &"
		3. Change Permissions for files with command "chmod +x /bin/burp"
	----------------------------------------------
	**6.1 For Executing Burp in Windows, Double Click on burp.VBS file.**
	**6.2 For Executing Burp in Linux, Write burp in Terminal and press Enter.**


POC for Windows : https://youtu.be/GuNiH1VUCGU


