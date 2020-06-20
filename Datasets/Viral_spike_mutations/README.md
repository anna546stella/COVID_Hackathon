# Binding measurements of viral spike mutants

This dataset describes a saturation-mutagenesis experiment done on the receptor-binding domain
of the SARS-CoV-2 virus' spike protein. For every amino acid in the protein domain, mutant variants
were generated for every possible other amino acid (out of the 20 standard amino acids) 
that could exist at that position. Thus every possible single-position mutation is tested for its
ability to bind to the virus' known ACE2 receptor. The measurements for spike binding to ACE2-expressing
cells have already been processed from the raw measurements.

For each mutation, two measurements are made: how often that mutation is found when you analyze the 
very strongest binding mutants out of all of them ("Top"), and how often that mutation is found when
you analyze the weakest binding mutants out of all of them ("Bottom"). For each position in the protein, 
the amino acid that is naturally found in the spike's sequence (wild-type or "WT") is defined as having 
0 enrichment in the top-binders and 0 enrichment in bottom-binders. All other measurements are log-enrichments 
based on this, so positive values mean greater representation than wild-type and negative values 
lower-representation. 


Although these metrics are correlated, because of the complexitiies of measurement in an experiment like this the
correlations are not perfect. Thus, sometimes you may see a positive value in "Top" (reprenting greater binding) 
but not a negative value in "Bottom".

