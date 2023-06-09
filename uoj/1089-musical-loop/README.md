<p><a href="https://www.beecrowd.com.br/repository/UOJ_1089_en.html">beecrowd.com.br/repository/UOJ_1089_en.html</a></p><hr>
    <div>
    <span>URI Online | 1089</span>
    <h1>Musical Loop</h1>
    <div><p>
       By Ricardo Anido&nbsp;<img alt="" src="https://resources.beecrowd.com.br/gallery/images/flags/br.gif" style="width: 16px; height: 11px;">&nbsp;Brazil</p></div>
      <strong>Timelimit: 1</strong>
    </div>
    <div>
    <div>
      <p>
       A <i>musical loop</i> is a small section of music composed to be played continuously (that is, the section is played again when it reaches the end), in a seamless way. Loops are used in many styles of popular music (hip hop, techno, etc), as well in computer games, especially casual games on the Internet.</p>
      <p>
       Loops may be digitalized for example using PCM (Pulse Code Modulation), a technique for representing analog signals used extensively in digital audio. In PCM, the magnitude of the signal is sampled at regular intervals, and the values sampled are stored in sequence. To produce the sound for the sampled data, the procedure is applied in reverse (demodulation).</p>
      <p>
       Fernanda works for a game software house, and composed a beautiful musical loop, coded in PCM. Analyzing the waveform of her loop in audio editing software, Fernanda became curious when she noticed the number of "peaks". A <i>peak</i> in a waveform is the value of a sample that represents a local maximum or minimum. The figure below illustrates (a) a waveform and (b) the loop formed with this waveform, containing 48 peaks.</p>
      <p>
      <img alt="" src="https://resources.beecrowd.com.br/gallery/images/problems/UOJ_1089_en.png" style="width: 533px; height: 338px;"></p>
      <p>
       Fernandinha is a dear friend of yours. She has asked your help to determine how many peaks exist in her musical loop.</p>
    </div>
    <h2>Input</h2>
    <div>
      <p>
       The input contains several test cases. The first line of a test case contains one integer <em><strong>N</strong></em>, representing the number of samples in the musical loop composed by Fernanda (<i>2 ≤ N ≤ 10<sup>4</sup></i>). The second line contains <i>N</i> integers <i>H<sub>i</sub></i>, separated by spaces, representing the sequence of magnitudes sampled (<i>-10<sup>4</sup> ≤ H<sub>i</sub> ≤ 10<sup>4</sup></i> for <i>1 ≤ i ≤ N</i>, <i>H<sub>1</sub> ≠ H<sub>N</sub></i> and <i>H<sub>i</sub> ≠ H<sub>i+1</sub></i> for <i>1 ≤ i &lt; N</i>). Notice that <i>H<sub>1</sub></i> follows <i>H<sub>N</sub></i> when the loop is played.</p>
      <p>
       The end of the input is indicated by a line that contains only one zero.</p>
    </div>
    <h2>Output</h2>
    <div>
      <p>
       For each test case in the input your program must print a single line, containing one integer, the number of peaks that exist in the musical loop.</p>
    </div>
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
           2<br>
           1 -3<br>
           6<br>
           40 0 -41 0 41 42<br>
           4<br>
           300 450 449 450<br>
           0</p>
        </td>
        <td>
          <p>
           2<br>
           2<br>
           4</p>
        </td>
      </tr>
    </tbody>
  </table> <p>
   Maratona de Programação da SBC 2008.</p>
</div>