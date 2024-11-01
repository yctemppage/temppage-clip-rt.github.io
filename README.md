# CLIP-RT : Learning Language-Conditioned Robotic Policies from Natural Language Supervision

## Abstract
This paper explores how nonexperts can teach robots desired skills in their environments. We argue that natural language is an intuitive and accessible interface for robot learning. To this end, we investigate two key aspects: (1) how nonexperts collect robotic data using natural language supervision and (2) how pre-trained vision-language models learn end-to-end policies directly from this supervision. We propose a data collection framework that collects robot demonstrations based on natural language supervision (e.g., “move forward”) and further augments these demonstrations. Next, we introduce a model that learns language-conditioned policies from natural language supervision called CLIP-RT. Our model employs pre-trained CLIP models and learns to predict actions represented in language via contrastive imitation learning. We first train CLIP-RT on large-scale robotic data and then enable it to learn desired skills using data collected from our framework. CLIP-RT shows strong capabilities in acquiring novel manipulation skills, outperforming the state-of-the-art model, OpenVLA (7B parameters), by 17% in average success rates, while using 7x fewer parameters (1B).

## Citation
If you use CLIP-RT in your research, please cite our work as follows:
```
@article{kang2024cliprt,
  title={CLIP-RT: Learning Language-Conditioned Robotic Policies from Natural Language Supervision},
  author={Kang, Gi-Cheon and Kim, Junghyun and Shim, Kyuhwan and Lee, Jun Ki and Zhang, Byoung-Tak},
  year={2024},
  conference={3rd Workshop on Language and Robot Learning (LangRob) @ The Conference on Robot Learning (CoRL 2024)}
}
```
## Acknowledgements
This work was partly supported by the IITP (RS-2021-II212068-AIHub/10%, RS-2021-II211343-GSAI/20%, 2022-0-00951-LBA/20%, 2022-0-00953-PICA/20%) and NRF (RS-2024-00353991/20%, RS-2023-00274280/10%) grant funded by the Korean government.
