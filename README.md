Collection of files used for investigation of stability of LSTM models of the 2-dimensional Henon map.
Results are available in the paper 
<br>
<br>
Important version info: <br>
Python (3.11.5) <br>
PyTorch (2.0.1) <br>
NumPy (1.26.4) <br>
pandas (2.0.3) <br>
matplotlib (3.9.0) <br>
<br>
Parameters used:<br> 
simulation start value = [0, 0.9]<br>
transients discarded = 10**5<br>
no. test series = 500<br>
test series length = 102<br>
train:validation split = 0.8:0.2<br>
maximum training epochs = 150v
batch size = 64<br>
optimizer = ADAM<br>
loss function = MAE<br>
starting learning rate = 0.02<br>
learning rate decay factor = 0.2<br>
early termination patience = 50<br>
testing accuracy threshold = 0.01 #1% series range (approx 0.026)
