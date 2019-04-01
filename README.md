# Turbo-charged Machine Learning: Fitting Models Fast with H2O (or: How to Make Your Computer Fan Run/Heat Up the Datacenter)

The model fitting stage of a data science workflow has always been compute-intensive. Combine this with a need to try multiple approaches and hyperparameter tuning, and older, single-threaded algorithms that are CPU-only just don't cut it anymore. We'll look at an open-source, high-performance, cross-platform package for machine learning that uses a columnar in-memory data store, combined with tight, machine-aware Java code that implements parallel versions of the major machine learning algorithms. It can take advantage of as many cores and as much memory as you give it, and can also use GPU compute for many algorithms. The algorithms can be used as drop-in replacements for the scikit-learn algorithms to vastly speed up your project, can be called via API from R or Python, or used through a web interface.


