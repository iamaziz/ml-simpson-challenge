
ML Hackathon: Simpson challenge

#### main repo:
- https://github.com/lukas/ml-class/tree/master/simpsons-challenge

#### competition:

- 15000 training images in 13 categories (for Simpson characters), and 1600 test images.
- setup environment: bit.ly/hub-setup and https://gist.github.com/vanpelt/b52f6f5360be626d2c23189d513f94de
- username: ------@----.edu pswd: ------


#### event url:
- https://www.eventbrite.com/e/machine-learning-hackathon-registration-50549582161



#### winning criteria:
- highest validation accuracy over the test set.



#### Tips:

- tweak params e.g. change # of epoch, batch size .. etc.
- use data augmentation:
    - to generate more data,
    - prevent over-fitting,
    - and careful not to produce non-realistic images.
    - DO NOT augment test dataset
    - use Keras auto-stopping
- change model to something like 1994 LeNet arch
- `model.save('simpsons.h5)` then later load it instead of starting from scratch after little tweaks.

#### See people's results:

- https://app.wandb.ai/mlclass/simposons-nov5/runs/io9qizs8
