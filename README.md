# 3DAMLCustomNeRFs
Take one object of your choosing and make a NeRF of it! You are going to be using the Instant-NGP implementation by NVIDIA. (2 - 5 hours)


https://user-images.githubusercontent.com/56688374/185812207-7283efac-86ca-4f25-8667-5cdf58ac48dc.mp4

## Part 1:  Get Instant-NGP up and running (1 Point)
  1. git clone https://github.com/NVlabs/instant-ngp
  2. Folow the installation instructions of Instant-NGP, Vulkan and OptiX are optional but there is no point in installing OptiX
  3. Scroll down to the NeRF Fox experiment and run it.
  4. Create your own camera path and render a video of your NeRF (5 seconds video at 30 fps), follow steps in https://youtu.be/8GbENSmdVeE?t=374 for reference
  5. Save the resulting video, this is whats worth 1 point.
  
## Part 2:  make your own NeRF (3 Points)
  1. Installing COLMAP, Follow instructions at https://colmap.github.io/install.html
  INPORTANT: COLMAP may complain for a variety of reasons whenever you try installing it,sometimes even having an active conda envirornment may be source of the problem. This issue discussion may be usefull : https://github.com/colmap/colmap/issues/188
  2. Install ffmpeg : https://www.tecmint.com/install-ffmpeg-in-linux/
  3. Take at least 30 pictures (50 for better results) or a short video of the object your desire. Remember that the more pictures or the more frames extracted from the video as well as the sparsity of them will lead to better results! (all pictures or the video trajectory should be around the same distance to the center of the object)
  4. Follow intructions in https://github.com/NVlabs/instant-ngp/blob/master/docs/nerf_dataset_tips.md#preparing-new-nerf-datasets
    NOTE: https://youtu.be/8GbENSmdVeE?t=104 Is a very good reference of what youre trying to do.
  6. Once your own NeRF is running, create a camera path and render a video of your NeRF (8 second video at 30 fps), 
  7. Deliver your outputted .mp4 video and data folder containing: base.msgpack, base_cam.json, colmap.db, colmap_sparse, colmap_text, images, transforms.json
  
## Part 3: answer questionaire (1 Point)

http://form-timer.com/start/bbcfc887

