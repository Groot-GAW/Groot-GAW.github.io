{:.no_toc}
* toc
{:toc}

# Groot: Generating Robust Watermark for Diffusion-Model-Based Audio Synthesis

## Audio Demo
### Single-Speaker Datasets (LJSpeech)

<table>
  <thead>
     <th style="text-align: center">DiffWave</th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/ljs/ljs_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/ljs/ljs1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/ljs/ljs2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/ljs/ljs3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/ljs/ljs4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/ljs/ljs5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
     <th style="text-align: center">WaveGrad</th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/wavegrad/ljs_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/wavegrad/ljs1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/wavegrad/ljs2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/wavegrad/ljs3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/wavegrad/ljs4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/wavegrad/ljs5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
     <th style="text-align: center">PriorGrad</th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/priorgrad/ljs_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/priorgrad/ljs1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/priorgrad/ljs2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/priorgrad/ljs3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/priorgrad/ljs4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/priorgrad/ljs5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>



### Multi-Speaker Datasets (LibriTTS)
<table>
  <thead>
     <th style="text-align: center">DiffWave</th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lts/lts_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/lts/lts1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lts/lts2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lts/lts3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lts/lts4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lts/lts5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>


### Multi-Speaker Datasets (LibriSpeech)
<table>
  <thead>
     <th style="text-align: center">DiffWave</th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/lbs/lbs_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/lbs/lbs1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lbs/lbs2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lbs/lbs3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lbs/lbs4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/lbs/lbs5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>


### Multi-Speaker Datasets (Aishell3)
<table>
  <thead>
     <th style="text-align: center"></th>
     <th style="text-align: center">Demo1</th>
     <th style="text-align: center">Demo2</th>
     <th style="text-align: center">Demo3</th>
     <th style="text-align: center">Demo4</th>
     <th style="text-align: center">Demo5</th>
  </thead>
  <tbody>
    <tr>
      <th>Generated</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_generated1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_generated2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_generated3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_generated4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_generated5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Watermarked</th>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_watermarked1.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_watermarked2.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_watermarked3.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_watermarked4.wav" type="audio/wav"></audio></td>
      <td style="text-align: center"><audio controls style="width: 150px;"><source src="audio/asl/asl_watermarked5.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>Mel</th>
      <td style="text-align: center"><img src="audio/asl/asl1.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/asl/asl2.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/asl/asl3.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/asl/asl4.png" alt="Description" style="width: 100%; height: 100%;"></td>
      <td style="text-align: center"><img src="audio/asl/asl5.png" alt="Description" style="width: 100%; height: 100%;"></td>
    </tr>
  </tbody>
</table>

