## Bins obtained from 

```bash
MCOOL=../steps/cool/fibroblast/fibroblast.merged.mcool

for res in {1000,5000,10000,50000,100000}
do
    cooler dump --header -t bins $MCOOL::resolutions/$res | cut -f1-3 > ../data/bins/t2tbins.$res.tsv
done
```