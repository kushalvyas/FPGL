# FPGL - Fit Pixels Get Labels / MetaSeg - A meta-learned implicit neural representation framework for medical image segmentation

## Code coming soon!

__Abstract__: Modern state-of-the-art deep learning architectures for medical image segmentation rely strictly on feed-forward passes over dense pixel/voxel grids, which scale poorly to large signals. Implicit neural representations (INRs) offer a lightweight, continuous alternative to raw grids, but are traditionally signal-specific and lack the semantic coherence needed for dataset-level predictive tasks. In this study, we introduce 	**FPGL**, a framework that adapts INRs for medical segmentation by meta-learning a shared initialization. By jointly fitting scans and segmentation maps across a training dataset, 	**FPGL** can segment novel subjects simply by fine-tuning on their raw test-time observations. We expand on our preliminary MICCAI study of this work in two key ways. First, we enable both first-order (Reptile) and second-order (MAML) meta-learning routines. Second, we introduce a generalized formulation that allows for segmentation from indirect measurements of a scan, such as tomographic projections and demonstrate several proofs-of-concept experiments across various forward and inverse tasks. We evaluate 	**FPGL** on a well-aligned brain 2D/3D MRI dataset and a more heterogeneous abdominal 2D CT dataset. On the MRI data, **FPGL** matches U-Net baselines.
However, performance drops significantly on the CT dataset, revealing a sensitivity to spatial misalignments unexplored in our previous MRI-only study. Interestingly, performing CT segmentation directly from the scans and indirectly from sparse synthetic tomographic projections yields remarkably similar performance, suggesting that 	**FPGL**'s current optimization design is not yet fully exploiting all details in a scan. We conduct additional studies and reveal key insights on the task- and optimizer-specific behavior of 	**FPGL**. By outlining both its promise and its current limitations, this study establishes a strong foundation for advancing the exciting new field of INR-based medical image segmentation.

## Citation

If you find our work useful, please cite us!

    TBD

