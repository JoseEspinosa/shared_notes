# Issues to tackle before 2.0.0 release

[207](https://github.com/nf-core/chipseq/issues/207) Error in the json file created by the launcher.

## Issues already fixed but still to be closed

[160](https://github.com/nf-core/chipseq/issues/160) Add bowtie2 as choice for aligner. Merged in [PR#244](https://github.com/nf-core/chipseq/pull/244) also includes the implementation of `STAR`.

[246](https://github.com/nf-core/chipseq/issues/246) Dashes in group identifier, coded changed in `deseq2_qc.r` to allow dashes in names. 

[228](https://github.com/nf-core/chipseq/issues/228) update Blacklists used in the pipelines. **Discuss** the open [PR](https://github.com/nf-core/chipseq/pull/250) with Harshil.

[222](https://github.com/nf-core/chipseq/issues/222) Amazon status code 403, answered but not closed.

[213](https://github.com/nf-core/chipseq/issues/213) Merged biological replicates.
maybe add replicate columns add to v2.0

## Issues half-way implemented

[237](https://github.com/nf-core/chipseq/issues/237) Implementation of the pipeline following new DSL2 v2.0 syntax. We might one to close in fact it is a milestone more than a issue.

[220](https://github.com/nf-core/chipseq/issues/220) Not in the corresponding process of the development branch `PHANTOMPEAKQUALTOOLS`, **Discuss** is just because we forgot or is there a reason?
close
## Issues to discuss if it's worth implementing before release

[128](https://github.com/nf-core/chipseq/issues/128) Error when no peaks are found.

Would be nice 

[251](https://github.com/nf-core/chipseq/issues/251) Output bigwigs with macs2 p-value signal for every base-pair. It will imply changing macs2 callpeak command and retrieve the new as a new output channel.

[242](https://github.com/nf-core/chipseq/issues/242). Missing output file(s) *igv.txt expected by process MACS2. Not sure was going on here

[242](https://github.com/nf-core/chipseq/issues/233) Chromap. There is a new release that should fix the memory problems found before. **Add now**

## Discarded issues for release 2.0.0

[87](https://github.com/nf-core/chipseq/issues/87) Add IDR analysis. **OK**
[235](https://github.com/nf-core/chipseq/issues/235) Add an optional column for replicates in the samplesheet. This is related to #87 just above. **OK**

## Can be closed?

[127](https://github.com/nf-core/chipseq/issues/127) Cut&Run, close since cut&run has already an independent pipeline.
[217](https://github.com/nf-core/chipseq/issues/217). May be a small bug.
[196](https://github.com/nf-core/chipseq/issues/196). Check if this implemented in the new r scripts or ask Harshil.

## Just help

[238](https://github.com/nf-core/chipseq/issues/238) scale folder in bigwig folder.
[223](https://github.com/nf-core/chipseq/issues/223) tools versions are running. **Answer** before release.
[198](https://github.com/nf-core/chipseq/issues/198) BWA_mem error. Should be solved right?
test dev version when ready

## Other

See [here](https://nfcore.slack.com/archives/CJRH30T6V/p1639051236150900) the proposal from Harshil and might be good to create an issue for it.

[This](https://github.com/nf-core/chipseq/blob/6924b669422215f9021144b251e83fc9929be1fe/main.nf#L1396) does not need to be this way anymore since the table will have the comparisons between samples right?

blacklist check that the chromosome sizes are the same and the name
only have version 2 and for human the v3
get rid of v1

also modify them to fit ensembl
that's the reason 

Check that intervals are the same

chrn -- ensembl or ncbi

ensembl 38 just number

v3 black list is chrn ucsc 

hg19 solo hay version 1 

la diferencia entre el hg19 de v1 and the one of v2 is that v1 was manually curated while v2 has not. That is why we maintain v1 for hg19 as the default.

check that hg19 and GRch37 have the same size
y cambiar names

me deja los antiguos para comparar con los nuevos que tienen la misma nomenclatura

hg ucsc GRch ensembl

in usage we can just copy paste and then say that in igenomes you can see what is used by default.

update modules in a separate pr

Add a replicate column-- for the bigweg files first normalize by replicate and then 