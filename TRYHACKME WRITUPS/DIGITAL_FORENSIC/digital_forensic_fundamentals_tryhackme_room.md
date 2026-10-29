The branch of forensics that investigates cyber crimes is known as digital forensics.
Digital Forensic Methodologyy is Collection->Examination->Analysis->Reporting
Different Examples of digital forensics are like Disk Forensic,........................

Write Blockers are used to ensure the data integrity of the collected data and they are available in physical and digital type.
Chain of custody contains all the collected information

WINDOWS FORENSIC
Memory image contains the data inside the operating systems RAM.
DATA image contains the data present on the storage device of the system

If someone have a digital data temperoy used and switch off the laptop,the memory image can be recovered before restarting the system again and is of big use

FTK Imager: FTK Imager is a widely used tool for taking disk images of Windows operating systems. It offers a user-friendly graphical interface for creating the image in various formats. This tool can also analyze the contents of a disk image. It can be used for both acquisition and analysis purposes.

THERE ARE TWO COOL TOOLS FOR META DATA TAKING .
PDFINFO AND EXIFTOOL
Let’s see what we can learn from the PDF file. We can try to read the metadata using the program pdfinfo. Pdfinfo displays various metadata related to a PDF file, such as title, subject, author, creator, and creation date. (The AttackBox already has pdfinfo installed; however, if you are using Kali Linux and don’t have pdfinfo installed, you can install it using sudo apt install poppler-utils.) 
Photo EXIF Data
EXIF stands for Exchangeable Image File Format; it is a standard for saving metadata to image files. Whenever you take a photo with your smartphone or with your digital camera, plenty of information gets embedded in the image. The following are examples of metadata that can be found in the original digital images:

Camera model / Smartphone model
Date and time of image capture
Photo settings such as focal length, aperture, shutter speed, and ISO settings
Because smartphones are equipped with a GPS sensor, finding GPS coordinates embedded in the image is highly probable. The GPS coordinates, i.e., latitude and longitude, would generally show the place where the photo was taken.

There are many online and offline tools to read the EXIF data from images. One command-line tool is exiftool. ExifTool is used to read and write metadata in various file types, such as JPEG images. The AttackBox already has exiftool installed; however, if you are using Kali Linux and don’t have exiftool installed, you can install it using sudo apt install libimage-exiftool-perl. 

THIS ROOM WAS COOL AND TAUGHT ON DIGITAL FORENSIC AND ANALYSING OF META DATA.NEED TO CHECK MORE ON OTHER ROOMS
