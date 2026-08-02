# Can Generative Models Recover Latent Distributions from Repeated Noisy Measurements?
$$W = Z + \varepsilon$$
- Extending flow-based and GMMN generative deconvolution models with MMD objectives to the unknown-noise setting
- Tests are OOS, using recovered empirical distribution (not the explicit density distribution)
<img width="507" height="325" alt="summary_bar_chart" src="https://github.com/user-attachments/assets/f37694b3-a74a-48e5-9865-91ebf32858d2" />
<details>
  <summary>Improvements</summary>
  - weibull, etc, Seed? Architecture?, Colours:), dgp, statioarity assumption, log_density
</details>

# Normalizing Flow Model

<details>
  <summary>Test on No-Noise Setting</summary>
  
  ## Gaussian
  <img width="650" height="780" alt="sanity_check_gaussian" src="https://github.com/user-attachments/assets/b60f3ac7-7d95-4680-a80c-f9c0e3523174" />
  
  ## GMM
  <img width="650" height="780" alt="sanity_check_gmm" src="https://github.com/user-attachments/assets/704fa44d-930f-4908-836d-4c0a5c5c84a4" />
  
  ## Laplace
  <img width="650" height="780" alt="sanity_check_laplace" src="https://github.com/user-attachments/assets/f18cc8f8-86b2-4e2a-a3ee-d2f707eaddaf" />
  
  ## Lognormal
  <img width="650" height="780" alt="sanity_check_lognormal" src="https://github.com/user-attachments/assets/86b1a730-79b6-496d-9a09-9f5ea5030733" />
  
  ## Manifold
  <img width="650" height="780" alt="sanity_check_manifold" src="https://github.com/user-attachments/assets/9b444966-4cf7-4a63-bad9-d3331c8d09b9" />
  
  ## Student's t
  <img width="650" height="780" alt="sanity_check_student_t" src="https://github.com/user-attachments/assets/ac207533-75d1-4288-bc5e-5953658ca92c" />
</details>

<details>
  <summary>Test on Unknown-Noise Setting</summary>
  
  ## W-Gaussian, E-Gaussian
  <img width="845" height="520" alt="config_gaussian_x_gaussian" src="https://github.com/user-attachments/assets/4f8f9265-0ef2-4a33-ba11-b72143a33238" />
  
  ## W-Gaussian, E-Laplace
  <img width="845" height="520" alt="config_gaussian_x_laplace" src="https://github.com/user-attachments/assets/b314b8d3-b920-4bc0-9e84-34237b55d9cc" />
  
  ## W-GMM, E-Gaussian
  <img width="845" height="520" alt="config_gmm_x_gaussian" src="https://github.com/user-attachments/assets/3702e777-15a2-40ca-8da4-5aeb8fec7db0" />
  
  ## W-GMM, E-Lognormal
  <img width="845" height="520" alt="config_gmm_x_lognormal" src="https://github.com/user-attachments/assets/f14afb70-3717-415e-8dfa-96834773fa2e" />
  
  ## W-Manifold, E-Laplace
  <img width="845" height="520" alt="config_manifold_x_laplace" src="https://github.com/user-attachments/assets/36f8be90-6240-4933-8811-8e207ef45ec3" />
  
  ## W-Student's t, E-Gaussian
  <img width="845" height="520" alt="config_student_t_x_gaussian" src="https://github.com/user-attachments/assets/4f09616d-ad7d-4599-9878-05f3711be468" />
</details>

# GMMN

<details>
  <summary>Test on No-Noise Setting</summary>
  
  ## Gaussian
  <img width="650" height="780" alt="sanity_check_gaussian_mlp" src="https://github.com/user-attachments/assets/d670bbc7-eb0d-4526-b795-c3edc6ea27f7" />
  
  ## GMM
  <img width="650" height="780" alt="sanity_check_gmm_mlp" src="https://github.com/user-attachments/assets/342c1460-ad1f-4571-9f0e-50fab3494506" />
  
  ## Laplace
  <img width="650" height="780" alt="sanity_check_laplace_mlp" src="https://github.com/user-attachments/assets/9d92e48f-beb7-4e60-9d45-47e54b572d5c" />
  
  ## Lognormal
  <img width="650" height="780" alt="sanity_check_lognormal_mlp" src="https://github.com/user-attachments/assets/ddfb7928-1554-4510-8ae9-c80a7e42aba4" />
  
  ## Manifold
  <img width="650" height="780" alt="sanity_check_manifold_mlp" src="https://github.com/user-attachments/assets/fa719d87-cc71-41e9-b099-8beb1dbeeb20" />
  
  ## Student's t
  <img width="650" height="780" alt="sanity_check_student_t_mlp" src="https://github.com/user-attachments/assets/170927df-f91c-4666-8798-87096b66809f" />

</details>

<details>
  <summary>Test on Unknown-Noise Setting</summary>
  
  ## W-Gaussian, E-Gaussian
  <img width="845" height="520" alt="config_gaussian_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/0586a23d-d352-45ff-932b-94277b731be2" />
  
  ## W-Gaussian, E-Laplace
  <img width="845" height="520" alt="config_gaussian_x_laplace_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/ac32cf0c-0acb-42c9-8513-084912d1f12a" />
  
  ## W-GMM, E-Gaussian
  <img width="845" height="520" alt="config_gmm_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/b1d1bee4-8f9d-4911-a290-ebc8f7215083" />
  
  ## W-GMM, E-Lognormal
  <img width="845" height="520" alt="config_gmm_x_lognormal_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/eb7b63ba-a816-4b5d-8b87-5ab6c90f2b1e" />
  
  ## W-Manifold, E-Laplace
  <img width="845" height="520" alt="config_student_t_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/3073977c-1dcf-4ce1-ae12-d9fbadb84467" />
  
  ## W-Student's t, E-Gaussian
  <img width="845" height="520" alt="config_manifold_x_laplace_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/6efa2e1f-04e4-4f2d-8f94-25f33abdcc9c" />

</details>





