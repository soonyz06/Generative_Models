# Can Generative Models Recover Latent Distributions from Repeated Noisy Measurements?
- Extending flow-based generative deconvolution models (MMD) to the unknown-noise setting
<details>
  <summary>Improvements</summary>
  - OOS? Seed? Architecture?
</details>

# Test on No-Noise Setting

<details>
  <summary>Results</summary>
  
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

# Test on Unknown-Noise Setting

<details>
  <summary>Results</summary>
  
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




