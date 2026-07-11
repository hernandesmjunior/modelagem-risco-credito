<img src="imagens/capa.jpg" width="100%">

<h1 style="font-size: 56px; font-weight: 900; letter-spacing: 0px; margin: 0;"><span style="color: rgb(166, 108, 255);">MODELO</span> DE RISCO DE CRÉDITO</h1>
<br>
<p>O presente trabalho utiliza o benchmark público <strong>German Credit</strong> para desenvolver um modelo que identifica quais clientes possuem probabilidade de "dar default", ou seja, não cumprir com suas obrigações em um contrato de empréstimo financeiro. O problema é de classificação binária, mas o que separa um classificador qualquer de um trabalho de risco de crédito é a higiene de validação, a interpretabilidade exigida por regulação e o custo assimétrico do erro. Aprovar um mau pagador custa o principal emprestado; reprovar um bom pagador custa uma margem. Os dois erros não valem o mesmo, e o modelo precisa refletir isso.

</p>
<br>
Ilustração de capa: Dmitrii Kharchenko.
<br>
<br>

<div style="background:#faf7ff;padding:6px 26px;margin:18px 0;">
<p style="font-weight:800;margin-bottom:4px;">ROTEIRO</p>
<ol style="color:#2D2A32;line-height:1.7;">
<li>Problema de negócio</li>
<li>Importando bibliotecas</li>
<li>Conjunto de dados</li>
<li>Análise exploratória</li>
<li>Qualidade dos dados e valores ausentes</li>
<li>Partição treino / teste</li>
<li>Weight of Evidence e Information Value</li>
<li>Pré-processamento como pipeline</li>
<li>Modelagem: baseline logístico e challenger XGBoost</li>
<li>Avaliação: ROC, KS, Gini, matriz de confusão e escolha de corte</li>
<li>Interpretação e scorecard (PDO)</li>
<li>Conclusão</li>
</ol></div>
