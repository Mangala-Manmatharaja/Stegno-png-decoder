# 🖼️ Steganography PNG Decoder

A Python script to extract encoded text from PNG images.

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


Example:

Extract text from a sample PNG image:

    $ ./steganography-png-decoder.py samples/tEXT-chunks.png

