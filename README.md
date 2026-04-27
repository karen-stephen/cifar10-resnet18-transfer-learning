# CIFAR-10 Classification with Pretrained ResNet18

Transfer learning project using PyTorch.

## Steps
- Loaded pretrained ResNet18
- Froze backbone layers
- Replaced final FC layer for 10 CIFAR-10 classes
- Trained on Google Colab GPU

## Result
- Test Accuracy: ~80%

## Tech Stack
- Python
- PyTorch
- torchvision