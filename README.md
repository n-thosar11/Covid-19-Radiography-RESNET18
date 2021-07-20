# Covid-19-Radiography-RESNET18

# How Accurate is Chest Imaging for Diagnosing COVID-19?

![](https://www.iaea.org/sites/default/files/styles/third_page_width_portrait_2_3/public/chestxray.png?itok=z07bhz5h&c=b64d5f5d9a54f1cfd815edc18198844a)

* People with suspected COVID-19 need to know quickly whether they are infected, so they can receive appropriate treatment, self-isolate, and inform close contacts.
* Currently, a formal diagnosis of COVID-19 requires a laboratory test (RT-PCR) of nose and throat samples. RT-PCR requires specialist equipment and takes at least 24 hours to produce a result. It is not completely accurate, and may require a second RT-PCR or a different test to confirm diagnosis.
* COVID-19 is a respiratory disease. Clinicians may use chest imaging to diagnose people who have COVID-19 symptoms, while awaiting RT-PCR results or when RT-PCR results are negative, and the person has COVID-19 symptoms.

#### We wanted to know whether chest imaging is accurate enough to diagnose COVID-19 in people with suspected infection.

Here we will use the RESNET model for the classification of the X-Rays. We will use Transfer Learning, and get the pretrained model from torchvision Library in python. 

ResNet, short for Residual Networks is a classic neural network used as a backbone for many computer vision tasks. This model was the winner of ImageNet challenge in 2015. The fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully.
