# spikeTrain
This project implements a Spiking Neural Network (SNN) to classify handwritten digits from the MNIST dataset.

## Getting Started  

This project is designed to be run in a Google Colab environment for ease of setup

### Prerequisites
* **Google account**: For access to Google Colab and Google Drive
* **MNIST Dataset**: Provided in this repository as a zipped archive

### Running in Google Colab 

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/YanYi-Now/spikeTrain.git spikeTrain
    ```
2.  **Open `SpikeTrain.ipynb` notebook in Google Colab**

3. **Upload MNIST dataset to Google Drive**

    * Unzip the `MNIST.zip` folder 
    * Create a folder named `MNIST` inside "My Drive" on Google Drive
    * Upload the extracted files to `/content/drive/My Drive/MNIST/`  

4. **Run the notebook** (Runtime -> Run all)
   
   * The training and testing process will begin, with progress printed to the output

## Acknowledgments
This project was built referencing the following research papers:  
* Diehl, P. & Cook, M., (2015). Unsupervised learning of digit recognition using spike-timing-dependent plasticity. Frontiers in Computational Neuroscience (Volume 9)  
* Srinivasa, N., & Cho, Y. (2014). Unsupervised discrimination of patterns in spiking neural networks with excitatory and inhibitory synaptic plasticity. Frontiers in computational neuroscience, 8, 159. doi:10.3389/fncom.2014.00159
* Shouval, H. Z., Wang, S. S., & Wittenberg, G. M. (2010). Spike timing dependent plasticity: a consequence of more fundamental learning rules. Frontiers in computational neuroscience, 4, 19. doi:10.3389/fncom.2010.00019
    
