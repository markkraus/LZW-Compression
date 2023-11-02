# LZW.java
- Array & Trie Codebooks<br>
- Standard input/output reading/writing<br>
- Dynamic dictionary resetting<br>

## Project Documentation
https://github.com/cs1501-2241/cs1501-assignment3-markkraus

# How to Run
Repository Overview: https://drive.google.com/file/d/11xmrJzhLfi5_88Vdgz3temxOcEGfM-cZ/view?usp=drive_link<br>
javac *.java<br>
To Compress without a dictionary reset: java LZW - n < _test file.type_ > _test file.type_.lzw <br>
To compress with a dictionary reset:    java LZW - r < _test file.type_ > _test file.type_.lzw <br>
To expand the compressed file:          java LZW + < _test file.type_.lzw > _test file.type_.rec <br>
