code.rar file contains code and data for the main figures in the manuscript "Understanding the onset of hot streaks across artistic, cultural, and scientific careers". 

Jupyter notebook (ipynb filetype, Python version 3.6) include guidance on installing specific packages. Python and jupyter notebook can be installed following the link: https://docs.anaconda.com/anaconda/install/. 

Installation should take few minutes on a normal computer.

This rar file contains 6 jupyter notebooks. 

Code 1: Python program to apply VGGNet on art images.
Code 2: Python program to apply text embedding to plots and deepwalk to cocasting network
Code 3: Python program to apply community detection and neural network to co-citation network of scientific publications
Code 4: Python program to measure exploration and exploitation from art embedding space
Code 5: Python program to measure exploration and exploitation from film embedding space
Code 6: Python program to measure exploration and exploitation from co-citing network

The running time of model training and embedding extraction in the scripts 1-3 is expected to last several hours. The running time of each plot in the scripts 4-6 is expected to last for a few minutes. 

=============

data.rar file contains data for the main figures in the manuscript "Understanding the onset of hot streaks across artistic, cultural, and scientific careers". 

This rar file contains 3 folders.

art folder: career prodifes (auction record and images for each indivudal) 
movie folder: career profiles (IMDB movie list for each indiviudal), movie cast data
science folder: career profiles (google scholar id and WoS paper id for each indiviudal), paper subject id to train 64D paper vector, and team size of each paper

Due to the github file size limitation, files/folders larger than 100MB can be downloaded from the following links  

tokenized movie plots (448MB): a pickle file, dictionary whose key is the movie id and the value is a list of tokens
- https://www.dropbox.com/s/kjpae6f7zwykooc/m2clean_word.p?dl=0

edgelist for co-citing network (1.6G): a compressed txt file, each row denotes the link between two papers and their weights 
- https://www.dropbox.com/s/7lwdgrmh3rvntxk/reference_edgelist_authors.txt.bz2?dl=0

artnet images (11.8G): a compressed folder, images within each artist subfolder 
- https://www.dropbox.com/s/bb5fol2c5f77pel/artnet_images.tar.gz?dl=0

ark500K images (56.6G): a compressed folder, images within each artist subfolder
- https://deepart.ust.hk/ART500K/art500k.html (Raw images of visual arts with general label list) 







