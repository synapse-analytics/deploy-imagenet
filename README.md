# deploy-imagenet

### ImageNet2012 Deployment and Inference Benchmarks

<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>

| Model             | PyTorch (Float32)  ||| ONNX (Float32)     ||| ONNX (Int8)         |||
|                   | Top-1 | Top-5 | Xent | Top-1 | Top-5 | Xent | Top-1 | Top-5 | Xent  |
| ----------------- | ----- | ----- | ---- | ----- | ----- | ---- | ----- | ----- | ----- |
| ResNet50          |       |       |      |       |       |      |       |       |       |
| AlexNet           |       |       |      |       |       |      |       |       |       |
| VGG-11            |       |       |      |       |       |      |       |       |       |
| VGG-13            |       |       |      |       |       |      |       |       |       |
| VGG-16            |       |       |      |       |       |      |       |       |       |
| VGG-19            |       |       |      |       |       |      |       |       |       |
| VGG-11 BN         |       |       |      |       |       |      |       |       |       |
| VGG-13 BN         |       |       |      |       |       |      |       |       |       |
| VGG-16 BN         |       |       |      |       |       |      |       |       |       |
| VGG-19 BN         |       |       |      |       |       |      |       |       |       |
| ResNet-18         |       |       |      |       |       |      |       |       |       |
| ResNet-34         |       |       |      |       |       |      |       |       |       |
| ResNet-50         |       |       |      |       |       |      |       |       |       |
| ResNet-101        |       |       |      |       |       |      |       |       |       |
| ResNet-152        |       |       |      |       |       |      |       |       |       |
| SqueezeNet 1.0    |       |       |      |       |       |      |       |       |       |
| SqueezeNet 1.1    |       |       |      |       |       |      |       |       |       |
| Densenet-121      |       |       |      |       |       |      |       |       |       |
| Densenet-169      |       |       |      |       |       |      |       |       |       |
| Densenet-201      |       |       |      |       |       |      |       |       |       |
| Densenet-161      |       |       |      |       |       |      |       |       |       |
| Inception V3      |       |       |      |       |       |      |       |       |       |
| GoogleNet         |       |       |      |       |       |      |       |       |       |
| ShuffleNet V2     |       |       |      |       |       |      |       |       |       |
| MobileNet V2      |       |       |      |       |       |      |       |       |       |
| ResNeXt-50-32x4d  |       |       |      |       |       |      |       |       |       |
| ResNeXt-101-32x8d |       |       |      |       |       |      |       |       |       |
| Wide ResNet-50-2  |       |       |      |       |       |      |       |       |       |
| Wide ResNet-101-2 |       |       |      |       |       |      |       |       |       |
| MNASNet           |       |       |      |       |       |      |       |       |       |


### PyTorch Model Loading
```
# TODO
```

### PyTorch Model Pre-processing
```
# TODO
```

### PyTorch Inference Example
```
# TODO
```

