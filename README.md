# codeforces-problems-to-pdf
## Requirements
- pdfkit
- PyPDF2
## Install Requirements 
```shell
pip3 install pdfkit PyPDF2
sudo apt-get install wkhtmltopdf
```
## How to use
First parameter: *problem link* <br>
Second parameter: *pdf name*  **(don't miss the ".pdf")** <br>
problem-cutter.py first_param second_param
Example: <br>
```shell
 python3  problem-cutter.py  https://codeforces.com/contest/96/problem/a  1.pdf
```
## ScreenShots
![Before](https://i.imgur.com/mbeRm83.png)
![After](https://i.imgur.com/HXW3ziE.png)
