# EncodeC
Chromatin conformation capture data analysis of compartments in look of correlations with ENCODE data. 


littleTest:

  This performs Iterative correction,
  creates a contact distance profile(CDP)
  builds a decaying model based on the (CDP)
  builds enrichment by the log of the corrected matrix/model-based matrix to center values to zero.
  performs eigendecomposition on the enrichment matrix.
  looks for linear relationship with E1 outer-product and the enrichment to validate the model.
