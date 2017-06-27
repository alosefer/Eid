<h1 align="center">
	<img width="400" src="https://raw.github.com/alosefer/Eid/master/Geeks_Eid.png" alt="Geeks Eid Mubarak">
	<br>
</h1>

<p align="center">
	<b>🎉 كل عام وانتم بخير - نسخة التقنيين 🎉 </b>
		<br><br>
	<b>🎊 Geeks Eid Mubarak 🎊</b>
</p>



## What it's about?
<b>
ملف تفاعلي للإضافة من الجميع أكواد وأوامر خاصة من البرمجة، التقنية، الأمن، التصميم... للتهنئة بالعيد ♥ ابدع بأفكارك 💡 ولايوجد حدود للإبداع 🙏
</b>
<br> <br>

## How to contribute 🤔?
<b>
شرح فيديو كيفية الاضافة معنا بشكل سهل 👋 ننتظر مشاركاتكم الابداااعية
</b><br>
https://www.periscope.tv/w/1eaJbYnkopeGX


## Porgramming

- [PHP](#php)
- [KOTLIN](#kotlin)
- [C++](#c++)
- [swift](#swift)
- [Python](#python)
- [JavaScript](#javascript)
- [Java](#java)
- [Ruby](#ruby)



## Security
- [nmap](#nmap)

## Database

- [SQL](#SQL)


---

## php
```
<?php
$date = date("Y/m/d");

if ($date == "2017/06/25"){
	echo "Eid Mubarak 🎊";
} else{ 
	echo"Work Hard🤓 there is no Eid😁";
}
//Yaser @alosefer
?>
```

## c++
```

#include <iostream>
#include <Ramadan>
using namespace std;

int main() 
{
    cout << "Eid Mubarak from Oman!";
    cout<< " Do not miss to fast 6 day in Shawal"; 
    return 0;
}

```
```
#include <iostream>

using namespace std;

int main() {
	int x;
	int y;
	for(x=1;x<3;x++)
	{
	cout<<"happy eid   "<< x<<"day    ";
	}
	y=x;
	
	if(y)
  cout<<"thanks alosefer "<< "all "<< y <<" day";	
	
}
```

## kotlin
```
package Eid

fun main(args: Array<string>) {
	println("Eid Mubarak 😁")
}
```

## swift
```
var data = "2017/6/25"
 
 if data == "2017/6/25"
 {
       print("Eid Mubarak 🎉")  
 }
 else
 {
 print("Error! 🤓 there is no Eid"
 }

//@ANAS-ALMANA

```

## java
```
public class EidGreeting{

public static void main(String [] args){

Scanner enter=new Scanner(System.in);
System.out.println(" Enter today's date : ");
String date=enter.next();
		
		if(date.equals("25/6/2017")){
			System.out.println("happy Eid 😎");
		}else{
			System.out.println(" there is no Eid 😢, You have to work hrad agine):");
		}
      }
}
//@rehabalhasan
```

## python
```
print (" كل عام و انتم بخير ")
```
```
Open in CMD 
^^


db_user = "Eid Mubarak"
db_passwd = "Happy Eid"


username = input ('Say,  Eid Mubarak: ')
password = input ('Say,  Happy Eid: ')


if username == db_user and password == db_passwd:
    print ('Happy Eid')
else:
    print ('Happy Eid Too ^_^ ')
```

New Python Code
```


#Fahad Alsubaie @FahadMIT
import time
import os
MessageBeforeEid = "The Eid will coming"
today = time.strftime("%d/%m/%Y")
EidTime= "25/06/2017"
user= os.popen('whoami').read()
EidMessage = ("Happy Eid :) Mr." + '%s' %user)
if today < EidTime:
    print (MessageBeforeEid)
elif today == EidTime:
    print (EidMessage)
elif today > EidTime:
    print ('Today is ''%s'' You miss the Eid'%today)
else:
    quit()
```


## javascript
```
    <script src="https://code.jquery.com/jquery-1.8.3.min.js"></script>
    <body>
        <h1>Reverse</h1>
        <p id="list"></p>
        <p id="results"></p>
    </body>
    <script>
        var n = prompt("Enter diE yppaH");
       
        while (n.length > 0) {
            
            var ch = n.substring(n.length-1);
            $("#list").append(ch);
            n = n.substring(0,n.length-1);
            
        }
        
        $("#results");
        
    </script>
```

## ruby
```

#!/usr/bin/ruby -w

puts " Happy Eid :) ";

// @Muneera_Salah
```

## nmap
```
Yasers-MacBook-Pro:~ yaser$ nmap -sS -sV -O sun.25.06.2017
Starting Nmap 5.00 ( http://nmap.org ) at 2017-06-25 07:30 SA
Interesting ports on sun.25.06.2017:
PORT    STATE   SERVICE     VERSION
09/tcp  closed  Ramadan     May Allah Accepts your fasting and prayers
10/tcp  open    Eid         Eid Mubarak 2017
=Service Info: Device: Yaser's firewall
MAC Address: 61:6c:6f:73:65:66:65:72 (Hex_To_Text)
Aggressive OS guesses: Yaser @Alosefer Linux V 4.12-rc6
No exact OS matches for host (test conditions non-ideal).

Nmap done: 1 IP address (1 host up) scanned in 0.51 seconds
```

## SQL
```
-- phpMyAdmin SQL Dump
-- version 4.5.1
-- http://www.phpmyadmin.net
--
-- Host: 127.0.0.1
-- Generation Time: Jun 27, 2017 at 09:40 AM
-- Server version: 10.1.10-MariaDB
-- PHP Version: 7.0.4

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";

CREATE DATABASE Eid  DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci; 

CREATE TABLE `eid_notification` (
  `ID` int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
  `Eid_Name` varchar(100) NOT NULL,
  `Eid_Date` date NOT NULL,
  `Eid_Description` varchar(250) NOT NULL,
  `Eid_Message` varchar(250) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8 ;

INSERT INTO `eid_notification` 
(`ID`, `Eid_Name`, `Eid_Date`, `Eid_Description`, `Eid_Message`) 
VALUES
(1, 'عيد الفطر - Eid Al Fitr\r\n', '2017-06-25', 'بعد صيام شهر رمضان المبارك - After fasting the holy month of Ramadan', 
'Eid Mubarak - عيد مبارك');

// @Muneera_Salah

```
