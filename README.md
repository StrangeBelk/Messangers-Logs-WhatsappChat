# Messangers analytics — Logs — Whatsapp Chat

## Instructions
### STEP #1. Export neccesary chats:
1. Open Whatwapp on your phone
2. Open Required to export chat
3. Open chat menu "⠇"
4. Press "More"
5. Press "Export Chat"
6. Select "Without media"
7. Save "{chat name}.zip" file on phone
8. Transfer "{chat name}.zip" to your PC

**RESULT:** Exported chat in ZIP file and saved on your phone. 

### STEP #2. Save chats on your PC
1. Create folder in your PC
2. Copy "{chat name}.zip" to that folder
3. Extract "{chat name}.zip" to that folder
   - You could export all chats to that folder. All of them will be procedd.
  
**RESULT:** You have one folder with extractes chats as *.txt files

### STEP #3: Setup dashboard
1. Open Dashboard template
2. Extend "Transform data ˅"
3. Press "Edit parameters"
4. Input to parameters following values:
   - 92-00 PARAM - Source — path to folder with extracted chats
   - 92-01 PARAM - File name — part of the file, before chat name
5. Press "Apply changes" button

**RESULT:** Updated dashoboard with your data

## Features
Slicers:
- Exported chats
- Authors
- Date & Time

Measures:
- Number of exported chats
- Number messages

## Screenshots
![Messanger Analytic - Whatsap Chat](https://github.com/user-attachments/assets/8be3a520-1836-40a5-a879-9a52f452bfac)
