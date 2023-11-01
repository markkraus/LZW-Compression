# LZW.java
- Array & Trie Codebooks<br>
- Standard input/output reading/writing<br>
- Dynamic dictionary resetting<br>

## Project Documentation
https://github.com/cs1501-2241/cs1501-assignment3-markkraus

# How to Run
Test Video: https://drive.google.com/file/d/1XxCaa66we6f-rlOttleZXo2lv7mvpq9L/view?usp=sharing<br>
javac *.java<br>
To Compress without a dictionary reset: java LZW - n < _test file.type_ > _test file.type_.lzw <br>
To compress with a dictionary reset:    java LZW - n < _test file.type_ > _test file.type_.lzw <br>
To expand the compressed file:          java LZW + < _test file.type_.lzw > _test file.type_.rec <br>
