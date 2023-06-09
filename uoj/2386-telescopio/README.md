<p><a href="https://www.beecrowd.com.br/repository/UOJ_2386_en.html">beecrowd.com.br/repository/UOJ_2386_en.html</a></p><hr>
<div>
  <span>URI Online | 2386</span>
  <h1>Telescópio</h1>
  <div>
    <p>Por OBI - Olimpíada Brasileira de Informática, 2010 <img src="https://resources.beecrowd.com.br/gallery/images/flags/br.gif" alt="BR"> Brazil</p>
  </div>
  <strong>Timelimit: 1</strong>
</div>
<div>
<div>
  <p>Telescópios são instrumentos que auxiliam a observação do céu, melhorando e aumentando o aspecto das estrelas, planetas e outros objetos brilhantes. Existem diversos tipos de telescópios, sendo os tipos mais comuns os de lentes objetivas (refratores) e os de espelhos (refletores).</p>
  <p>A maneira como os telescópios melhoram a nossa percepção dos astros no céu é aumentando a quantidade de luz captada que chega aos nossos olhos. Toda luz que entra pelos nossos olhos entra por um orifício chamado pupila. Tal controla a quantidade de luz que entra nos olhos, aumentando o diâmetro quando o ambiente está escuro (e portanto precisamos obter mais luz para identificar os objetos) e diminuindo quando o ambiente está claro. Num ambiente muito escuro, a pupila pode atingir um diâmetro de 8 mm.</p>
  <p>Cada objeto celeste (estrela, planeta, nebulosa, etc) emite uma quantidade de luz (fótons) que é homogeneamente distribuída quando chega na Terra. Por exemplo, a estrela A emite luz que pode ser captada a um fluxo de 40.000 fótons por segundo por milímetro quadrado. Isso é, a cada segundo, é possível captar 40.000 fótons provenientes da estrela A numa área de 1 mm 2. Ou seja, uma pupila de 10 mm 2 de área captaria 400.000 fótons provenientes da estrela A por segundo.</p>
  <p>Para que nosso cérebro consiga interpretar que existe um objeto ali, porém, ele precisa receber 40.000.000 fótons por segundo. Assim, podemos utilizar um telescópio com lente (ou espelho) de 100 mm 2 de área, que vai captar a quantidade necessária de fótons provenientes da estrela A e encaminhá-los até nossa pupila, fazendo assim com que nosso cérebro perceba a presença da estrela ali.</p>
  <p>Dada uma lista com estrelas no céu, o fluxo de fótons que cada uma delas emite, e área de abertura de um telescópio, dizer quantas estrelas serão perceptíveis usando tal telescópio.</p>
</div>
<h2>Entrada</h2>
<div>
  <p>A primeira linha da entrada terá um inteiro <strong>A</strong> (1 ≤ <strong>A</strong> ≤ 10.000) representando a área de abertura do telescópio (em milímetros quadrados) a ser considerado. A segunda linha possui um inteiro <strong>N</strong> (1 ≤ <strong>N</strong> ≤ 10.000) representando o número de estrelas a serem estudadas. As <strong>N</strong> linhas seguintes terão, cada uma, um inteiro <strong>F</strong> (1 ≤ <strong>F</strong> ≤ 20.000) representando o fluxo de fótons que cada uma das <strong>N</strong> estrelas emitem (em fótons por segundo por milímetro quadrado).</p>
</div>
<h2>Saída</h2>
<div>
  <p>Imprima um inteiro representando a quantidade de estrelas que serão percebidas ao se utilizar o telescópio em questão.</p>
</div>
<div></div>
<table>
  <thead>
    <tr>
      <td>Exemplos de Entrada</td>
      <td>Exemplos de Saída</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <p>10000</p>
        <p>3</p>
        <p>4000</p>
        <p>3500</p>
        <p>5100</p>
      </td>
      <td>
        <p>2</p>
      </td>
    </tr>
  </tbody>
</table>
<div></div>
<table>
  <thead>
  </thead>
  <tbody>
    <tr>
      <td>
        <p>5869</p>
        <p>3</p>
        <p>3975</p>
        <p>14234</p>
        <p>8569</p>
      </td>
      <td>
        <p>2</p>
      </td>
    </tr>
  </tbody>
</table>
<div></div>
  <table>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td>
          <p>2967</p>
          <p>9</p>
          <p>18650</p>
          <p>18338</p>
          <p>2400</p>
          <p>17702</p>
          <p>14619</p>
          <p>13934</p>
          <p>7979</p>
          <p>16316</p>
          <p>10533</p>
        </td>
        <td>
          <p>6</p>
        </td>
      </tr>
    </tbody>
  </table>
  <p>
  OBI - Olimpíada Brasileira de Informática - 2010 Fase 2 Modalidade Nível 2 (P2)</p>
</div>