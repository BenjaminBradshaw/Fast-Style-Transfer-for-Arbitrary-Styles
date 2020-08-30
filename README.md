# Batch processing to video for Fast Style Transfer for Arbitrary Styles

Using the model code in magenta: https://github.com/tensorflow/magenta/tree/master/magenta/models/arbitrary_image_stylization

From the TensorFlow Hub: https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2

and the publication:
    Exploring the structure of a real-time, arbitrary neural artistic stylization network. Golnaz Ghiasi, Honglak Lee, Manjunath Kudlur, Vincent Dumoulin, Jonathon Shlens, Proceedings of the British Machine Vision Conference (BMVC), 2017.: https://arxiv.org/abs/1705.06830
    
    
### Description:
This notebook uses imageio to feed frames from videos or images from an image sequence into a Fast Style Transfer for Arbitrary Styles model and write the results to a frame in a new video.
