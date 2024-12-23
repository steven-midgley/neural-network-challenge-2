# neural-network-challenge-2
Employee retention predictor

```bash
echo '\nDeactivating all active conda environments\n\n'
conda deactivate 2>/dev/null || true
echo '\nRemoving "neural_network_2" environment\n\n'
conda remove --name neural_network_2 --all -y
echo '\nRecreate "neural_network_2" environment\n\n'
conda env create -f environment.yml -y
echo '\nActivate "neural_network_2" environment\n\n'
conda activate neural_network_2
```
