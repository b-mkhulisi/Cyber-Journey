Date : 2026/06/13

Accoplishments:
Completed :
level 6 : FInd file by user,group  and size
level 7: grep command
level 8: sort and uniq
level 9: strings command
level 10: base64 encoding

key lessons:
2>/dev/null hides permission errors
strings extracts readable text from binary files
uniq -u finds unique lines
base64 is just encoding and not encryption

*Encoding - format conversion| base64, Hex, ASCII |anyone can
*Encryption- Secret | AES, RSA | Requires a key
*Hashing - not able to reverse at all   

Commands:

echo "text" |base64 | encode to base64
echo "encoded" | base64 -d | decode from base64
base64 -d file.txt | decode a file

Day 3 Complete.
