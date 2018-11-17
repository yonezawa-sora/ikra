# auto_counttable_maker

[idep](http://bioinformatics.sdstate.edu/idep/)のinputとしてcount tableをexperiment matrix（tpTregTconv_rnaseq_experiment_table.csv）から自動でつくる。salmonを用いる。

実行例

```bash
$ bash MakeCountTable_SRR.sh tpTregTconv_rnaseq_experiment_table.csv examle mm10
```

## やること

- fastqかSRRの判別
- 生物種の判別
- trimmomatic
- gtf, transcript file をGENCODEから
- salmon

## 参考

- [idep](http://bioinformatics.sdstate.edu/idep/)
- [GENCODE](https://www.gencodegenes.org/)
- [salmon](https://combine-lab.github.io/salmon/getting_started/)

