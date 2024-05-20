<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,docker" />
  </a>
</p>

# Temperature Converter

_Convert Fahrenheit to Celcius, using Tensorflow and PyTorch_

### Development Steps 

- Libraries
    - Tensorflow for Neural Net
    - Numpy for arrays
- Create celsius and fahrenheit values
    - Use numpy
    - Make them floats (dtype=float)... cause temperature exists as a continuum, therefore it needs decimals
- Layers and Model
    - Use tf's keras
    - Model is "Sequential"
- Compile Model
    - Use an optimizer (Adam; but could try others)
    - Choose a loss function
- Train
    - More epochs = Greater Accuracy = More Resources (gets pricey)
- Plot
    - Matplotlib
    - Shows how the Loss (error) progresses over Epochs (time)
- Test with an actual value





### Instructions
Clone this repo and run the Jupyter notebook with 

`source .venv/bin/activate` and on Windows `.venv\Scripts\activate`
Recreate this with Torch
