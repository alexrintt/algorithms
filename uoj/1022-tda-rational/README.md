<p><a href="https://www.beecrowd.com.br/repository/UOJ_1022_en.html">beecrowd.com.br/repository/UOJ_1022_en.html</a></p><hr>
  <div>
    <span>URI Online | 1022</span>
    <h1>TDA Rational</h1>
    <div><p>
       By Neilor Tonin, URI <img alt="" src="https://resources.beecrowd.com.br/gallery/images/flags/br.gif" style="width: 16px; height: 11px; "> Brazil</p>
    </div>
    <strong>Timelimit: 1</strong>
  </div>
  <div>
  <div>
    <p>
     You were invited to do a little job for your Mathematic teacher. The job is to read a Mathematic expression in format of two rational numbers (numerator / denominator) and present the result of the operation. Each operand or operator is separated by a blank space. The input sequence (each line) must respect the following format: number, (‘/’ char), number, operation char (‘/’, ‘*’, ‘+’, ‘-‘), number, (‘/’ char), number. The answer must be presented followed by ‘=’ operator and the simplified answer. If the answer can’t be simplified, it must be repeated after a ‘=’ operator. </p>
    <p>
     Considering N1 and D1 as numerator and denominator of the first fraction, follow the orientation about how to do each one of these 4 operations:</p>
    <p>
     Sum: (N1*D2 + N2*D1) / (D1*D2)<br>
     Subtraction: (N1*D2 - N2*D1) / (D1*D2)<br>
     Multiplication: (N1*N2) / (D1*D2)<br>
     Division: (N1/D1) / (N2/D2), that means (N1*D2)/(N2*D1)</p>
  </div>
  <h2>Input</h2>
  <div>
    <p>
     The input contains several cases of test. The first value is an integer <strong>N </strong>(1 ≤ <strong>N </strong>≤ 1*10<sup>4</sup>), indicating the amount of cases of test that must be read. Each case of test contains a rational value <strong>X </strong>(1 ≤ <strong>X </strong>≤ 1000), an operation (-, +, * or /) and another rational value <strong>Y </strong>(1 ≤ <strong>Y </strong>≤ 1000).<br> </p>
  </div>
  <h2>Output</h2>
  <div>
  <p>
   The output must be a rational number, followed by a “=“ sign and another rational number, that is the simplification of the first value. In case of the first value can’t be simplified, the same value must be repeated after the ‘=’ sign.<br>
</p></div>
<div></div>
  <table>
    <thead>
      <tr>
        <td>Input Sample</td>
        <td>Output Sample</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <p>
           4<br>
           1 / 2 + 3 / 4<br>
           1 / 2 - 3 / 4<br>
           2 / 3 * 6 / 6<br>
           1 / 2 / 3 / 4</p>
        </td>
        <td>
          <p>
           10/8 = 5/4<br>
           -2/8 = -1/4<br>
           12/18 = 2/3<br>
           4/6 = 2/3</p>
        </td>
      </tr>
    </tbody>
  </table>
</div>