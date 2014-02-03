
Vi
========

 | **What is Vi?**
 |
 | Vi is a visual text editor. It is not a word processor.
 | Vi lets you add, change, and delete text, but does not provide such formatting capabilities as centering lines or indenting paragraphs.
 |
 |
 | **What is vim?**
 |
 | Vim is older version of vi.
 |
 | 
 | **How to open a vi file?**
 |
 | Command to open a vi file with cursor in the first line:
 |    *$vi <filename>* 
 | Command to open a vi file with cursor in the last line:
 |    *$vi + <filename>*
 | Command to open a vi file with cursor in n line:
 |    *$vi +n <filename>*
 | where file could be of any extention.
 | If it is a new file, then it will be empty. If it is an old file, then it will show existing contents.
 |
 |
 |
 | **Modes of Vi**
 | 
 | *Command Mode* : 
 |    Letters of keyboard we type perform editing functions. To enter command mode, press the escape <Esc> key.
 | *Insert Mode*  : 
 |    Letters of keyboard we type form words and sentences.
 |
 |
 |
 | **Basic commands of vi**
 | *(! indicates negative form)*
 | 
 | *Press i*
 |         To type anything in the file.
 | *Press a*   
 |         To append (or enter) any text from current cursor position.
 | *Type :w*
 |         To save the file.
 | *Type :q*
 |         To exit if the file remains unchanged.
 | *Type :q!*
 |         To exit without saving.
 | *Type :x or :wq*
 |         To save and exit.
 | *Type :e!*
 |         To not save and go back to last saved version.
 | *Type :set nu*
 |         To set line number mode.
 | *Type :set nu!* 
 |         To remove line number mode.
 | *Type :<linenumber>*
 |         To go to a particular line number.
 | *Press r*       
 |         To replace current character with a new one, press r, then new character.
 | *Press x*      
 |         To delete a character.
 | *Press cw*      
 |         To change a word.
 | *Press C or c$*   
 |         To end line at that cursor point and delete everything after that.
 | *Press c0*      
 |         To bring cursor to the beginning of line and delete everything in the line before it.
 | *Press cc*      
 |         To change a whole line.
 | *Press d*       
 |         To delete.
 | *Press dw*      
 |         To delete a word.
 | *Press dd*      
 |         To delete a line.
 | *Press D or d$*    
 |         To delete upto end of line.
 | *Press d0*      
 |         To delete upto beginning of line.
 | *Press dd*    
 |         To delete a line.
 | *Press D or d$*    
 |         To delete upto end of line.
 | *Press d0*      
 |         To delete upto beginning of line.
 | *Press u*       
 |         To undo.
 | *Press Ctrl+r*  
 |         To redo.
 | *Press x*       
 |         To cut a character.
 | *Press y*       
 |         To copy a character.
 | *Press yw*      
 |         To copy a word.
 | *Press yy*      
 |         To copy a line.
 | *Press p*       
 |         To paste.
 | *Press ~*       
 |         To change case of letter.
 | *Press o*       
 |         To add a new line below this line.
 | *Press O*       
 |         To add a new line above this line.
 | *Press J*       
 |         To join the current line and next line.
 |
 |
 |
 | **To move around in vi file**
 |
 | *Press k*  
 |         To move one char up.
 | *Press j*
 |         To move on char down.
 | *Press h*
 |         To move one char left.
 | *Press l*  
 |         To move one char right.
 | *Press w*
 |         To move forward word by word.
 | *Press b*  
 |         To move backwards word by word.
 | *Press o*
 |         To move to beginning of line.
 | *Press $*  
 |         To move to end of line.
 | *Press c*  
 |         To move to end of word.
 | *Press G*  
 |         To go to last line.
 | *Press <linenumber>G*
 |         To go to a particular line.
 | *Press Ctrl + F* 
 |         To move forward one screen.
 | *Press Ctrl + B* 
 |         To move backwards one screen.
 | *Press Ctrl + D* 
 |         To move forward half screen.
 | *Press Ctrl + U* 
 |         To move backwards half screen.
 | *Press +*  
 |         To move to first character of next line.
 | *Press -*  
 |         To move to first character of last line.
 | *Press e*
 |         To move to end of word.
 |
 |
 |
 | **To search a word in vi file**
 | *(Stay in the same line in which you want to search the word)*
 | 
 | *Type /searchword*
 |         To search any specific text in forward content.
 | *Type ?searchword* 
 |         To search any specific text in backwards content.
 | *Press n/"/"*
 |         To go to next occurence.
 | *Press N/?*                    
 |         To go to previous occurence.
 | *Type :s/oldword/newword*
 |          To search a word and replace first occurence.
 | *Type :s/oldword/newword/g*      
 |          To search a word and replace all occurence in same line.
 | *Type :l,$s/oldword/newword*
 |          To search a word and replace all occurence in all the lines.
 | *Type :%s/oldstring/newstring/g*    
 |          To search a word and replace all occurence in all the lines.
 | *Type :%s/oldstring/newstring/gc*
 |          To search a word and replace all occurence in all the lines but confirming it first
 |
 |

