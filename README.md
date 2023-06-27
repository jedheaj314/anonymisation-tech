# anonymisation-tech

The goal of this project is to provide a benchmark for comparing the performance of multiple anonymisation technologies. The comparison is conducted based on two key metrics: time and accuracy. By evaluating these metrics, Mersey Care can make informed decisions about which anonymisation technology best suits their needs.


## Technologies
The following anonymisation technologies are currently included in this repository:

Presidio: This tool comes with two models to anonymise PII by default. This tool is know for modularity as any third party models and strategy can be implmeneted under this.

.....

## Usage

1. Clone the repository to your local machine:
git clone https://github.com/your-username/anonymisation-performance.git

2. Open the dev container.

3. Run following command:
python anonymisation_performance.py --technology <technology_name>

The script will output the anonymised dataset and provide performance metrics such as time taken for anonymisation and accuracy of the anonymised data.
