# Diverso Lab

# FaMa Framework: Automated Analyses of Feature Models

## Main features of the framework
We present a Python-based AAFM framework that takes into consideration previous AAFM tool designs and enables multi-solver and multi-metamodel support for the integration of AAFM tooling on the Python ecosystem

Easy to extend by enabling the creation of new plugins following a semi-automatic generator approach.
- Support multiple variability models
- Support multiple solvers
- Support multiple operations.

## Core operations

### Valid Model
This operation checks if the model is valid withrespect to its semantics.

### Valid Configuration.
This operation takes a model and a partial configuration and checks if the configuration is correct or not.

### Valid Product.
This operation takes a product and checks its validity on top of the selected model.

### All products.
This operation prints out the list of valid products from a feature model

### Dead Features.
This operation detects those features that cannot be present in any valid configuration

### Core Features.
This operation returns the features present in all products

### Error detection.
This operation returns a set of errors in a model.

### Error diagnosis.
This operation returns the possible solutions for the errors present in a model

# Try!

You can try our framework [here](https://github.com/diverso-lab/core)

# Authors

- David Benavides
- José Á. Galindo
- José Miguel Horcas
- Antonio Germán Márquez
- David Romero
- Pablo Pazo

