# PDF::Composite
Create PDF from bulk of images & PDF documents. 

## Purpose & Usage
The perl module helps to create PDF documents from multiple images or PDF documents resides in a directory. Very first, it created for creation of software demo documentation. Where we had a manual word based document and finally producing it a PDF. Due to the lengthy manual procedure, the programmers always distanced from doing it. One fine day, we had a requirement to show a software screenshot document with a minimal time availability that never possible in our existing process.

We worked out a small pdf document creations script based on Perl module PDF::Reuse that we used earlier. We put the screen shots in a directory with sequential content based naming like ( 1_Login.pdf,2.Project_Desk.pdf). The script concated all the pdfs in the name order and kept the file name as a title of the page. It's worked that day, from there it's continiously improved based on real time usage inputs.

We hope the module helpful in smilar needs. The module available with basic usage method & we are improving documentation. 
We are welcoming usage feedbacks & suggestions.

## How to
- Make sure the availability of modules 
  -  PDF::Reuse
  -  Image::Info
## Check the samples 
  - 1_hello_pdf_bulk.pl       -> create a PDF from multiple one page pdf's
  - 2_simple_image_bulk.pl    -> create a PDF from multiple jpeg images from given directory with additional content
  - 3_simple_pdf_bulk.pl      -> create a PDF from multiple one page pdf's and content from AoA
  - 4_simple_template.pl      -> create a PDF based on template pdf & content from AoA
  - 5_simple_template_csv.pl  -> create a PDF from template pdf and content from CSV file
  - 6_demo_images.pl          -> demo pdf creation 
  - 7_demo_doc.pl             -> demo document creation for demo process
  
  - The Object Instance will take inputs from both Bulk AoH input and propoerty level set & get methods

## Directories
- lib/PDF has the library module
- screens/pdf has sample pdf's for demo
- screens/jpg has sample jpeg images for demo
- screens/frame has sample frame for demo
- screens/csv has csv data for template based demo
- pdfs -> area for storing created pdf documents

## To Do
- Elabrative Documentation
- Step by Step Samples
- Packaging for meta::cpan

## Limitations
- Presently it will take only one page from PDF inputs 
- Takes only jpeg images

## Copyright and license

Copyright: info@webstarscg.com, 2018 and later.

All source files in this package, including the documentation, are open source software under the terms of [Perl's Artistic License 2.0](http://www.perlfoundation.org/artistic_license_2_0).
