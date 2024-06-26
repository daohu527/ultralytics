---
comments: true
description: Master Ultralytics HUB integrations with platforms & formats for seamless dataset imports and model training.
keywords: Ultralytics HUB, Roboflow integration, dataset import, model training, HUB integrations, export models, AI models
---

# Ultralytics HUB Integrations

Learn about [Ultralytics HUB](https://bit.ly/ultralytics_hub) integrations with various platforms and formats.

## Datasets

Seamlessly import your datasets in [Ultralytics HUB](https://bit.ly/ultralytics_hub) for [model training](./models.md#train-model).

After a dataset is imported in [Ultralytics HUB](https://bit.ly/ultralytics_hub), you can [train a model](./models.md#train-model) on your dataset just like you would using the [Ultralytics HUB](https://bit.ly/ultralytics_hub) datasets.

### Roboflow

You can easily filter the [Roboflow](https://roboflow.com/?ref=ultralytics) datasets on the [Ultralytics HUB](https://bit.ly/ultralytics_hub) [Datasets](https://hub.ultralytics.com/datasets) page.

![Ultralytics HUB screenshot of the Datasets page with Roboflow provider filter](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_1.jpg)

[Ultralytics HUB](https://bit.ly/ultralytics_hub) supports two types of integrations with [Roboflow](https://roboflow.com/?ref=ultralytics), [Universe](#universe) and [Workspace](#workspace).

#### Universe

The [Roboflow](https://roboflow.com/?ref=ultralytics) Universe integration allows you to import one dataset at a time into [Ultralytics HUB](https://bit.ly/ultralytics_hub) from [Roboflow](https://roboflow.com/?ref=ultralytics).

##### Import

When you export a [Roboflow](https://roboflow.com/?ref=ultralytics) dataset, select the [Ultralytics HUB](https://bit.ly/ultralytics_hub) format. This action will redirect you to [Ultralytics HUB](https://bit.ly/ultralytics_hub) and trigger the **Dataset Import** dialog.

You can import your [Roboflow](https://roboflow.com/?ref=ultralytics) dataset by clicking on the **Import** button.

![Ultralytics HUB screenshot of the Dataset Import dialog with an arrow pointing to the Import button](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_universe_import_1.jpg)

Next, [train a model](./models.md#train-model) on your dataset.

![Ultralytics HUB screenshot of the Dataset page of a Roboflow Universe dataset with an arrow pointing to the Train Model button](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_universe_import_2.jpg)

##### Remove

Navigate to the Dataset page of the [Roboflow](https://roboflow.com/?ref=ultralytics) dataset you want to remove, open the dataset actions dropdown and click on the **Remove** option.

![Ultralytics HUB screenshot of the Dataset page of a Roboflow Universe dataset with an arrow pointing to the Remove option](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_universe_remove_1.jpg)

??? tip "Tip"

    You can remove an imported [Roboflow](https://roboflow.com/?ref=ultralytics) dataset directly from the [Datasets](https://hub.ultralytics.com/datasets) page.

    ![Ultralytics HUB screenshot of the Datasets page with an arrow pointing to the Remove option of one of the Roboflow Universe datasets](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_remove_1.jpg)

#### Workspace

The [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace integration allows you to import an entire [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace at once into [Ultralytics HUB](https://bit.ly/ultralytics_hub).

##### Import

Navigate to the [Integrations](https://hub.ultralytics.com/settings?tab=integrations) page by clicking on the **Integrations** button in the sidebar.

Type your [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace private API key and click on the **Add** button.

??? tip "Tip"

    You can click on the **Get my API key** button which will redirect you to the settings of your [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace from where you can obtain your private API key.

![Ultralytics HUB screenshot of the Integrations page with an arrow pointing to the Integrations button in the sidebar and one to the Add button](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_workspace_import_1.jpg)

This will connect your [Ultralytics HUB](https://bit.ly/ultralytics_hub) account with your [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace and make your [Roboflow](https://roboflow.com/?ref=ultralytics) datasets available in [Ultralytics HUB](https://bit.ly/ultralytics_hub).

![Ultralytics HUB screenshot of the Integrations page with an arrow pointing to one of the connected workspaces](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_workspace_import_2.jpg)

Next, [train a model](./models.md#train-model) on your dataset.

![Ultralytics HUB screenshot of the Dataset page of a Roboflow Workspace dataset with an arrow pointing to the Train Model button](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_workspace_import_3.jpg)

##### Remove

Navigate to the [Integrations](https://hub.ultralytics.com/settings?tab=integrations) page by clicking on the **Integrations** button in the sidebar and click on the **Unlink** button of the [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace you want to remove.

![Ultralytics HUB screenshot of the Integrations page  with an arrow pointing to the Integrations button in the sidebar and one to the Unlink button of one of the connected workspaces](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_workspace_remove_1.jpg)

??? tip "Tip"

    You can remove a connected [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace directly from the Dataset page of one of the datasets from your [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace.

    ![Ultralytics HUB screenshot of the Dataset page of a Roboflow Workspace dataset with an arrow pointing to the remove option](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_workspace_remove_2.jpg)

??? tip "Tip"

    You can remove a connected [Roboflow](https://roboflow.com/?ref=ultralytics) Workspace directly from the [Datasets](https://hub.ultralytics.com/datasets) page.

    ![Ultralytics HUB screenshot of the Datasets page with an arrow pointing to the Remove option of one of the Roboflow Workspace datasets](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/integrations/hub_roboflow_remove_1.jpg)

## Models

### Exports

After you [train a model](./models.md#train-model), you can [export it](./models.md#deploy-model) to 13 different formats, including ONNX, OpenVINO, CoreML, TensorFlow, Paddle and many others.

![Ultralytics HUB screenshot of the Deploy tab inside the Model page with an arrow pointing to the Export card and all formats exported](https://raw.githubusercontent.com/ultralytics/assets/main/docs/hub/models/hub_deploy_model_1.jpg)

The available export formats are presented in the table below.

| Format                                            | `format` Argument | Model                     | Metadata | Arguments                                                            |
|---------------------------------------------------|-------------------|---------------------------|----------|----------------------------------------------------------------------|
| [PyTorch](https://pytorch.org/)                   | -                 | `yolov8n.pt`              | ✅        | -                                                                    |
| [TorchScript](../integrations/torchscript.md)     | `torchscript`     | `yolov8n.torchscript`     | ✅        | `imgsz`, `optimize`, `batch`                                         |
| [ONNX](../integrations/onnx.md)                   | `onnx`            | `yolov8n.onnx`            | ✅        | `imgsz`, `half`, `dynamic`, `simplify`, `opset`, `batch`             |
| [OpenVINO](../integrations/openvino.md)           | `openvino`        | `yolov8n_openvino_model/` | ✅        | `imgsz`, `half`, `int8`, `batch`                                     |
| [TensorRT](../integrations/tensorrt.md)           | `engine`          | `yolov8n.engine`          | ✅        | `imgsz`, `half`, `dynamic`, `simplify`, `workspace`, `int8`, `batch` |
| [CoreML](../integrations/coreml.md)               | `coreml`          | `yolov8n.mlpackage`       | ✅        | `imgsz`, `half`, `int8`, `nms`, `batch`                              |
| [TF SavedModel](../integrations/tf-savedmodel.md) | `saved_model`     | `yolov8n_saved_model/`    | ✅        | `imgsz`, `keras`, `int8`, `batch`                                    |
| [TF GraphDef](../integrations/tf-graphdef.md)     | `pb`              | `yolov8n.pb`              | ❌        | `imgsz`, `batch`                                                     |
| [TF Lite](../integrations/tflite.md)              | `tflite`          | `yolov8n.tflite`          | ✅        | `imgsz`, `half`, `int8`, `batch`                                     |
| [TF Edge TPU](../integrations/edge-tpu.md)        | `edgetpu`         | `yolov8n_edgetpu.tflite`  | ✅        | `imgsz`, `batch`                                                     |
| [TF.js](../integrations/tfjs.md)                  | `tfjs`            | `yolov8n_web_model/`      | ✅        | `imgsz`, `half`, `int8`, `batch`                                     |
| [PaddlePaddle](../integrations/paddlepaddle.md)   | `paddle`          | `yolov8n_paddle_model/`   | ✅        | `imgsz`, `batch`                                                     |
| [NCNN](../integrations/ncnn.md)                   | `ncnn`            | `yolov8n_ncnn_model/`     | ✅        | `imgsz`, `half`, `batch`                                             |

## Exciting New Features on the Way 🎉

- Additional Dataset Integrations
- Detailed Export Integration Guides
- Step-by-Step Tutorials for Each Integration

## Stay Updated 🚧

This integrations page is your first stop for upcoming developments. Keep an eye out with our:

- **Newsletter:** Subscribe [here](https://ultralytics.com/#newsletter) for the latest news.
- **Social Media:** Follow us [here](https://www.linkedin.com/company/ultralytics) for updates and teasers.
- **Blog:** Visit our [blog](https://ultralytics.com/blog) for detailed insights.

## We Value Your Input 🗣️

Your feedback shapes our future releases. Share your thoughts and suggestions [here](https://ultralytics.com/survey).

## Thank You, Community! 🌍

Your [contributions](https://docs.ultralytics.com/help/contributing) inspire our continuous [innovation](https://github.com/ultralytics/ultralytics). Stay tuned for the big reveal of what's next in AI and ML at Ultralytics!
