# CarDetect
Link to models (rename worked_models dir to triton_repo): <br/>
https://disk.yandex.ru/d/krhczDWHgGkfmA <br/>
To start triton server: <br/>
docker run --runtime=nvidia --gpus all --rm -v </PATH/TO/WORKED_MODELS/WITH_NAME/triton_repo>:/models -p 8000:8000 nvcr.io/nvidia/tritonserver:22.12-py3 tritonserver --model-repository=/models
