#NU66ET(mineserbetci)'s answer to Question 2

**Q2** Assign variables to the individual components of your favorite gene (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator on the standard output! Note: Feel free to create a fictional gene sequence by randomly filling in the gene components by the characters corresponding to individual nucleotide bases.

**Answer**


star_codon ='AUG'
treonin+glutamat = 'ACGGAG'
-stop_codon ='UAA' or 'UAG'
aspartic_acid = 'GAU' or 'GAC'
binding_site = 'GGCCAATCT'
1_mutation = 'AAATTGCTGACGTTTCGATT'
exon1 :'AGT' + 'ATT'

my_fav_gene = (star_codon + stop_codon + aspartic_acid + binding_site + 1_mutation + treonin+glutamat)

print= ('My favourite gene sequences is as follows:' + ' ' + my_fav_gene)