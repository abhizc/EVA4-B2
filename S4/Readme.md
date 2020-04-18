put-37-40fddca887e3> in <module>()
      4 
      5 for epoch in range(1, 5):
----> 6     train(model, device, train_loader, optimizer, epoch)
      7     test(model, device, test_loader)

1 frames
/usr/local/lib/python3.6/dist-packages/torch/nn/functional.py in nll_loss(input, target, weight, size_average, ignore_index, reduce, reduction)
   1834     if input.size(0) != target.size(0):
   1835         raise ValueError('Expected input batch_size ({}) to match target batch_size ({}).'
-> 1836                          .format(input.size(0), target.size(0)))
   1837     if dim == 2:
   1838         ret = torch._C._nn.nll_loss(input, target, weight, _Reduction
