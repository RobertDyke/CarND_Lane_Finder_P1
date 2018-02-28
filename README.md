# CarND_Lane_Finder_P1
Project 1 CarND class
   This was the first project from the Udacity Self Driving Car class. It is in Python (my first Python project) on Jupyter Notebook (another first).
   It takes in several still images of roads and identifies the lanes correctly. It also takes in a video and correctly identifies the lanes in it. Cool stuff. 

Notes on usage:

   The section "Test Matplotlib and Plotting" analyses a single image. It is read in one of the first lines of code after the import statements. 
   
   img = mping.imread('YOUR_IMAGE.jpg')
   
   This same image is used to Test OpenCV in the next cell.
   The following cell tests that TensorFlow is loaded and working. If it is working it will output '1 + 2 = 3'
   Lastly a movie of road travel is analysed. It is one of the first lines after importing VideoFileClip.
   
   test_clip = VideoFileClip('YOUR_INPUT_FILM.mp4')
   
   The output film is made here:
   
   new_clip_output = 'YOUR_MOVIE.mp4'
