# 1. Harness_Patch  
## Checkout harness  
git clone https://github.com/EleutherAI/lm-evaluation-harness  
cd lm-evaluation-harness  
git checkout 091aaf6f31f3e87e81135a5d204c30707711d94a  
## Apply harness patch  
curl -fSL -O https://raw.githubusercontent.com/shawn9977/Harness-Lighteval_Patch/main/0001-My-custom-modifications-for-patch.patch  
git apply --check 0001-My-custom-modifications-for-patch.patch  
git apply 0001-My-custom-modifications-for-patch.patch  



  

# 2. Lighteval_Patch  
## Checkout lighteval  
git clone https://github.com/huggingface/lighteval.git  
cd lighteval  
git checkout d805f9fa0a84da9ca4c0c6a638bbed149a7012a3  
## Apply lighteval patch  
curl -fSL -O https://raw.githubusercontent.com/shawn9977/Harness-Lighteval_Patch/main/0002-My-custom-modifications-for-patch.patch    
git apply --check 0002-My-custom-modifications-for-patch.patch      
git apply 0002-My-custom-modifications-for-patch.patch      
