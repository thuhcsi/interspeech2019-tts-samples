Samples for paper [Knowledge-based Linguistic Encoding for End-to-End Mandarin Text-to-Speech Synthesis](https://github.com/thuhcsi/interspeech2019-tts-samples/raw/master/1118_Paper.pdf) at INTERSPEECH 2019
====

## Sample 1

* __Text__ (Chinese): 徐文跟我们分享一下你的答案吧。
> (English Translation): Xu Wen please share your answer with us.

* Sythesized audios:
Baseline approach:
<audio controls>
  <source src="sample1-baseline.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

Proposed approach:

<audio controls>
  <source src="sample1-proposed.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

* Explanation:

The baseline approach has word tokenization error around the 3-rd character,
resulting in pause deletion between the 2-nd and the 3-rd characters and improper pause insertion between the 3-rd and 4-th characters.
The baseline approach also has syllable pronunciation error at the 8-th character,
incorrectly predicting the pronunciation of the character from `yi2` to `yi4`.

The proposed system has synthesized the speech with expected pronunciations and pauses.
