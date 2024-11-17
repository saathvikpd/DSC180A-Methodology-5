### Saathvik Dirisala
#### Email: sdirisala@ucsd.edu
#### Section: A15
#### Mentors: Dr. Rayan Saab and Dr. Alex Cloninger

#### Responses:

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic in my domain, "Neural Network Compression," has been GPTQ, an efficient method for quantizing LLMs. This method employs the Hessian of each layer to quantize weights one at a time. The loss incurred from quantizing a single weight is redistributed amongst the remaining weights. This is a powerful method that enables 4-bit quantization of LLMs with minimal loss in performance/information.


**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

An investigation I would like to pursue for my Quarter 2 project is applying the GPTQ algorithm to Convolutional Layers and experiment with mixed-precision quantization for image classification tasks.


**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A change I would make to my current Quarter 1 Project would be to focus not just on a single algorithm (GPTQ) and explore other cutting-edge 4-bit quantization techniques, like GPFQ. Furthermore, I would like to expand my implementations to more large-scale models, since I have only been experimenting with toy models.


**4. What other techniques would you be interested in using in your project?**

Some techniques I am curious to use in my project are:
- Mixed-precision quantization
- Convolutional layer quantization
- Transfer Learning, combined with Quantization-Aware Training, to observe performance boosts on ImageNet subtasks.
