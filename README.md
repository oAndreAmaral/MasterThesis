# MasterThesis - Implementation Work
## Deep Neural Networks for Behavioral Modeling of Analog ICs

This repository aims to store all the information about modeling the behavior of analog circuits.

All this work is of the authorship of **André Carneiro Amaral**

Firstly, a [LSTM Model](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/1%20-%20PyTorch%20-%20Model%20LSTM) is implemented to modelate the behavior of an amplifier taking in consideration different dimensions of the devices.

Secondly, a [MLP with two delay lines](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/2%20-%20PyTorch%20-%20Model%20MLP%20Delay%20Lines) is also obtained to modelate te behavior of the same amplifier.

Having the models producing results with accuracy, it is time to convert them to Verilog-A language in order to be possible to integrate them in complex front-end circuits. So, since Verilog-A has lack of support, I developed a [generator script](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/3%20-%20Generator%20Script%20(Python%20to%20Verilog-A)) capable to, given the neural network weights matrices and bias in Python, generate the Verilog-A code.

To prove the efficiency and well function of that script a [dummy example](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/4%20-%20VerilogA%20-%20Sin%20Dummy%20Example) with the Sin wave is created in Python and, using the generator script, implemented in Verilog-A. The exemple is extended in [this version](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/5%20-%20Verilog-A%20-%20Sin%20Dummy%20Example%20(Extension)), adding the circuit dimensions.

Finaly, the MLP model with two delay lines is [implemented](https://github.com/oAndreAmaral/MasterThesis/tree/Implementation-Work/6%20-%20VerilogA%20-%20Model%20MLP%20Delay%20Lines) in Verilog-A.

