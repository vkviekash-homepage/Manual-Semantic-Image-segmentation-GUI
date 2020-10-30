# Manual-Semantic-Image-segmentation-GUI

‣ This is a minor part of a bigger project with a goal to achieve automatic segmentation of fetal ultrasound images by the use of Deep Learning segmentation methods.

‣ For this purpose, we need to generate a dataset to train the segmentation model, which consists of the training pairs: input ultrasound images, segmented labels.

‣ Input ultrasound images will be provided by the medical centres, but the segmented labels are something which we have to generate.

‣ For this purpose, we proposed the idea of using a segmentation tool to manually segment images.

‣ Amira avizo-> is a tool available in the market for the same purpose. Avizo is a general-purpose commercial software application for scientific and industrial data visualization and analysis.

‣ But this tool provides a lot of extra features and also is not available as opensource but is a paid software.

‣ Thus to cut down the cost the idea of making a GUI was proposed.

Used Pytkinter and PyQt to develop 2 versions of the same tool.

This tool is not restricted to ultrasound images alone. This can be used to generate segmented labels for any semantic segmentation project.
