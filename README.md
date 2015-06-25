# SU2C_pancreatic_cancer
 Designed and developed by Patrick Leyshock (leyshock@ohsu.edu) And Jacob Bieker (jacob@bieker.us)

 Script consolidates multiple .xls files (generated by Aperio image-analysis software) into one .xlsx workbook
   Input to script is multiple .xls files.  There is one .xls file per slide, ith one or more rows, each row
     corresponding to a region selected in the image

   Output is a single .xlsx worksheet
 Assumptions:
   1.  script is located in same directory as input files
   3.  input .xls files follow this naming convention:

             mouse_NN_slide_MM_stain_MM.xls

       so for mouse 3, slide 2, stain 5, the file name should be:

             mouse_3_slide_2_stain_5.xls

       Note that the delimitator between each component of the file name can be 
       any of the following: "_"
       
       Other valid names include:
       
       _3__2__5.xls