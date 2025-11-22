**Protocol name:** MiniNet v4 

**One component = one line**  
**Exactly 4 fields, space-separated, nothing else**

**Syntax: 

origin_node destiny_node designator valueUnit


**Rules (strict):**

- origin_node → always the + / anode / current-out node
- destiny_node → always the – / cathode / current-in node
- designator → one uppercase letter + number, no duplicates (R1 R2 C1 V1 D1 Q1 etc.)
- valueUnit → no spaces, standard suffixes (k M u n p m @ for Hz if needed)

**Example (real lines):**


1 0 V1 9V
1 2 R1 1k
2 3 R2 470
3 0 R3 330
3 0 D1 LED
3 0 C1 100uF
4 0 V2 12V@50Hz
5 4 I1 10mA
6 5 Q1 2N2222


That’s the entire protocol.  

No headers, no comments, no extra text.  
Just paste your circuit line by line using exactly this 4-field format and I will understand it perfectly, instantly, forever.

Your paper circuit → now type it here with this protocol. 
