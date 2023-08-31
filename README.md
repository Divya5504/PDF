# PDF
How to convert documents to PDF

AtomSphere does not currently support PDF conversion natively, but you may be able to find a PDF utility for Java and use custom scripting to convert documents into binary PDF data.

Two popular PDF libraries to consider are Apache PDFBox and iText. This stackoverflow post compares some of PDF libraries available.

Create and deploy a Custom Library for the required jar file(s). See Working with custom libraries for details.
Upload the required jar file(s) to your Account Library.
Create a Custom Library component of type "Scripting" and reference the Account Library(ies).
Deploy the Custom Library component to your Atom.
Develop a custom script in Groovy within a Data Process Custom Scripting shape to invoke the PDF library and perform the necessary conversion steps.
