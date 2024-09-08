## hi

## introduction
Recent advancements in non-autoregressive audio generation have garnered significant attention. However,traditional single-task speech synthesis methods focus primarily on mapping semantic tokens to acoustic tokens, which overlooking the internal relationships within acoustic features. Addressing this gap, we introduce SpeechSEC, a unified multi-task framework designed for Speech Synthesis, Editing, and Continuation tasks by dynamically adjusting input conditions. SpeechSEC not only enhances speech synthesis performance in speech intelligibility, audio quality, voice preservation by acquiring shared and diverse knowledge across different tasks,  but also efficiently executes editing and continuation tasks with good performance via non-autoregressive techniques. Additionally, SpeechSEC exhibits a strong adaptability to current speech discretization methods, like Hubert, Descript-Audio-Codec and SpeechTokenizer, which showcases robustness of our approach. Audio samples are available.

## 框架图
![示例图片](./images/0311_06.png)

## 创新点描述
- We improve speech synthesis performance through multi-task joint training in aspects including speech intelligibility, voice preservation, audio quality with fast speed utilizing non-autoregressive methods.
- We propose a multi-task audio processing framework that can efficiently accomplish high-quality speech synthesis, speech editing and speech continuation tasks in a non-autoregressive manner through a single unified model, bringing innovation to the field of audio processing.
- We verify the adaptability of different discretion methods of speech processing and demonstrated that the multi-task joint training method we proposed is effective for different extractors of semantic tokens and acoustic tokens which showcases the wide applicability and robustness of our method.

## Demos
Here are some demos of our speech synthesis system. You can click the audio files below to listen to examples

### SpeechSEC_SpeechSynthesis 
<div align="center">
    <audio controls>
        <source src="https://example.com/audio1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://example.com/audio2.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://example.com/audio3.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://example.com/audio4.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="https://example.com/audio5.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>

### SpeechSEC_SpeechEditing

### SpeechSEC_SpeechContinuation
