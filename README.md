# background
from rembg import remove
from PIL import Image
input_path='C:\\Users\\hp\\Downloads\\mink-mingle-96JD67agngE-unsplash.jpg"'
output_path='C:\\Users\hp\\Downloads\\sodapdf-converted.png'
input=Image.open(input_path)
output=remove(input)
output.save(output_path)
