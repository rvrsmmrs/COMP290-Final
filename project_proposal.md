# Project Proposal

❓ What type of project will you work on? Will it be a web app, mobile app, or something else?  What will your project do?

🅰️ I will create a convolutional neural network to locate ecDNA in medical images. Extrachromosomal DNA, or ecDNA, are small ringlets of DNA that form independent from a chromosome. Large quantities of these ringlets is linked with certain types of cancers. For this reason, it can be important to moniter their numbers. The current method requires a trained individual to count the number of ecDNA ringlets from images, a process that usually takes several hours (depending on the image size). Consequently, this limits the data that can be collected, and slows down the process of researching ecDNA. I am working extracurricularly with several other UNC students on a similar task, but the work I produce for this project will be entirely my own. The final product will likely not involve a web app, but rather a program that can be downloaded and run from the command line. The user will input an image and the program will output an image with the location of each ring of ecDNA marked with a dot.

❓ Why did you choose to work on this project? What motivates you to choose this topic?

🅰️ As mentioned earlier, I am working with other students in the AI Club at UNC to improve an existing model that counts the number of ecDNA ringlets in an image. However, I want to build my own model that finds the location, not the number, of ecDNA. I hope to improve my knowledge of PyTorch and Numpy through this project, and gain a better understanding of convolutional neural network architecture. I am deeply interested in medicine, and I want to explore how computer science and deep learning methods can improve our understanding of biology. This project will help me learn about computational pathology methods, and better equip me to work on other projects. Eventually, I hope that a ecDNA detecter can become accurate enough for medical use. This project will be incredibly challenging (as someone with about 2 months of PyTorch experience), but its a challenge that I am excited to tackle. 

❓ What problem does your project hope to tackle? How will your final product help to solve this problem? How will the target audience you specified above benefit from your app?

🅰️ Counting ecDNA is a process that currently requires many man-hours of work per image, which is a major barrier to ecDNA research. If an accurate model could be constructed to perform this task, researchers could improve their studies by collecting and analysizing much more data. This could be crucial given the relationships between ecDNA and cancerous tumors. Research suggests that cancer cells contain much more ecDNA than regular cells, which may help cancers adapt and become resistant to medication ([source](https://www.cancergrandchallenges.org/challenges/active-challenges/extrachromosomal-dna#:~:text=New%20research%20has%20revealed%20that,and%20become%20resistant%20to%20treatment.)). I hope that AI-assisted research could help us better understand or predict certain kinds of cancers. I am going to explore and architecture that is different from the others in my group, which I hope provides insight into improving these models. Specifically, I will use a U-net to abstract elements from the original image, and then produce an output of the same dimensions of the input image.

## Tools and Languages

The entire project will be written in Python 3, whose documentation can be found here: https://docs.python.org/3/

The libraries I plan to use and their documentation is listed below.

- Pytorch: https://pytorch.org/docs/stable/index.html
- Numpy: https://numpy.org/devdocs/reference/index.html#reference
- Pyplot: https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html



