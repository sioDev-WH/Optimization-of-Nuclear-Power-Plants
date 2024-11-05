## Statistical Data Reconciliation for Optimization of Nuclear Power Plants (NPPs)
An open-source library of statistical data Reconciliation (DR) algorithms for the optimization of nuclear power plants (NNPs). The DR algorithms play a key role in Measurement Uncertainty Recapture (MUR) analysis, a requirement for the power-generation uprate of NPPS. The MUR term refers to the regulatory process to authorize increasing power (MW) rating of NPPs by reducing certain emergency core cooling system (ECCS) assumptions regarding reactor power measurement uncertainty.

### Requirements
The algorithms described here adhere to the VDI 2048 standard, focusing on the basic requirements of data reconciliation:
*	The corrections to measurement data must be as small as possible (to ensure reconciliation results are not based on gross errors),
*	The reconciliation algorithm must reconcile not only measurement values but also measurement uncertainty (i.e., to reconcile covariances) to assess confidence in reconciled values.

We review the mathematical foundation of requirements for commercial and open-source algorithms, along with examples for CANDU NPPs. 
