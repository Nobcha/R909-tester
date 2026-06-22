R909-tester

Raspberry Pi Pico Zero Based DIY Test Instrument

R909-tester is a compact DIY electronic test instrument built around the Raspberry Pi Pico Zero (RP2040).
The project started as a simple continuity tester and gradually evolved into a multifunction measurement tool for the electronics workbench.

R909-testerは Raspberry Pi Pico Zero（RP2040）を利用した小型電子測定器です。
本プロジェクトは単なる測定器製作ではなく、「RP2040単体でどこまで実用的な機能を実現できるか」をテーマとしています。
________________________________________
Features
•	Continuity Tester
•	Capacitor Meter
•	Frequency Counter
•	Diode Identification
•	OLED Display
•	Rotary Encoder User Interface
All functions are integrated into a single handheld device.

Lチカから一歩進み、
•	OLED表示
•	ロータリーエンコーダ操作
•	周波数計測
•	コンデンサ測定
•	ダイオード判別
•	ステートマシン制御
などを実装した応用事例です。
________________________________________
Hardware
•	Raspberry Pi Pico Zero (RP2040)
•	SSD1306 OLED Display
•	Rotary Encoder
•	Buzzer
•	Test Terminals
The design emphasizes simplicity and low cost while remaining useful for everyday electronics experiments.
________________________________________
Software
The firmware is written using Arduino IDE.
A state-machine architecture is used to organize multiple measurement functions and simplify future expansion.
GitHub Repository:　https://github.com/Nobcha/R909-tester
________________________________________
Development Articles
Detailed development logs are available on my Hatena Blog.
•	Continuity Tester　　　 https://nobcha23.hatenablog.com/
•	Capacitor Meter　　　 
•	Frequency Counter　　 
•	State Machine Design　
•	Diode Identification　　
The project is still evolving as a practical learning platform for RP2040 development.　　 https://chitose6thplant.fc2.page/r909-tester/ ________________________________________
This project is intended as a practical RP2040 learning platform.

RP2040活用事例として継続的に機能追加を行っています。

Copyright (C) 2026 Nobuteru Asai

This project is released under GNU GPL v3.0.

Source code and design files are available from the GitHub repository.
著作権者はNobuteru Asaiであり、公開ライセンスはGPLv3です。


