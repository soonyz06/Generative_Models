# Can Generative Models Recover Latent Distributions from Repeated Noisy Measurements?
$$W = Z + \varepsilon$$
- Extending normalising flow and GMMN models w/ MMD objectives to the unknown-noise setting 
- Tests are OOS, using recovered empirical distribution (not the explicit density distribution)

<details>
  <summary>Improvements</summary>
  - weibull, etc, Seed? Architecture?, Colours:), dgp, statioarity assumption, log_density
</details>

# Normalizing Flow Model

<img width="507" height="325" alt="summary_bar_chart" src="https://github.com/user-attachments/assets/5b2679dc-65b0-43ea-a1ce-ace92ff6924c" />
<details>
  <summary>Test on No-Noise Setting</summary>
  
  ## Gaussian
  <img width="650" height="780" alt="sanity_check_gaussian_flow" src="https://github.com/user-attachments/assets/5585f87d-25ba-4376-b043-99b78d8f6316" />
  
  ## GMM
  <img width="650" height="780" alt="sanity_check_gmm_flow" src="https://github.com/user-attachments/assets/4e0d1005-f640-432b-94b8-8089dfaf4f62" />
  
  ## Laplace
  <img width="650" height="780" alt="sanity_check_laplace_flow" src="https://github.com/user-attachments/assets/cd40d3cc-c56e-44cd-8801-d698775ca7dd" />
  
  ## Lognormal
  <img width="650" height="780" alt="sanity_check_lognormal_flow" src="https://github.com/user-attachments/assets/276351a5-c927-43a4-8161-6b18395d6be1" />

  ## Manifold
  <img width="650" height="780" alt="sanity_check_manifold_flow" src="https://github.com/user-attachments/assets/a0162a65-44b0-4478-b0c1-e37ba1122c4c" />
  
  ## Student's t
  <img width="650" height="780" alt="sanity_check_student_t_flow" src="https://github.com/user-attachments/assets/a2957788-c005-4306-9ade-92d02b423741" />
</details>

<details>
  <summary>Test on Unknown-Noise Setting</summary>
  
  ## W-Gaussian, E-Gaussian
  <img width="650" height="1560" alt="config_gaussian_x_gaussian_e-flow_z-flow" src="https://github.com/user-attachments/assets/e0f26852-4a6e-4b75-b04d-a04e3f4b9fce" />

  ## W-Gaussian, E-Laplace
  <img width="650" height="1560" alt="config_gaussian_x_laplace_e-flow_z-flow" src="https://github.com/user-attachments/assets/2861eaf5-ac18-4dff-9c09-9b0e4330a6ee" />
  
  ## W-GMM, E-Gaussian
  <img width="650" height="1560" alt="config_gmm_x_gaussian_e-flow_z-flow" src="https://github.com/user-attachments/assets/2449b586-b2f2-40ec-8d30-8447bc65f833" />
  
  ## W-GMM, E-Lognormal
  <img width="650" height="1560" alt="config_gmm_x_lognormal_e-flow_z-flow" src="https://github.com/user-attachments/assets/7cf9d808-cb50-4404-949d-d031b4fd54ce" />
    
  ## W-Manifold, E-Laplace
  <img width="650" height="1560" alt="config_manifold_x_laplace_e-flow_z-flow" src="https://github.com/user-attachments/assets/a003de6a-9c98-478b-8b5c-b3234bf2f1a0" />
  
  ## W-Student's t, E-Gaussian
  <img width="650" height="1560" alt="config_student_t_x_gaussian_e-flow_z-flow" src="https://github.com/user-attachments/assets/0c8a1a3a-bffa-4278-90d0-992f6ec9dcfc" />
</details>

# GMMN

<img width="507" height="325" alt="summary_bar_chart" src="https://github.com/user-attachments/assets/f37694b3-a74a-48e5-9865-91ebf32858d2" />
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
  <img width="650" height="1560" alt="config_gaussian_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/4eaac567-7b29-424d-92b9-f4c2661607ae" />
  
  ## W-Gaussian, E-Laplace
  <img width="650" height="1560" alt="config_gaussian_x_laplace_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/e7d30ea3-d058-41c0-a27e-b1cedfc2da94" />

  ## W-GMM, E-Gaussian
  <img width="650" height="1560" alt="config_gmm_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/8b9947af-72df-44d6-88c3-d9e72fb8321c" />

  ## W-GMM, E-Lognormal
  <img width="650" height="1560" alt="config_gmm_x_lognormal_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/c5f39864-77fd-46fe-822a-99eb6771915e" />
  
  ## W-Manifold, E-Laplace
  <img width="650" height="1560" alt="config_manifold_x_laplace_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/04a4bb9d-8c03-420d-a9ac-8f097f91d50e" />

  ## W-Student's t, E-Gaussian
  <img width="650" height="1560" alt="config_student_t_x_gaussian_e-mlp_z-mlp" src="https://github.com/user-attachments/assets/8818a211-eab5-4082-8705-34398b156c87" />

</details>





