Mitigating the Discrepancy Between Video and Text Temporal Sequences: A Time-Perception Enhanced Video Grounding method for LLM
Installation 

conda create --name=vtimellm python=3.10
conda activate tpevllm

git clone https://github.com/lixuefenfen/TPE-VLLM.git
cd VTimeLLM
pip install -r requirements.txt

pip install ninja
pip install flash-attn --no-build-isolation

cd VTimeLLM
bash scripts/stage1.sh
bash scripts/stage2.sh
bash scripts/stage3.sh
