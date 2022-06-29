先创建info3.txt 包含自己的id和name
使用以下语句将info3.txt隐藏在input.png中获得test.png
python3 LSB-Steganography/LSBSteg.py encode -i input.png -o test.png -f info3.txt 
使用以下语句获得info3.txt的信息
python3 LSB-Steganography/LSBSteg.py decode -i test.png -o info3_get.txt 
