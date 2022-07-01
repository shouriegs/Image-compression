# Image-compression
This folder contains two Jupyter Notebooks, each implementing two different ways of compressing and decompressing images. The two implementations differ in the way of subsampling of the Chrominance channels of an image. The notebook named 'GramaSrinivasShourie_A_withResize' performs subsampling using the skimage.transform.resize function. The other notebook 'GramaSrinivasShourie_B_withoutResize' performs subsampling by calculating adjacent column means of the two Chrominance channels and adds the column into one matrix. 

Both the approaches reduce the amount of storage space required for storing data of Chrominance channels.

The rest of the functioning of both the Notebooks is similar. Functions are implemented for each of the steps. 

The directory needs to changed in the second cell. Run all the cells and scroll to the bottom to check the output.

