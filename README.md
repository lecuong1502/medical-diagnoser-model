# medical-diagnoser-model
DEEP LEARNING CAN BE USED TO BUILD A MEDICAL DIAGNOSIS MODEL

- I build a deep learning model that will be trained on Patient's Problems which will be textual data, then my model will give the predicted Disease and will recommend Medicine to treat the patient's problem as an output.

- Application: Recurrent Neural Network (RNN). This is because we need a model that will store the information from the previous text and use it later to predict the output.

- Algorithms: Long Short-Term Memory (LSTM)
-> When dealing with textual data, such as patient symptoms, a specific type of deep learning architecture called a Long Short-Term Memory (LSTM) network is often used. LSTM networks are well-suited for tasks involving sequences of data, as they can learn long-term dependencies between elements in the sequence.

- The dataset used in this model:
    + Patient Symptoms: Textual descriptions of the patient's symptoms.
    + Diagnoses: The confirmed diseases for each patient.
    + Medications: The prescribed medications for each patient's condition.

- Framework: TensorFlow, a popular open-source library for machine learning.
- Trained on GPU GeForce RTX 4050 with epoch = 1000, batch_size = 32, accurancy (epoch = 1000) = 1, time training = 110.0078 seconds