# opendatahub
Installing OpenDataHub can be a few step process depending on what all would you like to install. OpenDataHub has many components that includes - 
(i) Jupyter Notebooks
(ii) Seldon
(iii) Kafka
(iv) AI_Library
(v) Rook/Ceph (Storage)
(vi) Spark

*Storage*
Using Rook operator to install Ceph is optional. You can choose storage provider as you wish. However, to get same experience in the public cloud, or on-prem - rook/ceph is a good option. 
You can install Ceph with Rook Operator by following instructions here: https://opendatahub.io/arch.html#ceph-installation-with-the-rook-operator

*Open Data Hub*
Installing Open Data Hub depends on what options you choose. You can take manual installation route by going to this link: https://gitlab.com/opendatahub/opendatahub-operator/blob/master/docs/manual-installation.adoc

(i) Clone the OpenDataHub Operator by going here: https://gitlab.com/opendatahub/opendatahub-operator
(ii) Please choose your options by editing the file opendatahub_v1alpha1_opendatahub_cr.yaml (Path: deploy/crds)
(iii) look for odh_deploy and turn flag to false or true depending on what would you like to install. 
