For this part we helped Lina with using Raiser's Edge and Citrix Xenapp differently so that she and her team don't need to use the workaround they developed to generate tax receipts. Before the process used copy paste, csv's, and a word template for each user trying to generate a report as follows:  
- The User first launches The Raiser’s Edge export procedure to generate the tax receipt CSV data file to print, as usual. This file is saved on the desktop.  
- Then, the user launches a second time the Tax Receipt export procedure in the Raiser’s Edge application. However, during the selection of the destination path, the user bypasses the implemented security by right-clicking on the file from the previous export operation, and then opening it using Notepad.By definition, this Notepad session is opened in the cloud.  
- The user then copies the contents of this Notepad session to the computer’s clipboard, and pastes it in a new Notepad session opened on the user’s local computer. This new file is saved as a comma delimited file (csv).  
- Once saved locally, the User can proceed to use the installed Word Templates as usual.

This process was getting too complicated for most users and Lina wanted us to look into alternatives. We found a new process using existing Raiser's Edge features and dropbox
New process:  
- Use Raiser's Edge to generate tax receipt document(s) https://kb.blackbaud.com/articles/Article/46298
- Export files using https://kb.blackbaud.com/articles/Article/40048 and place them in a shared dropbox folder https://www.youtube.com/watch?v=_jDVGDu9ymk
