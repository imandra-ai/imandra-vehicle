# imandra-vehicle
An ImandraX backend for the Vehicle neural network verification system

# Status
We're basing our ImandraX backend on Isabelle/HOL's, and we've currently ported these libraries to ImandraX:
 - `Tensor`
 - `Subtensor`
 - `Add`
 - `Scalar_mult`
 - `Vehicle`

With these libs, we can then naturally encode the NN version of the Boyer-Green-Moore car controller, and verify it (cf. `Car_safety_proof.iml`).

All of these files are fully verified by ImandraX.

# TODO

Next, we want to instrument Vehicle to output ImandraX encodings of its verification results, using
these ImandraX libraries (`Tensor,` ..., `Vehicle`).

# Contact
Grant Passmore (grant@imandra.ai)