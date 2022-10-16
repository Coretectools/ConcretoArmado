<!-- Não apagar este bloco-->
<!-- início do bloco de algoritmo-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!-- fim do bloco de algoritmo-->

<h1>Comprimento de ancoragem necessário (\(l_{b,nec}\))</h1>

<p align="justify">
Para o cálculo do comprimento de ancoragem, é preciso obter a tensão de aderência de cálculo (\(f_{bd}\)), que depende de alguns fatores, tais como: (a) o tipo da barra, se é lisa ou nervurada (fator \(η_1\)), (b) a posição da barra na geometria da peça (fator \(η_2\)), (c) diâmetro da barra (fator \(η_3\)), além da (d) resistência de cálculo do concreto à tração de cálculo (\(f_{ctd}\)). O cálculo da tensão \(f_{bd}\) é dado conforme equação (1):
</p> 

<table width = "100%" border = "0">
    <tr>
        <td width = "90%">
            <p>\[f_{bd}=η_1.η_3.η_3.f_{ctd}\]</p>
        </td>
        <td width = "10%">
            <p align="right">(1)</p>
        </td>
    </tr>
</table>

<ul>
    <li>\(\eta_1\) = 1,00 para barras lisas;</li>
    <li>\(\eta_1\) = 1,40 para barras entalhadas;</li>
    <li>\(\eta_1\) = 2,25 para barras nervuradas;</li>
    <li>\(\eta_2\) = 1,00 para situações de boa aderência;</li>
    <li>\(\eta_2\) = 0,70 para situações de má aderência;</li>
    <li>\(\eta_3\) = 1,00 para \(\phi_l < 32 mm\);</li>
    <li>\(\eta_3\) = \(\frac{132-\phi_l}{100}\) para \(\phi_l \geq 32 mm\).</li>
</ul>

<p align="justify">
A resistência do concreto à tração de cálculo (\(f_{ctd}\)) se dá através da equação (2) onde \(f_{ctk,inf\) é a resistência caracterísitca à tração direta do concreto para o quantil inferior (\(f_{ctk,inf}=0,21.\sqrt[3]{f_{ck}^{2}}\)) e \(\gamma_c=1,40\).
</p> 

<table width = "100%" border = "0">
    <tr>
        <td width = "90%">
            <p>\[f_{ctd}=\frac{f_{ctk,inf}}{\gamma_c}\]</p>
        </td>
        <td width = "10%">
            <p align="right">(2)</p>
        </td>
    </tr>
</table>

<p align="justify">
A partir disso, tem-se o comprimento básico de ancoragem (\(l_b\)), que tem que deverá ser maior ou igual a \(25.\phi_l\) conforme equação (3). Já a equação (4) apresenta o comprimento de ancoragem necessário (\(l_{b,nec}\)):
</p> 

<table width = "100%" border = "0">
    <tr>
        <td width = "90%">
            <p>\[l_{b}=\frac{\phi}{4}.\frac{f_{yd}}{f_{bd}} \geq 25.\phi\]</p>
        </td>
        <td width = "10%">
            <p align="right">(3)</p>
        </td>
    </tr>
    <tr>
        <td width = "90%">
            <p>
                  \[l_{b,nec}=\alpha.l_{b}.\frac{A_{s,calc}}{A_{s,ef}}\geq \left\{\begin{matrix}0,30.l_b
                  \\10.\phi 
                  \\100 mm 
                  \end{matrix}\right.\]
            </p>
        </td>
        <td width = "10%">
            <p align="right">(4)</p>
        </td>
    </tr>
</table>

<ul>
    <li>\(\alpha\) = 0,70 sem gancho;</li>
    <li>\(\alpha\) = 1,00 com gancho;</li>
    <li>\(A_{s,calc}\) - Área de aço calculada;</li>
    <li>\(A_{s,ef}\) - Área de aço efetiva.</li>
</ul>

<h2>Exemplo resolvido</h2>

<p align="justify">
Determinar o comprimento de ancoragem básico (\(l_b\)) de uma barra de aço de 16,00 mm sujeita a situações de boa e má aderência em uma peça de concreto com \(f_{ck}\) = 25 MPa.
</p>

<p align="justify">
Para avaliarmos o comprimento básico de ancoragem é necessário determinar as incógnitas da equação (1). Os termos \(\eta\) podem ser dados como:
</p>

<ul>
    <li>\(\eta_1\) = 2,25 para barras nervuradas como é o caso do CA-50;</li>
    <li>\(\eta_2\) = 1,00 para situações de boa aderência;</li>
    <li>\(\eta_2\) = 0,70 para situações de má aderência;</li>
    <li>\(\eta_3\) = 1,00 para \(\phi_l < 32 mm\);</li>
</ul>

<p align="justify">
Determinando a resistência de cálculo à tração e o comprimento de ancoragem básico:
</p>

\[f_{ctd}=\frac{0,21.\sqrt[3]{25^{2}}}}{\gamma_c}=1,28\]  
\[f_bd=2,25.\eta_2.1.1,28=2,88.\eta_2\]  
\[l_{b}=\frac{\phi}{4}.\frac{f_{yd}}{f_{bd}} \geq 25.\phi\]  
