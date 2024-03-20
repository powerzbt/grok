# Grok-1 Repository

This repository hosts the example code for loading and executing the Grok-1 model, which is available with open weights. The Grok-1 model is a state-of-the-art machine learning model designed for a wide range of applications.

## Getting Started

To utilize the Grok-1 model, please follow these instructions:

1. **Download the Checkpoint**: First, ensure you have downloaded the checkpoint. Place the `ckpt-0` directory within the `checkpoint` folder.
2. **Install Dependencies**: Install the required Python packages by running the following command in your terminal:

    ```shell
    pip install -r requirements.txt
    ```

3. **Execute the Model**: You can run the model using the provided script. Execute the following command:

    ```shell
    python run.py
    ```

This script will load the checkpoint and sample from the model using a test input.

## Requirements

Due to the extensive size of the Grok-1 model, which consists of 314 billion parameters, it is imperative to use a machine equipped with sufficient GPU memory to run the example code effectively.

It is important to note that the implementation of the Mixture of Experts (MoE) layer in this repository prioritizes simplicity over efficiency. This decision was made to eliminate the necessity for custom kernels, thereby facilitating the validation of the model's accuracy.

## Downloading the Model Weights

The Grok-1 model weights can be acquired using a torrent client with the following magnet link:


```
magnet:?xt=urn:btih:5f96d43576e3d386c9ba65b883210a393b68210e&tr=https%3A%2F%2Facademictorrents.com%2Fannounce.php&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce
```

# Contributors

Thanks goes to these wonderful contributors ([emoji key](https://allcontributors.org/docs/en/emoji-key) following [all-contributors](https://github.com/all-contributors/all-contributors) specification):

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/ibab"><img src="https://avatars.githubusercontent.com/ibab?v=4&s=100" width="100px;" alt="ibab"/><br /><sub><b>ibab</b></sub></a><br />
      <a href="https://github.com/xai-org/grok-1/commits?author=ibab" title="Code">💻</a>
      <a href="https://github.com/xai-org/grok-1/commits?author=ibab" title="Documentation">📖</a>
      <a href="#infra-ibab" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a>
      <a href="#maintenance-ibab" title="Maintenance">🚧</a>
      <a href="#ideas-ibab" title="Ideas & Planning">🤔</a>
      <a href="#review-ibab" title="Reviewed Pull Requests">👀</a>
      <a href="#tool-ibab" title="Tools">🔧</a>
      <a href="#test-ibab" title="Tests">⚠️</a>
      <a href="#research-ibab" title="Research">🔬</a>
      </td>
      <td align="center"><a href="https://github.com/TobyPDE"><img src="https://avatars.githubusercontent.com/TobyPDE?v=4&s=100" width="100px;" alt="TobyPDE"/><br /><sub><b>TobyPDE</b></sub></a><br />
      <a href="https://github.com/xai-org/grok-1/commits?author=TobyPDE" title="Code">💻</a>
      <a href="#review-TobyPDE" title="Reviewed Pull Requests">👀</a>
      <a href="#bug-TobyPDE" title="Bug reports">🐛</a>
      <a href="#ideas-TobyPDE" title="Ideas & Planning">🤔</a>
      <a href="#maintenance-TobyPDE" title="Maintenance">🚧</a>
      <a href="#test-TobyPDE" title="Tests">⚠️</a>
      <a href="#doc-TobyPDE" title="Documentation">📖</a>
      <a href="#security-TobyPDE" title="Security">🛡️</a>
      </td>
    </tr>
  </tbody>
</table>

Contributions from those not on the research team are welcome.

# License

The code and associated Grok-1 weights in this release are licensed under the
Apache 2.0 license. The license only applies to the source files in this
repository and the model weights of Grok-1.
