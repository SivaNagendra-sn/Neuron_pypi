
This is a Perceptron network and can be implemented with your own datasets.

Installation:
```bash
pip install Neuron-pypi-SivaNagendra-sn==0.0.3
```

How to Use:
```python
from Neuron.perceptron import Perceptron

## get X and y and then use below commands
model = Perceptron(eta=eta, epochs=epochs)
model.fit(X, y)
