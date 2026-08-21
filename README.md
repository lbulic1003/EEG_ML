# Distributed sex structure in consumer-grade EEG via NMF

Non-negative matrix factorisation of task-evoked spectral power from a
14-channel EMOTIV EPOC+ device (n = 86, 37-task battery). An unsupervised
decomposition into five stable components, screened against 17 participant
variables under a single FDR correction, finds that only sex aligns with the
embedding — resolving into two opposing-sign components (anterior-frontal,
higher in women; right-frontal, higher in men) with distinct task profiles.

Reproducible pipeline: feature-matrix construction, NMF with stability-based
rank selection, clustering, and omnibus permutation testing.
