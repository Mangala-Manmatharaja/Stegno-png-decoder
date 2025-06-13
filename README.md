# 🖼️ Steganography PNG Decoder

A Python script to extract encoded text from PNG images,

### 🚀 Prepare

Clone the repository and set up the script:

    $ git clone https://github.com/s373r/steganography-png-decoder.git
    $ cd steganography-png-decoder
    $ chmod +x steganography-png-decoder.py

### 📖 Basic Usage

Check the help message for usage details:

    $ ./steganography-png-decoder.py -h

Output:

    usage: steganography-png-decoder.py [-h] file
    
    Prints PNG text sections
    
    positional arguments:
      file        📄 A PNG image
    
    optional arguments:
      -h, --help  ❓ Show this help message and exit

Example Output:

    [00000049-00000074] 📝 tEXt:
    Title PngSuite
    
    [00000075-00000135] 👤 tEXt:
    Author Willem A.J. van Schaik
    (willem@schaik.com)
    
    [00000136-00000203] ©️ tEXt:
    Copyright Copyright Willem van Schaik, Singapore 1995-96
    
    [00000204-00000466] ℹ️ tEXt:
    Description A compilation of a set of images created to test the
    various color-types of the PNG format. Included are
    black&white, color, paletted, with alpha channel, with
    transparency formats. All bit-depths allowed according
    to the spec are present.
    
    [00000467-00000535] 💻 tEXt:
    Software Created on a NeXTstation color using "pnmtopng".
    
    [00000536-00000567] ⚖️ tEXt:
    Disclaimer Freeware.
    
    Example:
    
    Extract text from a sample PNG image:

    $ ./steganography-png-decoder.py samples/tEXT-chunks.png

