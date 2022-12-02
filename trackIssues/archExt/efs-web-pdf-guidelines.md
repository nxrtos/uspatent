# EFS-Web PDF Guidelines

[uspto.gov](https://www.uspto.gov/patents/apply/applying-online/efs-web-pdf-guidelines#)

------

## **PDF Guidelines**

The USPTO will be receiving electronic patent application documents in the  Adobe PDF (Portable Document Format) format, from which images will be  produced for the Image File Wrapper (IFW) system. Because the PDF format is so feature-rich, a standard is required to restrict submitted  content to what the United States Patent Office is prepared to receive.  The following guidelines set forth in this document will help to ensure  that the created PDF documents meet the requirements for processing at  the USPTO.

The following guidelines are based in part on the PDF/A specification; a document conforming to PDF/A will meet the  requirements of EFS Web for submission to the USPTO.

## **Document Formatting**

The page size should be either 21.0 cm by 29.7 cm (DIN size A4) or 21.6 cm  by 27.9 cm (8.5 by 11 inches). Pages of a larger size will be reduced to 8.5 by 11 inches, which may affect readability of the document and/or  distort any attached image.

## **PDF Version**

The PDF document must conform to any one of versions 1.1 through 1.6 of the Adobe PDF specification. These are the versions supported by the USPTO  reference viewer (Adobe Acrobat Reader version 7.0 or higher). This  document will be revised to indicate support for any future versions of  PDF. A review of the to-be-filed document(s) is strongly recommended  before submission.

## **Fonts**

All characters  (glyphs) that make up the text of the document must be embedded.  Embedding allows the fonts used in the creation of a document to travel  with that document, ensuring that a user sees documents exactly as the  designer intended them to be seen. Embedded fonts may be limited to a  subset containing the glyphs necessary to render the document. All fonts embedded within the document must be licensed and legally embeddable.

## **Color Text**

It is recommended that the text of the document be black. Text of other  colors may not convert to image properly, resulting in unreadable or  invisible text.

## **Images**

Bi-tonal (black and white), color, or grayscale images should be scanned at a minimum resolution of 300 DPI.

It is recommended to use images saved in a lossless format (e.g., TIFF,  PNG, GIF, BMP). It is strongly recommended that the PDF creation  software does not downsample images during the PDF creation process, as  this could degrade the quality of the image. For color and grayscale  images, it is recommended that no compression be used; CCITT Group IV  compression is recommended for bi-tonal images.

The use of  Alternates (a feature within PDF that allows for alternate images to be  used for on-screen rendering and printing) is prohibited.

Images  consisting of multiple layers must be flattened before embedding into  the PDF document. The properties of all layers should be marked as  "visible" before flattening. This ensures that the complete image is  visible to the examiner.

## **Layers**

PDF  documents with multiple layers must be flattened prior to submission to  ensure that the complete document is available to the examiner. If a  document contains layers that are marked as "invisible", the invisible  layers will be lost when the received document is processed within the  USPTO. Documents submitted with multiple layers will be flattened by the USPTO when converted to an image.

## **Object Content**

Content that cannot render (be viewed) directly or completely to a printed  page, including: multimedia (e.g., sound, video, animations,  slideshows), 3-dimensional models (e.g., CAD drawings), file  attachments, multi-page objects (e.g., Microsoft Excel spreadsheets,  multi-page TIFF images), and commenting/reviewing features  (highlighting, annotations, comments, notes, and the like) are  prohibited.

There must be no dependencies on external files or resources of any type in order to render the attached image.

## **Security Features**

Password protection and encryption are prohibited. Documents that are protected  in this manner will not pass validation, thus will not be submitted.  When files are submitted through EFS Web, the SSL v3 / TLS v1 protocol  within the TruePass security application will provide the needed  security and protection.

## **Embedded Code/Viruses**

The PDF document must be free of executables, worms, viruses, or any type  of potentially malicious content. Any files that found to have potential malicious content will be deleted.

## **JobOptions File**

Most PDF creation tools have the ability to create a customized job option  file that configures the print driver to use certain printing settings.  This can be used for the user's specification for creating PDF print  jobs that are used frequently but are not the standard. It allows users  to create PDF files that meet the USPTO guidelines. This joboptions file may not work with other PDF creation tools.  

 \>> See [EFS-Web Resources](https://www.uspto.gov/patents/apply/applying-online/efs-web-guidance-and-resources) to download the JobOptions file and for usage instructions

Read " [Files that can be submitted](https://www.uspto.gov/patents/apply/applying-online/files-be-submitted-naming-pdf-files) " for instructions on allowed file types and file naming requirements.

​          