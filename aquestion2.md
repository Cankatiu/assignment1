**Q2.** Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene
by using the string concatenation operator, on the standard output! Note: Feel free to create a
fictional gene sequence by randomly filling in the gene components by the characters
corresponding to individual nucleotide bases.

....
promotor='TATTTAAATTAAAAATT'
5_prime_UTR='GTAATGTTGGGGAAAA'
start_codon='ATG'
exon1='ATCCCGGGTTCGAACTG'
intron='AATTTTTAAGGGGGAAAAA'
exon2='GCATTAGTCCAATGAAG'
stop_codon='TAG'
3_prime_UTR='AAAATTAAAAAAAAAAA'

my_fav_gene= promoter + 5_prime_UTR + start_codon + exon1 + \
             intron + exon2 + stop_codon + 3_prime_UTR
             
print('My favorite gene sequence is as follows:')
print(my_fav_gene)
......