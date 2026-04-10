
### [Evaluation and Benchmarking of LLM Agents: A Survey](https://arxiv.org/abs/2507.21504)
Добротная обзорная статья. Понравилось,что для многочисленных заданий предлагаются подходящие метрики.
Evaluation Process раскладывается в следующий пайплайн

Сложности в ролевой модели доступа, надёжности, более-менее сложных взаимодействиях и правовых ограничениях. Ожидаемо. 

![Agent taxonomy](pic/taxonomy.png "Entity diagram")

🔘 какие измерения вообще входят в оценку агентов, кроме task success;
🔘 как можно раскладывать evaluation process на interaction mode, benchmark, metric и tooling;
🔘 в чем agent evaluation до сих пор остается фрагментированной и методологически недостроенной областью.

____
### [Towards a Science of AI Agent Reliability](https://arxiv.org/html/2602.16666v1)

🔘почему оценку безопасности нельзя усреднять, если речь идет о tail risks;
🔘как reliability framework меняет сам вопрос интерпретации результатов оценки.

_______
### [METR: Guidelines for capability elicitation](https://evaluations.metr.org/elicitation-protocol/)

🔘 почему agent evaluation может занижать реальные возможности модели, если не учитывать elicitation;
🔘 как использовать dev set не только для улучшения агента, но и для классификации типов провалов;
🔘 чем spurious failure отличается от real failure и tradeoff;
🔘 какие red flags стоит проверять, прежде чем интерпретировать итоговый score как meaningful.