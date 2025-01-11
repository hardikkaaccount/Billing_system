# Billing System 💸

## How to start

1. Download `Billing System.xlsm`.
2. In File Explorer, navigate to the file, right-click, select `Properties`, and at the bottom, unblock it by unticking the box.
3. Enable Developer by right-clicking on any tab in the Ribbon and selecting `Enable Developer`.
4. In the Developer tab, go to `Macros` and look for `SaveInvoiceAsPDF`. Once found, click on it and edit the code.
5. In the code, change the location where the PDF will be stored. The code will look like this:

   ```vb
   pdfPath = "J:\Abill\Bill-" & billNumber & ".pdf"
   Replace only [J:\Abill] with your desired path.

6. Done! Everything should be cool.





