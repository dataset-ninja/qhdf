Dataset **QHDF** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMzUxM19RSERGL3FoZGYtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiSlBQUnFVd2tzUzF4ZTNyZ1FVbWJabjlLVEpCZy95UFdMRmo1VUxRQVNNND0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22qhdf-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='QHDF', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://data.researchdatafinder.qut.edu.au/dataset/fc42f962-29c8-4be4-8d29-f61ebe165264/resource/1fdca442-dca0-4fd0-8412-4231297336a9/download/qhdf2020.tar.gz).