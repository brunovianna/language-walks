# language-walks
Walks around latent space prompts in n-sphere

## Instructions
Open the notebooks in Google Colab. Connect to a machine with GPU. The parameters are hard coded:

num_points = 4 #number of points in the n-sphere, images to be generated
seed = 10000002 #start seed. the batch size will increment the seed ( if seed = 17 and batch size =3, the final seeds will be 17,18,19)
num_steps=25 #steps generating the image
batch_size = 4 #amount of different seeds with the same vector
sphere_radius = 5 #distance from the original prompt vector
prompt = "talo" #orginal prompt used for center of the n-sphere
