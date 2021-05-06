# Credit-Card-Fraud-Detection

Dataset Used: https://www.kaggle.com/mlg-ulb/creditcardfraud

Train Set: https://drive.google.com/file/d/1CoN9MhHboJxGudsHwMftEsRDi4NEgs09/view?usp=sharing

Test Set: https://drive.google.com/file/d/1pxYp0JNhwcryVu3i8quLamqIR7B3JxRR/view?usp=sharing

Implementation for "Limitations and Applicability of GANs in Banking Domain" http://ceur-ws.org/Vol-2692/paper1.pdf

In this paper, we present a systematic study to train GANs for synthetic fraud generation, demonstrating improved classifier performance detecting fraud. Training of GANs is conducted in various settings, including min-max objective and with or without auxiliary loss
discriminating synthetic fraud and real fraud from non-fraud samples. Auxiliary loss is obtained using contrastive loss or triplet loss.
Quality of trained GANs is estimated by evaluating the lift in classifier performance when trained with dataset augmented with synthetic fraud. Further, the effect of Discriminator Rejection Sampling (DRS) is studied in synthetic sample selection used for training data
augmentation. The performance comparison of different settings proposed in this study is evaluated using a publicly available Credit-Card
dataset and showed an absolute improvement of up to 6% in Recall and 3% in precision.
