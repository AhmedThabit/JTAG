# JTAG

few useful commands:

## Train

**from a pre-trained model**

```
flow --model cfg/tiny-yolo-voc-3c.cfg --load bin/tiny-yolo-voc.weights --train --annotation test/training/annotations --dataset test/training/images --lr 0.0001 --epoch 200 --save 100
```

## Test

```
./flow --imgdir test/training/images --model cfg/tiny-yolo-voc-3c.cfg --load -1
```
