# Quantum Steganography

We are **Team QPower** and this project was made as part of IBM's Creative challenge at QC Hack 2021.


## Project Idea

We have implemented Quantum Steganography using qiskit in this project.   

![q stega](qstega.png)

The idea is to encode the sender's text(secret message) using the concept of interference. The secret message is encoded based on the cover file(a text sentence in this case). An interactive working implementation is available here: [https://qc-hacks.herokuapp.com/](https://qc-hacks.herokuapp.com/). 

We have chosen our cover file and the secret message to be in text formats to make it easier for new learners to understand the concept of quantum steganography while also trying it out interactively in a console. 

## Implementation Details

The encoder circuit is based on 7 qubits but our interactive application has an option to create circuits based on the number of qubits selected and view them instantaneously.  

Here are some steps to interactively play with our application:

1. Choose the number of qubits using the slider. We would suggest that you choose 7 for the encoding and decoding scheme to work flawlessly. You can also test out other number of qubits to view the generated circuit.  

![no_of_qubits](images/no_of_qubits.png)

2. Enter the Secret message and press enter. You could try out *qiskit* as one of the test words.  

![secret_msg](images/secret_msg.png)  
Here, you can also view the generated circuit.

3. Upload a sentence where you wish to hide your message and press enter. You could try this sentence *hellooo worlddd hellooo worlddd hellooo worlddd*, a bit too dramatic to be a sentence, but it works. We are fixing our backend to support all sentence types.   
In this image, I have used *Sophisticated Superconductors* as the short sentence and it works.  


![upload sentence](images/upload_sentence.png)  

4. Click of encode to view the encoded message and then click on decode to finally view your original message.  

![encode](images/encoded_msg.png)  

![decode](images/decode.png)

You can now play around with this tool and chat with your friends using **Quantum Steganography**. Isn't it cool?



