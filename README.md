<details>
  <summary>
  <b>[01] General & Forensics Warmups 1</b></summary>

### Part 1

```bash
# Download a image with link
wget "https://asdfasdfasd"

# Zip a png image
zip flag.zip img.png

# Unzip file
unzip flag.zip

# Show image
eog img.png
```

</details>
<details>
  <summary>
  <b>[02] General & Forensics Warmups 2</b></summary>

```bash
# File does not open
file flag.png // shows is a JPEG

# Rename to JPEG
mv flag.png flag.jpeg

# Save message to file
nano flag.txt // extensions_are_lies

# Use xclip to copy to clipboard
cat flag.txt | xclip -selection clipboard

# How you convert 0x41 from Hexadecimal what would be in ascii
pyton
>>> 0x41
65

# Create an output in python with the result

!/usr/bin/env python 
print "result(%s)" % chr(0x41)

# Make the file executable
chmod +x get_flag.py

# Copy the output to the clipboard
./get_flag.py | xclip -selection clipboard


```
  </details>