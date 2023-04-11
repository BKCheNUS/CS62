# ViG
In the original paper the model was run on ImageNet.  Here I applied the model to CIFAR10.  
At first I fully intended to write all the code, however including the KNNs and the code for the patches that actually becomes a very involved process so I did reference their code a good amount.  
One thing to note, since CIFAR10 has inputs which are of much smaller dimension compared to imagenet, the number and variety of the patches you can draw is very limited.  This may explain why the model didn't perform as regular CNNs on the CIFAR dataset.
Furthermore the model was much slower than a standard CIFAR10 model.  I'm not sure if that's due to the complexity of the model or because GPUs are more suited to working with CNNs than GNNs.

To conclude a main takeaway is such a model may be very costly and be more suitable for larger images which further incurs a larger cost
