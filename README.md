{\rtf1\ansi\ansicpg1251\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .AppleSystemUIFontMonospaced-Regular;\f1\fnil\fcharset0 .SFNS-Regular;}
{\colortbl;\red255\green255\blue255;\red14\green14\blue14;\red155\green162\blue177;}
{\*\expandedcolortbl;;\cssrgb\c6700\c6700\c6700;\cssrgb\c67059\c69804\c74902;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f0\fs32 \cf2 # \uc0\u55358 \u56598  RPA Challenge Bot (PIX)\
\
This project contains an RPA bot built using the [PIX RPA platform](https://pixrpa.ru/).  \
It is designed to complete the [rpachallenge.com](https://www.rpachallenge.com/) task as part of a test assignment.\
\
---\
\
## \uc0\u55358 \u56809  Project Structure\
```\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f1 \cf2 pix-project/\
\uc0\u9500 \u9472 \u9472  Main.pixproj                   # Entry point script\
\uc0\u9500 \u9472 \u9472  Framework/\
\uc0\u9474    \u9500 \u9472 \u9472  ReadConfig.pixproj         # Configuration reader\
\uc0\u9474    \u9492 \u9472 \u9472  WebsiteAutomation.pixproj  # Interaction with the website\
\uc0\u9500 \u9472 \u9472  assets/\
\uc0\u9474    \u9492 \u9472 \u9472  config.xlsx                # Configuration file\
```\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f0\fs30 \cf3 ---\
\
## \uc0\u9881 \u65039  Functionality\
\
- Loads configuration parameters from external file\
- Launches `rpachallenge.com` and fills out web forms\
- Follows best practices in modular RPA architecture\
\
---\
\
## \uc0\u55357 \u56550  Platform\
\
- **RPA Platform**: PIX\
- **Format**: `.pixproj` project files\
- **OS**: Windows (tested)\
\
---\
\
## \uc0\u55357 \u56541  Notes\
\
This project was developed as part of a test task to demonstrate the ability to automate web-based processes using PIX RPA.\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f1\fs32 \cf2 \
\
}