# PASYDA
Synthetic Datasets for Enhancing Online Child Protection from Grooming

The PASYDA project aimed to address the challenge of generating synthetic datasets representing online interactions related to instances of online grooming. With the rise of end-to-end encryption, accessing raw text data has become increasingly difficult. Therefore, our focus was on synthesizing metadata, which remains accessible and relevant for real-world applications. The primary objective was to provide researchers with a valuable resource for refining and validating their detection models for online grooming.

The accomplish this goal, we sought to create an agent-based simulation to simulate interactions within the victim's social network. To do this, we used the Perverted Justice scenarios, as a data source of grooming cases. Next, we developed a method of generating a synthetic social network. To do this we analysed the SNAP Social Circles dataset and extracted distributions from it to inform the structure of the new network. Upon establishing the grooming scenario and generating the social network, we developed an agent-based simulation using NetLogo. This simulation populated the network with agents representing individuals and simulated their social media engagements, thereby generating a stream of interactions. These simulated messages were recorded to form our synthetic dataset.


Our data consists of 10 synthetic datasets encapsulating metadata from social media interactions centred around instances of child grooming. These datasets serve as resources for researchers seeking to evaluate and enhance their detection algorithms.
