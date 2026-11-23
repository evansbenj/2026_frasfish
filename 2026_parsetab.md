# Parsetab

I used spades to assemble the genome of BJE4220 - a male individual:
```
/home/ben/projects/rrg-ben/ben/2026_fraseri_WGS/fq/trimmed/J/BJE4220_male_spades
```
I then used freebayes to genotype the fraseri data mapped to this individual and parsetab to look for sex-specific positions; files are here:
```
/home/ben/projects/rrg-ben/ben/2026_fraseri_WGS/bamz_mapped_to_frasBJE4220_male
```

I then used the XL CDS to check what coding regions are in the contigs with at least 1 het positions in all nine females and zero in all nine males. Results are consistent with the inferred complete duplicate of magicD (all exons) plus portions of flanking genez.
