# 6DPoseAnnotator

An interactive 6 degreee-of-freedom pose annotation tool using point cloud processings.

## Requirements
- Open3d
- Numpy
- OpenCV

## 6D pose annotation with mouse and keyboard commands

Type:
```
$ python 6DoFPoseAnnotator.py
```

You can use following commands: 

- Left click - Translation to the mouse pointer
- "1" - Rotation around roll axis.
- "2" - Rotation around pitch axis.
- "3" - Rotation around yaw axis.
- "i" - ICP algorithm is applied with current pose.
- "q" - Quit

![2DView](./data/screenshot_2d_view.png)

## Visualization by 3d viewer

For visualizing results in 3D space, type:
```
$ pv.py --input cloud_in_ds.ply cloud_m.ply
```

![3DView](./data/screenshot_3d_view.png)