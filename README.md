# Bonding_Quotient
A new similarity measure to discover underlying patterns in the dataset
Each RGB image is represented as 256 * 3 = 768 dimensional vector in terms of frequency distribution of each pixel in the
range 0-255. Color images are preferred as it provides 3X more information than B&W. It is then normalized with the size of 
the image making all images comparable like for like. In a sense RGB value of each pixel is treated as visual alphabet and 
its frequency distribution provides similar representational value as word frequency does for a document. In both instances, 
`bag of words` is used not their relative locational properties. But even without using the latter, it often does good job
of classification.
