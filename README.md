# deepops
Deep Learning Very High performance operations written to run on GPU using PyCUDA.

# Tensor
```
a = Tensor([1,2,3,4,5])
deepop tensor 
```
# Attach to a cuda device
```
a = Tensor([1,2,3,4,5])
a.device("gpu:0") # attach to gpu device.
```
# check Device
```
a.where
# 'cpu'
```
# Addition
```
a = Tensor([1.0,2.0])
print(a + a)
# GPU Operation
```

# Contribution is highly appreciated.
Please contribute to my work.

# TODOs
write tests...
support more operations.

# lot of work ahead...
```
# Add gradient support.
# backward pass.
# add a mini optimizer.
# neurons semantics.
```

