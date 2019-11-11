# VO
Visual odometer based on RGB-D

### Datasets
Test dataset is [here](https://vision.in.tum.de/rgbd/dataset/freiburg1/rgbd_dataset_freiburg1_xyz.tgz).

### Dependencies

- Eigen
- OpenCV >= 3.1
- Sophus 
- G2O

### Compile
```
mkdir build
cd build
cmake ..
make
```

### How to run
```
./bin/run_vo ./config/default.yaml
```

