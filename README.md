# Dataedo
Junior c# developer zadanie

1. Program.cs
   1. Input file name repaired according to file name
2. DataReader.cs
   1. Adding validation while importing data from Input file to List object to avoid empty lines
   2. Loop, responsible for creating importedObject, is improved by changing starting position from 0 to 1, to skip headers.
   3. Try catch block added in loop where each of properties in importedObject is assigned from input file.
   4. Try catch block added in loop where correction of imported data is realized.
   5. If condition added, which is responsible for checking wheather current line has DataType(eventually only lines, which have pointed Database, meet this condition).
   6. Increment improved in loop, responsible for assigning number of children to imported objects.
   7. A few conditions are fixed in loop, responsible for displaying data. Verification by ParentType property is added to avoid those lines, which do not have ParentType provided. 
