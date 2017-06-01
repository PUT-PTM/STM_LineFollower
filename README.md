# STM_LineFollower

Overview - 2-3 krótkie zdania, które mówią o czym jest projekt.
STM32 based Line Follower. Autonomous robot designed to complete specified tracks without any human intervention.

Description - bardziej rozbudowany opis projektu - z czego się składa (np. aplikacji na PC i STM32), główne moduły, metodologia wykorzystana do tworzenia.
This Line Follower was built from ground up using CooCox IDE on Windows 8.
It's main modules inclulde :
  - Mo
  - 

Tools - jakie narzędzie zostały użyte - wersje itp. Jeśli używany jest sterownik (VPC) to tutaj podać jaki, skąd pobrać. Jaki język.

Entirety of the project was coded in C with addition of STM32 Repository Libraries in CooCox IDE
  available here:www.coocox.org/software.html
Driver used for flashing program into the board is STSW-LINK009
  available here:http://www.st.com/content/st_com/en/products/embedded-software/development-tool-software/stsw-link009.html

How to run - wskazać swoją wersję release i co jest niezbędne aby ją uruchomić. Dodatkowo opisać jak używać programu.

How to compile -wystarczy skopiować ( czy niezbędne jest podjęcie jakiś specjalnych kroków, czy wystarczy skopiować?)
This code has been reviewed multiple times and is ready to be deployed. To run it on Your STM32 board simply paste it into IDE of Your choice(however please make sure that You have necessary Libraries), compile and flash onto the board.

Future improvements - co w projekcie można poprawić, czy występują bugi?
Steering algorithm is very simple and very prone to making wrong decisions.
Both engines operate on very low speed.
Program lacks easily accesible information on current direction of engine rotation.

Attributions - jeśli wykorzystano jakieś fragmenty kodu - wskazać skąd, jeśli na czymś bazowano - wskazać, jeśli grafika nie jest autorska - wskazać kto jest autorem. W projektach wykorzystujących Virtual Port Com wskazać:
https://github.com/xenovacivus/STM32DiscoveryVCP

License - podać licencję dla swojego projektu (sprawdzić czy plik LICENSE zawiera odpowiedni tekst), proponowana licencja: MIT

Credits - Adam Dębczak, Olaf Bergmann, Darek Krajewski

The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology.
Supervisor: Marek Kraft/Michał Fularz/Tomasz Mańkowski/Adam Bondyra
