Dataset **Animal Object Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/P/5/mT/ZegADSyA1TWr0EaVRxdfc1umyN9ukZ5SuVP8eLbdl6sMPP7h5fUiKzMY6KkPg2E1pUpU8Dd0lQJFtouVEaZ3wunVvC7teUilIALaBAXVk5LxfJGx1yV4sHqGltbn.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Animal Object Detection', dst_path='~/dtools/datasets/Animal Object Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/animal-detection-yvpsn/animal-object-detection-gbwme/dataset/2/download)