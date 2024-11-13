[![Qualcomm® AI Hub Models](https://qaihub-public-assets.s3.us-west-2.amazonaws.com/qai-hub-models/quic-logo.jpg)](../../README.md)


# [YOLOv11-Detection: Real-time object detection optimized for mobile and edge by Ultralytics](https://aihub.qualcomm.com/models/yolov11_det)

Ultralytics YOLOv11 is a machine learning model that predicts bounding boxes and classes of objects in an image.

{source_repo_details}This repository contains scripts for optimized on-device
export suitable to run on Qualcomm® devices. More details on model performance
accross various devices, can be found [here](https://aihub.qualcomm.com/models/yolov11_det).

[Sign up](https://myaccount.qualcomm.com/signup) to start using Qualcomm AI Hub and run these models on a hosted Qualcomm® device.




## Example & Usage

Install the package via pip:
```bash
pip install "qai_hub_models[yolov11_det]"
```


Once installed, run the following simple CLI demo:

```bash
python -m qai_hub_models.models.yolov11_det.demo
```
More details on the CLI tool can be found with the `--help` option. See
[demo.py](demo.py) for sample usage of the model including pre/post processing
scripts. Please refer to our [general instructions on using
models](../../../#getting-started) for more usage instructions.

## Export for on-device deployment

This repository contains export scripts that produce a model optimized for
on-device deployment. This can be run as follows:

```bash
python -m qai_hub_models.models.yolov11_det.export
```
Additional options are documented with the `--help` option. Note that the above
script requires access to Deployment instructions for Qualcomm® AI Hub.


## License
* The license for the original implementation of YOLOv11-Detection can be found
  [here](https://github.com/ultralytics/ultralytics/blob/main/LICENSE).
* The license for the compiled assets for on-device deployment can be found [here](https://github.com/ultralytics/ultralytics/blob/main/LICENSE)


## References
* [Ultralytics YOLOv11 Docs: Object Detection](https://docs.ultralytics.com/tasks/detect/)
* [Source Model Implementation](https://github.com/ultralytics/ultralytics/tree/main/ultralytics/models/yolo/detect)



## Community
* Join [our AI Hub Slack community](https://aihub.qualcomm.com/community/slack) to collaborate, post questions and learn more about on-device AI.
* For questions or feedback please [reach out to us](mailto:ai-hub-support@qti.qualcomm.com).

