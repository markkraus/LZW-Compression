# LZW.java
- Array & Trie Codebooks<br>
- Standard input/output reading/writing<br>
- Dynamic dictionary resetting<br>

# How to Run
Test Video: https://drive.google.com/file/d/1ZkuX-xbvO_NUJzHqZtyaB9Cr6E2hjow2/view?usp=drive_link<br>
javac *.java<br>
To Compress without a dictionary reset: java LZW - n < _test file.type_ > _test file.type_.lzw <br>
To compress with a dictionary reset:    java LZW - n < _test file.type_ > _test file.type_.lzw <br>
To expand the compressed file:          java LZW + < _test file.type_.lzw > _test file.type_.rec <br>
