# Termite: Dataset for Investigating the Impact of Data Contamination of Large Language Models in Text-to-SQL translation #

Understanding textual description to generate code seems to be an achieved capability of instruction-following Large Language Models (LLMs) in zero-shot scenario. However, there is a severe possibility that this translation ability may be influenced by having seen target textual descriptions and the related code. This effect is known as _Data Contamination_.

In our study "Investigating the Impact of Data Contamination of Large Language Models in Text-to-SQL translation", accepted as ACL Findings, we investigate the impact of Data Contamination on the performance of GPT-3.5 in the Text-to-SQL code-generating tasks.
Hence, we introduce a novel method to detect Data Contamination in GPTs and examine GPT-3.5's Text-to-SQL performances using the known Spider Dataset and our new unfamiliar dataset Termite.
Furthermore, we analyze GPT-3.5's efficacy on databases with modified information via an adversarial table disconnection (ATD) approach, complicating Text-to-SQL tasks by removing structural pieces of information from the database.
Our results indicate a significant performance drop in GPT-3.5 on the unfamiliar Termite dataset, even with ATD modifications, highlighting the effect of Data Contamination on LLMs in Text-to-SQL translation tasks.

You can find our dataset in the [Termite.zip](https://github.com/ART-Group-it/Termite/blob/main/Termite.zip): the password to access the data is, as indicated also in the name of the file, "youshallnotpass".
