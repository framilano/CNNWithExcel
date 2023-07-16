# CNNWithExcel
An example of basic Convolutional Neural Network theory applied with Excel.
Learned during ACloudGuru courses!

https://github.com/framilano/CNNWithExcel/assets/28491164/06816b79-4d96-4f3a-8b9c-b8574ee474f5

# Objective
Using [Convolution Neural Networks (CNN)](https://en.wikipedia.org/wiki/Convolutional_neural_network) concepts to recognize line patterns based on filters (slash, backslash, vertical and horizontal lines).

# How

The drawing field is a 6x6 square, every filter has its own 6x6 square where every single cell is the SUM of PRODUCTS between the filter square (2x2) and a 2x2 sector inside the drawing field.

![immagine](https://github.com/framilano/CNNWithExcel/assets/28491164/1e286424-b0cb-417b-8122-b65fabdec7cd)

If the pattern has been recognized (like a DASH) the SUM of PRODUCTS between the two matrixes is 2, whenever a 2 is evaluated  it means the filter is valid and the "The is line is a Dash" String is print.

![immagine](https://github.com/framilano/CNNWithExcel/assets/28491164/be9f3573-4bb9-4bc3-b9e7-078e193420eb)
