
<div>
  <div align="center">
    <h2 style="margin-bottom: 20px;">Introduction</h2>
  </div>
  <p style="text-align: justify;">
    Recent advancements in non-autoregressive audio generation have garnered significant attention. However, traditional single-task speech synthesis methods focus primarily on mapping semantic tokens to acoustic tokens, overlooking the internal relationships within acoustic features. Addressing this gap, we introduce SpeechSEC, a unified multi-task framework designed for Speech Synthesis, Editing, and Continuation tasks by dynamically adjusting input conditions.SpeechSEC not only enhances speech synthesis performance in speech intelligibility, audio quality, and voice preservation by acquiring shared and diverse knowledge across different tasks, but also efficiently executes editing and continuation tasks with good performance via non-autoregressive techniques. Additionally, SpeechSEC exhibits a strong adaptability to current speech discretization methods, like Hubert, Descript-Audio-Codec, and SpeechTokenizer, which showcases the robustness of our approach. Audio samples are available.
  </p>
</div>

<div align="center">
  <h2>Model Structure</h2>
</div>
![示例图片](./images/0311_06.png)

<div align="center">
  <h2>Contribution</h2>
</div>

- We improve speech synthesis performance through multi-task joint training in aspects including speech intelligibility, voice preservation, audio quality with fast speed utilizing non-autoregressive methods.
- We propose a multi-task audio processing framework that can efficiently accomplish high-quality speech synthesis, speech editing and speech continuation tasks in a non-autoregressive manner through a single unified model, bringing innovation to the field of audio processing.
- We verify the adaptability of different discretion methods of speech processing and demonstrated that the multi-task joint training method we proposed is effective for different extractors of semantic tokens and acoustic tokens which showcases the wide applicability and robustness of our method.

<div align="center">
  <h2>Demos</h2>
</div>
Here are some demos of our speech synthesis system. You can click the audio files below to listen to examples

### SpeechSEC_SpeechSynthesis 

<div align="center">
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/1_SpeechSEC_SpeechSynthesis/1.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/1_SpeechSEC_SpeechSynthesis/2.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/1_SpeechSEC_SpeechSynthesis/3.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/1_SpeechSEC_SpeechSynthesis/4.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/1_SpeechSEC_SpeechSynthesis/5.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>

### SpeechSEC_SpeechEditing

### SpeechSEC_SpeechContinuation

<div align="center">
    <!-- 第一行 2 个音频 -->
    <audio controls>
        <source src="https://raw.githubusercontent.com/your-username/your-repository/main/path-to-audio-file/audio1.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://raw.githubusercontent.com/your-username/your-repository/main/path-to-audio-file/audio2.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>

<br>

<div align="center">
    <!-- 第二行 2 个音频 -->
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/3_SpeechSEC_SpeechContinuation/1.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://github.com/CL0077/SpeechSEC/blob/gh-pages/docs/demo-main/demo-main/3_SpeechSEC_SpeechContinuation/1_ContinueResult.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>

