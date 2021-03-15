# Memristors-MNIST

## Running the code
1. Clone [this](https://github.com/Tioz90/Memristor-Nengo) repository for the library code
2. Run the experiments:
    * ``mnist.py`` runs unsupervised MNIST classification using Oja or mOja (memristor-Oja).  Highest accuracy was measured to be 70% with 20.000 input samples and 20 excitatory neurons.
    * ``mOja_test.py`` uses mOja to teach recurrently-connected neurons to sustain firing
