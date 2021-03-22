# criticality

Data is generated by the c++ code.
The neural network is written in python using tensorflow.

## Requirements

* Python 3.8+

```shell
pip install -r requirements.txt
```
 ### Example: Generate and save .

 ```shell
    python statphy/data_factory.py \
        --model square lattice percolation \
        --L 128 \
        --crit_parameter 0.5927 \
        --sample_per_configuration 100
 ```

## License
[Apache License 2.0](https://github.com/bisonai/mobilenetv3-tensorflow/blob/master/LICENSE)
