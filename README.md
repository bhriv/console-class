# console-class
Make console.log() messages colorful and contextual for faster debugging. Focus on the console.log messages that matter first. 


Usage: Instead of using: 
    console.log('This is my message'); 
Use: 
    cc('This is my message','info'); 
where "info" is a bootstrap class, or custom style class.

Why: Easily sift through lots of console messages to target message types (i.e. Quickly identify Errors / Warnings / Success messages) for debugging.

Example Usage: send a console log message and the bootstrap class of 'success' to print a green console message: 
    cc('This is the message that will be printed in the console','success');
